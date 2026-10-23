GeoSkicirka MAP Android 0.1 — IZVORNI ANDROID STUDIO PROJEKAT

Ovo NIJE gotov APK. Za kompajliranje je potreban Android Studio, Android SDK i internet za prvi Gradle sync.

KAKO NAPRAVITI APK:
1. Instalirati Android Studio na Windows/macOS/Linux računaru.
2. Raspakovati ZIP i u Android Studio izabrati Open, zatim fasciklu GeoSkicirka_MAP_Android_0_1.
3. Sačekati da se Gradle projekat sinhronizuje.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Instalirati izgrađen app-debug.apk na Android telefon i odobriti instalaciju za taj izvor, ako Android traži.
6. Prilikom GPS ON odobriti dozvolu za lokaciju. Za bolje praćenje izabrati preciznu lokaciju.

FUNKCIJE:
- Skicirka MAP 0.2 kao sadržaj aplikacije u sigurnom lokalnom HTTPS poreklu (WebViewAssetLoader).
- GPS dostupnost preko Android dozvola, bez javnog servera.
- Karte preko OpenStreetMap internetskog servisa. Bez interneta nema podloge, crtanje i GNSS pozicija telefona mogu raditi.
- Izvoz JSON preko Android čuvanja i Podeli; uvoz JSON preko Android birača fajla.
- Postojeći JSON format za AutoLISP nije promenjen.
- Originalna GeoSkicirka 0.7 ostaje netaknuta.

OGRANIČENJA / TESTIRANJE:
- Još nije kompajlirano niti testirano na Android uređaju: ovde nema instaliranog Android SDK/Gradle.
- PNG export iz web dela nije integrisan sa Android Storage Access Framework i može biti ograničen u WebView-u.
- GPS zavisi od Android dozvola, uključenih Location Services i uređaja.
- Mape zahtevaju internet; nisu spremljene offline pločice.
- GPS koordinate su SAMO orijentacione, nisu geodetski tačne.
- Projekat ne traži dozvolu za lokaciju u pozadini.
