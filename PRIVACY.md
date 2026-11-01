# Salah Bar for Android: Privacy Policy

*Last updated: 31 October 2026*

**In short: Salah Bar collects nothing.** There are no accounts, no analytics, no ads and no
tracking. Your settings, your location and your prayer log stay on your phone, unless you choose
to sync them through your own Google Drive or a file in your own cloud drive (or open Nearby mosques, which asks
OpenStreetMap for the mosques around you, or a map, which loads map images of that area). The
developer never receives any of your data. The one exception, off until you turn it on, is the
weather: then your location, rounded to about 10 km, goes to Open-Meteo (see below).

## What stays on your phone

- **Your location.** With your permission, Android tells Salah Bar your location, to
  calculate prayer times and the Qibla direction (an approximate location is enough; Nearby mosques
  uses your precise location, if you allow it, to tell which mosque is nearest). The calculation happens on your phone. The
  place name (such as "Manisa, TR") and its time zone come from a list of cities built into the
  app, so your location is never sent anywhere to be named. Salah Bar keeps your last location
  on your phone so the times are right the next time it opens. Your location is never synced
  to a cloud drive.
- **Your watch.** If you install Salah Bar on a Wear OS watch, your phone hands it your
  settings, the city on show (with its location) and the prayers you marked around today, so
  the watch can calculate the times for its tile and complications; prayers you mark on the
  watch go back to your phone's prayer log. They go over Wear OS's own phone-to-watch connection (Google Play
  services), which may carry them through Google's servers when the watch is connected by Wi-Fi
  rather than Bluetooth. Nothing reaches the developer. On a watch with GPS, the watch's Qibla
  can use the watch's own location if you allow it on the watch: it's used on the watch only,
  never sent to your phone or anywhere else, and left out of backups.
- **The camera (only if you use it).** The Qibla screen's Camera view shows what your rear camera sees with the Qibla drawn over it, and Settings → Iqama → Scan QR code reads your mosque's QR code on the phone; the picture stays on screen and is never stored or sent.
- **Your settings**, your saved cities, your prayer log, your Ramadan log, where you stopped in
  each surah, and any adhans and recitations you download.
- **Whether you're busy.** To keep the adhan quiet during a call, or when the phone is on silent
  or Do Not Disturb, Salah Bar checks at prayer time whether a call is in progress and how the
  ringer is set. It never listens to or records anything, and stores nothing about it.
- **Your calendar (only if you turn it on).** In Settings → Calendar you can let Salah Bar read
  your calendar's events, to warn you about meetings that overlap a prayer, and write prayer
  blocks into a calendar you choose. The events are read on your phone and never sent anywhere.
  Salah Bar only ever changes or deletes the prayer blocks it created. If the calendar you choose
  syncs to an account (such as Google Calendar), that account's service receives the blocks, as
  with any event you add.
- **Do Not Disturb during prayer (only if you turn it on).** In Settings → Reminders you can let
  Salah Bar turn on Do Not Disturb for a few minutes at each prayer you choose. Android asks you
  to allow Do Not Disturb access first. Salah Bar only turns on its own quiet time and puts the
  phone back as it was afterwards; it keeps nothing about it but the current quiet time.
- **For sisters (only if you choose Sister).** The excused days you log (when they started and
  ended, and whether after childbirth), pregnancy and nursing if you set them, and the fasts you
  have to make up are kept on your phone, to tell which prayers are excused and to predict the next
  start. Notifications, widgets and the watch never mention them.
- **Health Connect (only if you turn it on).** In Settings → For sisters you can link Salah Bar
  with Health Connect, after Android asks your permission. Salah Bar then reads the menstruation
  periods of the last 180 days recorded there, so the prayers of those days count as excused, and
  writes the excused days you finish logging as menstruation periods. This data is used only for
  that: it is never sent to the developer or anyone else, never used for advertising, and never
  sold. You can remove the permission at any time in Health Connect.
- **The Tasbih counter** is kept on your phone; it isn't synced.
- **Reminders** are scheduled on your phone with Android's alarms and shown as notifications on
  your phone.

## Sync (only if you turn it on)

**With Google Drive.** In Settings → Sync and backup you can tap *Sign in with Google*. Salah Bar
then asks Google for one permission only, to keep its own file in your Google Drive's hidden app
folder (the `drive.appdata` scope): it can't see, open or change any of your other files in Drive.
It keeps the same sync file described below there, `Salah Bar sync.json`, sending it straight from
your phone to your own Google Drive over HTTPS; there is no Salah Bar server in between, and the
developer never sees the file or your account. Signing in is handled by Google Play services, which
keeps the permission; Salah Bar stores only your account's email address on the phone, to show it
and to sync in the background. Google's privacy policy applies to your Google account and Drive.
*Sign out* takes this phone's data out of the file and stops syncing here; *Remove my data from
Drive* deletes the file from your Drive (every device's data in it) and takes Salah Bar's access
away. You can also remove Salah Bar's access at any time from your Google Account
(Security → Third-party apps), and Drive → Settings → Manage apps lets you delete its hidden data.
Salah Bar's use and transfer to any other app of information received from Google APIs will adhere
to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements: it only reads and writes its own sync file in your Drive,
to sync your devices, and never uses it for anything else or passes it to anyone.

**With a file.** In Settings → Sync and backup you can instead choose a file in a cloud drive you already use (Google
Drive, OneDrive, Nextcloud or any app that appears in Android's file picker). Salah Bar then
writes your settings, saved cities, prayer log, Ramadan log, excused days (For sisters), Khatma progress and Quran places to that file, with
your phone's name (as set in Android's settings) so your other devices can show where the data
came from, and reads what your other devices wrote there. The file goes only where you put it:
Salah Bar has no server, and the developer never sees it. Your cloud drive's own privacy policy
applies to the file. "Stop syncing" takes this phone's data out of the file. **Export** writes the
same data to a file you choose, and **Import** reads one back.

## Android's backup

If backup is turned on in your phone's settings, Android may include Salah Bar's settings, logs
and downloaded adhans in your phone's backup to your Google account, as it does for most apps, so
they come back on a new phone. Salah Bar leaves its Quran downloads, its sync link and its Health Connect link out
of that backup. You can turn backup off in Android's settings.

## What goes over the internet

Salah Bar only connects to the services below, and only for the feature named. None of them
receives your name, your settings or an account, and only OpenStreetMap and the Overpass API (for
Nearby mosques), OpenFreeMap (for the maps) and Open-Meteo (for the weather, if you turn it on) receive a location, but like any web request each
sees your phone's IP address.

| Service | When | What it receives |
|---|---|---|
| **mp3quran.net** | When you use the Quran tab: the list of reciters (at most once a week), the surahs you play or download, and ayah timings for Hifz | Requests for those files |
| **EveryAyah.com** | Hifz with recitations it serves ayah by ayah | Requests for those ayahs' files |
| **hisnmuslim.com** | When you listen to a dua read by Hamad al-Duraihim (the default reciter), or by another reciter who has no recording of it | A request for that dua's recording |
| **IslamHouse.com** | When you listen to a dua read by Sulayman al-Shuwaihi or Walid Abu Ziyad (Duas → Reading and voice) | A request for the reciter's file that holds that dua |
| **archive.org** (the Internet Archive) | When you listen to a dua read by Abu Ahmad al-Shaydhmi or the Dua & Zikr app's reciter | A request for the reciter's file that holds that dua |
| **android.quran.com** | When you open the list of Quran translations and tafsirs, or download one | Requests for that list and those editions |
| **files.quran.app** | When you download the printed Mushaf pages | Requests for those page images |
| **GitHub** | When you choose or preview an adhan from the online library | A request for that adhan's file |
| **Diyanet** (dinhizmetleri.diyanet.gov.tr, with e-Devlet's copy at www.turkiye.gov.tr as the fallback), **DITIB** (www.ditib.de), **JAIS** (e-khutbah.jais.gov.my), **JAKIM** (www.islam.gov.my), **Kuwait's Ministry of Awqaf** (www.awqaf.gov.kw, content.awqaf.gov.kw) and **Morocco's Ministry of Habous** (www.habous.gov.ma) and **Islamic Network** (sermons.islamic.network, cdn.islamic.network: the UAE's) | Only for This week's khutbah: when you open it, and when Today shows its card on a Thursday or Friday, for the country it follows (the one you chose, or the city on show's, worked out on your phone); and when you open or download a khutbah's PDF, Word file or recording | A request for that authority's list of khutbahs and for the files you open or download; nothing about you or where you are. For JAKIM and Kuwait, opening a khutbah's text first reads that sermon's own page to find its PDF. Egypt's and Singapore's pages open in Salah Bar's own web view, like any web page you visit |
| **YouTube** (www.youtube.com) | With Türkiye's (Diyanet's) khutbah list, at the same times (and on Friday until the week's video is in) | A request for the public feed of Salah Bar's own YouTube channel, to find the week's khutbah video; no account, no key, no cookies, nothing about you |
| **YouTube's player** (www.youtube-nocookie.com) | Only when you tap *Watch* on a week's khutbah | The video plays in YouTube's privacy-enhanced player inside the app; Salah Bar sends nothing about you, clears the player's cookies and storage when you close it, and [Google's privacy policy](https://policies.google.com/privacy) applies to the player |
| **Wikimedia Commons** (upload.wikimedia.org) | Only when you play a name in the 99 Names (or a name-of-the-day card) or download the names for offline use | Requests for the recordings you play or download |
| **Your mosque's website** (the link you give) or **islamic.app** (api.islamic.app) | Only with *Iqama times from your mosque* on (Settings → Prayer Times → Iqama): when you save the link, when you tap *Refresh now*, and once a week | A request for the iqama timetable at that link (or that islamic.app mosque); nothing is sent with it |
| **OpenStreetMap** (Nominatim search) | Only when you open Nearby mosques, on the Qibla screen | The point to search around (your location or the city on show, rounded to about 100 m) ([OpenStreetMap's privacy policy](https://osmfoundation.org/wiki/Privacy_Policy) applies) |
| **Overpass API** (overpass-api.de, a free OpenStreetMap search run by FOSSGIS e.V.) | Only when you open Nearby mosques, on the Qibla screen, at the same time as the Nominatim search | The same rounded point, to find every mosque mapped around it ([FOSSGIS terms of use](https://www.fossgis.de/arbeitsgruppen/osm-server/nutzungsbedingungen/)) |
| **Open-Meteo** (api.open-meteo.com) | Only with *Show the weather* on (Settings → Appearance): when you turn it on, then at most every 30 minutes while the app is open | Your location rounded to 0.1° (about 10 km), to get the current weather there; nothing else is sent with it |
| **OpenFreeMap** (map tiles, from OpenStreetMap data) | When a map is on screen: Nearby mosques, and the Qibla screen's Map | Requests for the map tiles of the area shown ([OpenFreeMap](https://openfreemap.org)) |

**The weather** (off until you turn it on, on each phone). The sky behind the next prayer and in
the widgets is worked out on the phone from the prayer times. If you turn on *Show the weather*
(Settings → Appearance), Salah Bar first says what it will send, then asks Open-Meteo
(open-meteo.com) for the current weather at the city on show rounded to 0.1° (about 10 km), at
most every 30 minutes while the app is open (never in the background), with no account, key,
cookie or identifier. The answer (clouds, rain, snow…) stays on the phone, is drawn by its widgets,
and is left out of Android's backup. Turning the switch off stops the requests and forgets the last
answer. Open-Meteo's terms and privacy policy apply to the request; its weather data is CC BY 4.0.

**Automation webhook** (Settings → Advanced → Automation) is off by default: when you turn it on,
Salah Bar sends the prayer's name, its time and iqama, the city and the Hijri date to the one address you
choose, at prayer times and around the adhan. That address must be on your own network unless you
tick "Allow internet addresses".

Links you tap (such as Tanzil.net for the Quran text's source) open in your browser.
Directions to a mosque open in the maps app you choose on your phone; that app's own privacy
policy applies.

## Children

Salah Bar collects no data from anyone, including children.

## Changes

If this policy changes, the new version will be published on this page with a new date.

## Contact

Questions about privacy: open an issue at https://github.com/be-liever95/salah-bar/issues.
