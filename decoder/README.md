# Decoder

Jednoduchá Android aplikace, která zobrazuje přehled zadaných kódů. Načte záznamy z databáze, sjednotí duplicitní kódy a ukáže u každého, jestli byl zadán **správně ✓** nebo **špatně ✗**. Umí:

- vyhledávání v kódech,
- filtr správně / špatně / vše,
- řazení A→Z / Z→A,
- obnovení dat tlačítkem nebo gestem přetažení dolů (pull-to-refresh).

## Stažení

APK je přímo v této složce: **[decoder.apk](https://mikipoldi.github.io/decoder/decoder.apk)**

Požadavky: Android 7.0 (Nougat) nebo novější a připojení k internetu.

## ⚠️ Instalace na Android

Aplikace **není z Google Play** — instaluje se ručně z APK souboru (tzv. sideload). Android proto při instalaci zobrazí varování a **je potřeba povolit instalaci z neznámých zdrojů**. To je u aplikací mimo Google Play normální.

Postup:

1. **Stáhněte APK** — otevřete v telefonu odkaz výše (nebo si soubor pošlete do telefonu jinak, např. přes USB či cloud).
2. **Otevřete stažený soubor** — klepněte na `decoder.apk` v notifikaci o stažení, nebo ho najděte v aplikaci *Soubory* ve složce *Stažené*.
3. **Povolte instalaci z neznámých zdrojů** — Android zobrazí hlášku typu *„Z bezpečnostních důvodů nemůže telefon instalovat neznámé aplikace z tohoto zdroje"*:
   - klepněte na **Nastavení**,
   - zapněte **Povolit z tohoto zdroje** (povolení se dává aplikaci, ze které APK otevíráte — typicky prohlížeč Chrome nebo správce souborů),
   - vraťte se zpět tlačítkem Zpět.
4. **Nainstalujte** — klepněte na **Instalovat** a počkejte na dokončení.
5. Pokud se ozve **Play Protect** s varováním, že aplikaci nezná, zvolte **Přesto nainstalovat** (může být schované pod *Další podrobnosti*).
6. Hotovo — aplikaci **Decoder** najdete v seznamu aplikací.

> Tip: Povolení z kroku 3 můžete po instalaci zase vypnout v **Nastavení → Aplikace → (Chrome / Soubory) → Instalace neznámých aplikací**.

## Proč Android varuje?

Google Play kontroluje aplikace před zveřejněním, u ručně instalovaných APK to udělat nemůže, proto se ptá. Tento APK je podepsaný vývojářský build — instalujte ho jen pokud jste ho stáhli z tohoto webu.
