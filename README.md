# Kitchen Rota

A weekly cook rota for the restaurant kitchen, Sunday to Saturday.
One self-contained HTML file — no build step, no server, no dependencies.

* Tap a cook to put them on a shift, tap again to take them off.
* Sunday–Thursday share one set of shift times; Friday keeps its own per clock.
* Saturday opens after Shabbat goes out in Haifa — the time is computed from
  sunset for that date, so it moves every week.
* Share the week as a picture (WhatsApp / Messenger) or as a link that carries
  the whole week in its address.
* The rota is stored in the browser on the device that edits it.

Instructions inside the app are in Thai with English underneath.

## Hosting

`index.html` at the repository root is all GitHub Pages needs.
Settings → Pages → Deploy from a branch → `main` / `/ (root)`.

`docs/index.html` is a copy of the root `index.html`, so GitHub Pages can serve
from either `/ (root)` or `/docs`. Keep the two in sync when the app changes.
