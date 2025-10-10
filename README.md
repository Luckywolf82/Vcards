# Vcards – flerorganisasjonsoppsett

Klar for GitHub Pages. Strukturen bruker én mappe per organisasjon og én undermappe per person.

## Struktur
Vcards/
├─ index.html
├─ .nojekyll
├─ Wayback/
│  ├─ index.html
│  └─ trygve/
│     ├─ index.html
│     └─ trygve_wayback.vcf
├─ MollerBil/
│  ├─ index.html
│  └─ eksempel/
│     ├─ index.html
│     └─ eksempel_mollerbil.vcf
└─ JarwsonsKjokken/
   ├─ index.html
   └─ eksempel/
      ├─ index.html
      └─ eksempel_jarwsons.vcf

## Legg til ny person
1. Kopier en personmappe (f.eks. `Wayback/trygve`) og gi den nytt navn (kun ASCII i mappenavn).
2. Rediger `index.html` (visning) og `.vcf` (kontaktinfo).
3. Commit – GitHub Pages oppdateres automatisk.

## NFC-URL (eksempler)
- Trygve (Wayback): https://luckywolf82.github.io/Vcards/Wayback/trygve/trygve_wayback.vcf
- Eksempel (Møller Bil): https://luckywolf82.github.io/Vcards/MollerBil/eksempel/eksempel_mollerbil.vcf
- Eksempel (Jarwsons): https://luckywolf82.github.io/Vcards/JarwsonsKjokken/eksempel/eksempel_jarwsons.vcf
