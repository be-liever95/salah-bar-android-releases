# Salah Bar for Android: Privacy Policy

*Last updated: 15 October 2026*

**In short: Salah Bar collects nothing.** There are no accounts, no analytics, no ads and no
tracking. Your settings, your location and your prayer log stay on your phone, unless you choose
to sync them through a file in your own cloud drive. The developer never receives any of your data.

## What stays on your phone

- **Your location.** With your permission, Android tells Salah Bar your approximate location, to
  calculate prayer times and the Qibla direction. The calculation happens on your phone. The
  place name (such as "Manisa, TR") and its time zone come from a list of cities built into the
  app, so your location is never sent anywhere to be named. Salah Bar keeps your last location
  on your phone so the times are right the next time it opens. Your location is never synced
  to a cloud drive.
- **Your watch.** If you install Salah Bar on a Wear OS watch, your phone hands it your
  settings and the city on show (with its location), so the watch can calculate the times for
  its tile and complications. They go over Wear OS's own phone-to-watch connection (Google Play
  services), which may carry them through Google's servers when the watch is connected by Wi-Fi
  rather than Bluetooth. Nothing reaches the developer.
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
- **The Tasbih counter** is kept on your phone; it isn't synced.
- **Reminders** are scheduled on your phone with Android's alarms and shown as notifications on
  your phone.

## Sync (only if you turn it on)

In Settings → Sync and backup you can choose a file in a cloud drive you already use (Google
Drive, OneDrive, Nextcloud or any app that appears in Android's file picker). Salah Bar then
writes your settings, saved cities, prayer log, Ramadan log, Khatma progress and Quran places to that file, with
your phone's name (as set in Android's settings) so your other devices can show where the data
came from, and reads what your other devices wrote there. The file goes only where you put it:
Salah Bar has no server, and the developer never sees it. Your cloud drive's own privacy policy
applies to the file. "Stop syncing" takes this phone's data out of the file. **Export** writes the
same data to a file you choose, and **Import** reads one back.

## Android's backup

If backup is turned on in your phone's settings, Android may include Salah Bar's settings, logs
and downloaded adhans in your phone's backup to your Google account, as it does for most apps, so
they come back on a new phone. Salah Bar leaves its Quran downloads and its sync link out of that
backup. You can turn backup off in Android's settings.

## What goes over the internet

Salah Bar only connects to the services below, and only for the feature named. None of them
receives your name, your location, your settings or an account, but like any web request each
sees your phone's IP address.

| Service | When | What it receives |
|---|---|---|
| **mp3quran.net** | When you use the Quran tab: the list of reciters (at most once a week), the surahs you play or download, and ayah timings for Hifz | Requests for those files |
| **EveryAyah.com** | Hifz with recitations it serves ayah by ayah | Requests for those ayahs' files |
| **hisnmuslim.com** | When you listen to a dua | A request for that dua's recording |
| **android.quran.com** | When you open the list of Quran translations and tafsirs, or download one | Requests for that list and those editions |
| **files.quran.app** | When you download the printed Mushaf pages | Requests for those page images |
| **GitHub** | When you choose or preview an adhan from the online library | A request for that adhan's file |

Links you tap (such as Tanzil.net for the Quran text's source) open in your browser.
**Nearby mosques** hands your location to the maps app you choose on your phone, which searches
for mosques around it; that app's own privacy policy applies. Salah Bar itself sends it nowhere.

## Children

Salah Bar collects no data from anyone, including children.

## Changes

If this policy changes, the new version will be published on this page with a new date.

## Contact

Questions about privacy: open an issue at https://github.com/be-liever95/salah-bar/issues.
