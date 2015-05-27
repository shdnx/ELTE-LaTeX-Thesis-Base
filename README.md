LaTeX alap ELTE-s szakdolgozatokhoz
===============================

Ez a project egy LaTeX keretrendszert biztosít az ELTE informatikai kara hallgatói szakdolgozatához. Természetesen ennek ellenére felhasználható más egyetemek hallgatói, sőt: bárki által is.

Előre be vannak állítva az ELTE IK BSc-s szakdolgozat formai követelményei - mint például az A4-es papír, 12-es betűméret, másfélszeres sorköz, stb. - valamint a belső fedőlappal se neked kell szórakoznod.

Használat
-----------------------

Letöltés után két fájlt kell csak elvileg módosítanod:

* a _tex/adatok.tex_ fájlban add meg a szakdolgozat címét és egyéb adataidat (ezekből generálódik a fedőlap)
* a _tex/tartalom.tex_-be kerül a szakdolgozatod tartalma

A szakdolgozatodat PDF formátumban az alábbi parancs futtatásával tudod létrehozni:

	pdflatex szakdolgozat.tex

... feltéve, ha a LaTeX-es környezeted és a megfelelő csomagok fel vannak telepítve.

License, felelősség
--------------------------------

A project MIT license alatt van: azt csinálsz vele, amit akarsz, azzal a megkötéssel, hogy megemlíted az eredeti forrást és nem próbálsz engem bármilyen módon akármilyen felelősségre vonni.

Ez a keretrendszer megfelelt az ELTE IK formai követelményeknek a BSc-s szakdolgozatokhoz 2015 nyarán. Ennek ellenére én semmilyen felelősséget vagy garanciát nem vállalok; a felhasználó feladata és felelőssége, hogy ellenőrizze, hogy a készült szakdolgozata valóban megfelel minden formai és tartalmi követelménynek.
