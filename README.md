# KRYPT placeholder

En færdig statisk side til `kryptkolding.dk`. Ingen installation eller build er nødvendig.

## Filer

- `index.html`: siden og dens metadata.
- `styles.css`: responsivt mørkt design og en kort indtoning. Indtoningen er slået fra ved reduceret bevægelse.
- `assets/krypt-logo.jpg`: det vedhæftede, uændrede logo. CSS skjuler kun overskydende sorte kanter i visningen.
- `.nojekyll`: gør pakken egnet til direkte statisk publicering på GitHub Pages.
- `CNAME`: angiver det ønskede domæne `kryptkolding.dk` til GitHub Pages. Filen foretager ingen DNS-ændringer.

## Lokal visning

Åbn `index.html` i en browser. Siden fungerer også direkte fra disk.

## Publicering senere

Pak ZIP-filen ud, og læg indholdet af denne mappe direkte i den mappe, GitHub Pages skal publicere. Bevar undermappen `assets` og filen `.nojekyll`. Der er ingen afhængigheder eller build-trin.

Pakken er forberedt til eget domæne med `CNAME`. Registrering af domænet, GitHub Pages-opsætning, DNS og HTTPS skal håndteres særskilt, før siden er tilgængelig på `kryptkolding.dk`. Til en midlertidig GitHub Pages-adresse kan `CNAME` udelades, indtil eget domæne skal tilkobles.

Ingen filer er uploadet eller publiceret, og der er ikke foretaget køb eller DNS-ændringer.

## Privatliv og vedligeholdelse

Siden bruger ingen JavaScript, formularer, cookies, tracking, eksterne skrifttyper, biblioteker eller backend. Alle ressourcer ligger i pakken. Hostingudbyderens eventuelle serverlogs er ikke en del af denne kode.

Teksten ændres i `index.html`; farver og afstande ændres i `styles.css`. Designet tager udgangspunkt i det leverede logo: sort/hvidt med en svag mørkerød glød. Der var ingen app-stilfiler i projektets referencemappe til at verificere et præcist match med KryptKore.
