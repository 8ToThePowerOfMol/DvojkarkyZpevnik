#Dvojka�sk� zp�vn�k

Bude to megazp�vn�k!!!
Pros�m, pro z�le�itosti, kter� je pot�eba vy�e�it �t�te issues. (Hod� se p�e��st si i ty Closed.)

Filesystem prozat�m vy�e�en tak, �e m�me soubory:
- main.tex
    - sem se vkl�daj� adresy jednotliv�ch song� (je pot�eba m�t to se�azen�)
- test.tex
    - zde se testuj� jednotliv� songy (asi po jednom)
    - existuje proto, �e to nejde testovat p��mo v t�ch jednotliv�ch souborech dan� song
- songy
    - slo�ka obsahuj�c� jednotliv� songy
    - je zvykem pojmenov�vat ty soubory bez mezer a za��tek ka�d�ho slova m�t velk�m p�smenem

Kdy� chcete p�idat nov� song, tak mus�te:
1) Zalo�it nov� latex soubor ve slo�ce songy.
2) Vyplnit obsah souboru
2*) Je mo�no ho testovat pomoc� test.tex
3) P�idat (podle abecedn�ho po��dku) odkaz na soubor v main.tex pomoc� tagu \subfile{}