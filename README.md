# Verkstedhåndboka

Nettbasert verkstedhåndbok for verksted og undervisning (VG2 Industriteknologi).

**Emner (som i verkstedhåndboka):** 1 SI-enheter, 2 Toleranser, 3 Maskinering, 4 Sammenføyning, 5 Maskinelement, 6 Gjenger, 7 Materialer, 8 Hydraulikk og pneumatikk, 9 Elektro, 10 Matematikk, 11 Fysikk, 12 Mekanikk. Hvert emne har innholdsliste med delemner; delemner merket «kommer» fylles inn fortløpende.

Hele appen er én statisk side, `index.html`, uten byggesteg eller avhengigheter.

## App på telefonen (PWA)
Appen kan installeres på hjemskjermen og virker uten nett etter første besøk.
- **iPhone (Safari):** Del-knappen → *Legg til på Hjem-skjerm*.
- **Android (Chrome):** knappen *Installer app* øverst, eller ⋮ → *Installer app*.

Filer: `manifest.webmanifest` (navn, ikon, farger), `sw.js` (offline-lager), `icons/`.
Når en ny versjon pushes, viser appen «Ny versjon er klar → Oppdater».

## Kjøre lokalt
Åpne `index.html` i nettleseren. Offline-funksjonen krever http(s), f.eks. `python -m http.server`.

## Deploy
Vercel: importer repoet, velg Framework Preset **Other**, la Build Command og Output Directory stå tomme.
