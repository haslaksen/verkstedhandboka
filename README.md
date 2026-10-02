# Verkstedhåndboka

Nettbasert verkstedhåndbok for verksted og undervisning (VG2 Industriteknologi).

**Kapitler:** toleranser (ISO 286), passninger, generelle toleranser (ISO 2768), form- og beliggenhetstoleranser (ISO 1101), metriske gjenger, tommegjenger (UNC, UNF og UN 8) og rørgjenger, overflateruhet, skjæredata, materialer og vekt, sveisesymboler (ISO 2553), pneumatikk, hydraulikk, elektro med motorstyring, måling med multimeter, fysikk og matematikk.

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
