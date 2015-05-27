LaTeX alap ELTE-s szakdolgozatokhoz
===============================

Ez biztosít egy keretet ahhoz, hogy az ELTE-s szakdolgozatodat LaTeX-ben megírd.

Előre be vannak állítva a BSc-s szakdolgozat formai követelményei (A4-es papír, 12-es betűméret, másfélszeres sorköz, stb.), valamint a belső fedőlappal se neked kell szórakoznod.

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

MIT license: azt csinálsz vele, amit akarsz, amíg megemlíted az eredeti forrást és nem próbálsz engem felelősségre vonni.

Ez a keretrendszer megfelelt a formai követelményeknek az ELTE-s BSc szakdolgozatokhoz 2015 nyarán. Ennek ellenére semmilyen felelősséget vagy garanciát nem vállalok; a felhasználó feladata és felelőssége, hogy ellenőrizze, hogy a készült szakdolgozata valóban megfelel minden formai és tartalmi követelménynek.
