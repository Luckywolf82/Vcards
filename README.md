# vCard Host – Trygve Eiulf Waagen (Wayback Trondheim)

Filer for å hoste vCard (.vcf) via GitHub Pages.

## Innhold
- `.nojekyll` – Slår av Jekyll-behandling på GitHub Pages.
- `index.html` – Landingsside med nedlastingsknapp.
- `trygve_wayback.vcf` – vCard 3.0 (UTF-8).

## Publisering (GitHub Pages)
1. Opprett et public repo (f.eks. `vcard-wayback`) og last opp filene i rot.
2. **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*.
3. Velg **Branch: main** og **/ (root)** → **Save**.
4. Siden blir tilgjengelig på `https://<brukernavn>.github.io/<repo>/`.

### Direkte vCard-URL
`https://<brukernavn>.github.io/<repo>/trygve_wayback.vcf`

## NFC (NTAG213/215/216)
Skriv NDEF-URL til direkte vCard-lenka over for sømløs import på iPhone/Android.
