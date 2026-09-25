TOKO ANDA — Stok (PWA)
========================
index.html            The whole app (open this). Labelled with [TAGS] —
                      search e.g. [RECORD] or [JS-STOCK] to jump there.
                      The file map is at the top of index.html.
support.js            Runtime that renders index.html (don't edit).
manifest.webmanifest  App name + icon for "Add to Home Screen".
sw.js                 Service worker: lets the app open offline.
icons/                App icons.

Quick test on a laptop: double-click index.html (works, but no offline/install).
To install on a phone: upload this whole folder to a free HTTPS host
(Netlify Drop: drag the folder onto app.netlify.com/drop, or GitHub Pages),
open the link on the phone, then "Add to Home Screen".

Data is stored in the browser of each device (IndexedDB).
Back up regularly: Pengaturan > Unduh cadangan (.json).
