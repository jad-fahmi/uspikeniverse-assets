# USpikeNIVerse! — image assets

Images for the USpikeNIVerse! student project (a Google Apps Script web app
about volleyball), served through the jsDelivr CDN:

    https://cdn.jsdelivr.net/gh/jad-fahmi/uspikeniverse-assets@<tag>/img/<path>

The site pins a release tag (for example `v1.0.0`) so cached files never change
under it. To update an image: commit it here, push a new tag, then bump the
`ASSETS` constant in the web app's `Code.gs`.

- `img/photos/` — photographs from Wikimedia Commons under their stated licences.
  Author, licence and source for each file are in `img/photos/credits.json`.
- `img/players/`, `img/teams/` — *Haikyu!!* character art and school emblems
  © Haruichi Furudate / Shueisha, "Haikyu!!" Production Committee, from the
  official haikyu.jp site. Used for non-commercial, educational purposes only.
  All rights remain with their owners.
