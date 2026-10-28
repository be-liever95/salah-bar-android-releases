# Third-party notices

Salah Bar for Android is "all rights reserved" (see [LICENSE](LICENSE)), except for the
components below, which keep their own licenses and owners.

## Prayer-time calculation
Salah Bar computes the sun's position with its own code, written from the U.S. Naval
Observatory's public-domain "Approximate Solar Coordinates"
(https://aa.usno.navy.mil/faq/sun_approx).

## The Quran text
The Arabic of the Quranic quotes, and the full Quran text bundled for the Hifz
(memorisation) mode (`shared/quran-text.json`, copied from Salah Bar for Mac), is from the
**Tanzil Quran Text** (quran-simple, version 1.1), Copyright (c) 2007–2026 Tanzil Project,
https://tanzil.net, licensed under Creative Commons Attribution 3.0 and used verbatim under
its terms of use: the text is not changed, its source is credited, and Tanzil's copyright
notice is kept in the bundled file.

## The Amiri font
[Amiri](https://github.com/aliftype/amiri) 1.000 by Khaled Hosny, bundled unmodified
(`Amiri-Bold.ttf`, `Amiri-Regular.ttf`) under the
[SIL Open Font License 1.1](https://openfontlicense.org); its licence text is
`shared/fonts/Amiri-OFL.txt`.

## GeoNames (city list)
`data/cities.tsv.gz` is derived from GeoNames (https://www.geonames.org), cities with
15,000+ people, licensed under **Creative Commons Attribution 4.0**
(https://creativecommons.org/licenses/by/4.0/). Built by `tools/gen-cities.py`.

## Natural Earth (world outline)
`data/world-land.json` is derived from Natural Earth 1:110m land
(https://www.naturalearthdata.com), public domain, built by `tools/gen-world.py`,
no endorsement implied.

## Translations
English quotes use **Sahih International**; Turkish quotes use the **Diyanet İşleri
Başkanlığı** translation. These belong to their publishers.

## Adhan recordings
The bundled default adhan and the recordings in the online library belong to their
reciters and producers and are not covered by Salah Bar's license.

These openly licensed recordings in the library are used under their licenses (each is also
credited where it's chosen in the app):
- “Call to prayer from the Prophet's Mosque” by ejaz215, CC BY 3.0, via Wikimedia Commons: https://commons.wikimedia.org/wiki/File:33937_ejaz215_call-to-prayer-from-the-prophet-s-mo.ogg
- “AZAAN in Makkah” by Seyfula Islam, CC BY 3.0, via Wikimedia Commons: https://commons.wikimedia.org/wiki/File:Adhan,_Great_Mosque_of_Mecca_-_Jan_21,_2013.webm
- “Eid al-Fitr Fajr azan at Malmö Mosque” by Islamic Center Malmö, CC BY 3.0, via Wikimedia Commons: https://commons.wikimedia.org/wiki/File:Eid_al-Fitr_Fajr_azan_at_Malmö_Mosque_-_19_August_2012.webm
- “Adhan in Shalqar mosque” by Esetok, CC BY-SA 4.0, via Wikimedia Commons: https://commons.wikimedia.org/wiki/File:Adhan_in_Shalqar_mosque.webm
- “Islamic Call to Prayer (Dhuhr Adhan)” by RJStefanski, CC BY 3.0, via Freesound: https://freesound.org/people/RJStefanski/sounds/255231/
- “adzan-forest” by bagustris, CC0, via Freesound: https://freesound.org/people/bagustris/sounds/508441/

## Libraries
- **AndroidX** (Core, Activity, Lifecycle, Compose, Material 3 and its icons; on the watch Wear
  Compose, Tiles, Complications and Watch Face Push) and **Media3 ExoPlayer**:
  Copyright The Android Open Source Project, Apache License 2.0
  (https://www.apache.org/licenses/LICENSE-2.0).
- **Guava** (on the watch, with Watch Face Push): Copyright The Guava Authors, Apache License 2.0.
- **MapLibre Native** (the Qibla and Nearby mosques maps): Copyright MapLibre contributors, BSD 2-Clause
  License (https://github.com/maplibre/maplibre-native). Map tiles from OpenFreeMap (https://openfreemap.org),
  data © OpenStreetMap contributors (ODbL).
- **Map data and tiles** in Nearby mosques: © OpenStreetMap contributors, Open Database License
  (https://www.openstreetmap.org/copyright).
- **Kotlin** standard library and **kotlinx.serialization**: Copyright JetBrains s.r.o. and
  Kotlin contributors, Apache License 2.0.
- **ICU4J** (tests only, not in the app): Copyright Unicode, Inc., Unicode License v3
  (https://www.unicode.org/license.txt).

## Official prayer-time data
The fixtures under `shared/fixtures` come from Diyanet İşleri Başkanlığı
(namazvakitleri.diyanet.gov.tr) and Aladhan (aladhan.com), and are used only to test accuracy.
