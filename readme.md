# Fate Condensed Magyarul

Ez a Fate Condensed fordításának a forráskódja. Felhasználhatod a saját játékod elkészítéséhez, emiatt elég sok időt töltöttem azzal, hogy könnyű legyen kiegészíteni.

## Szükséges karakterkészletek

Az alábbi helyekről kell letöltened az ingyenes karakterkészleteket és a gépedre installálnod, különben nem fogsz tudni pdf fájlokat fordítani.

[Fate Font](https://www.faterpg.com/licensing/)

[Wingdings3](https://www.wfonts.com/font/wingdings-3)

[EB Garamond](https://fonts.google.com/specimen/EB+Garamond)

[Roboto](https://fonts.google.com/specimen/Roboto)

[Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed)

## Lefordítás

Nyisd meg a "Fate Condensed HU.tex" fájlt a [TeXworks](http://www.tug.org/texworks/) ingyenes alkalmazásban. Ezután állítsd át a Typeset menüben, hogy a XeLaTeX motort használja. Erre azért van szükség, mert az - igencsak ódivatú - eredeti pdfLaTeX nagyon rosszul kezeli a karakterkészleteket. Ezután a Ctrl+T gombbal tudod lefordítani, ami automatikusan el is indítja a beépített pdf böngészőt. Ezt legalább kétszer meg kell nyomnod, mert a tartalomjegyzék csak akkor frissül, ha már egyszer sikeresen lefordította a forrásokat, és tudja, hogy melyik fejezet melyik oldalon van.

## Saját játék készítése

A források szét vannak szedve összefüggő lapokra, ahol van értelme szétvagdosni a szöveget. A cél az, hogy ha saját játékot csinálsz, akkor csinálj egy másolatot a "Fate Condensed HU.tex" fájlból. Ezután töröld ki azokat a "\include{condensed/...}" sorokat, amire nincs szükséged. Végül adjál hozzá új "\include{jatekod/...}" bejegyzéseket. Ezzel a módszerrel elég könnyen követni tudod majd a javításokat az eredetiben, amikor is csak fordítanod kell a te játékodból egy újabb verziót, és készen is vagy. Persze beleírhatsz az eredeti fejezetekbe is, de akkor nagyobb meló lesz a változtatásokat követni.

## Hibabejelentés

Ha találsz benne hibát, szívesen veszem, ha jelzed. Vagy akár küldhetsz egy PR-t is.

Mivel a LaTeX-et csak most tanultam meg (ez az könyv volt a kifogás, hogy miért ne halogassam tovább), ezért a legtöbb dolgot csak az internetről másoltam, és valószínűleg rosszul használom. Ezek javítását is szívesen látom.

*Remélem sok örömet fog ez a rendszer okozni neked!*

NoiseEHC
