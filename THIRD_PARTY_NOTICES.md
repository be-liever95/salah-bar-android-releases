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

## Translations
English quotes use **Sahih International**; Turkish quotes use the **Diyanet İşleri
Başkanlığı** translation. These belong to their publishers.

## Adhan recordings
The bundled default adhan and the recordings in the online library belong to their
reciters and producers and are not covered by Salah Bar's license.

## Libraries
- **AndroidX** (Core, Activity, Lifecycle, Compose, Material 3) and **Media3 ExoPlayer**:
  Copyright The Android Open Source Project, Apache License 2.0
  (https://www.apache.org/licenses/LICENSE-2.0).
- **Kotlin** standard library and **kotlinx.serialization**: Copyright JetBrains s.r.o. and
  Kotlin contributors, Apache License 2.0.
- **ICU4J** (tests only, not in the app): Copyright Unicode, Inc., Unicode License v3
  (https://www.unicode.org/license.txt).

## Official prayer-time data
The fixtures under `shared/fixtures` come from Diyanet İşleri Başkanlığı
(namazvakitleri.diyanet.gov.tr) and Aladhan (aladhan.com), and are used only to test accuracy.
