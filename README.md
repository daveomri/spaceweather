# spaceweather

NI-BML project

### Description
Na webu NOAA - např. na https://www.swpc.noaa.gov/products/goes-electron-flux - jsou k dispozici online reporty parametrů slunečního větru. Zájemci vypracují projekt, který:
- online stahuje tyto reporty a parsuje data,
- z dat v nich obsažených modeluje "rozumně" vybraným modelem AR(p) vývoj **vybrané** vhodné proměnné (např. elektrony s energií větší než 2MeV),
- vykresluje aktuální průběh modelované proměnné,
- vykresluje bodové odhady regresních koeficientů beta,
- doplňuje jednokrokovou (zájemci i více) predikci.

Při spuštění by program měl načíst aspoň 20 nejnovějších dat - je potřeba vhodně se poprat s přelomem dne (aby modelování nerestartovalo s každým novým dnem). Nezapomeňte na zapomínání (viz výše). Využít můžete třídu NiG, použitou i ve cvičeních. V podstatě jde o to využít programátorské schopnosti a nově nabyté znalosti - nic těžkého na projektu není :-)