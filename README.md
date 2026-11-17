# Ministri Public Website

This package updates the existing GitHub Pages website for `ministri.app`.

## Structure

- `/index.html` — public Ministri marketing site, now positioned for Ministri Cloud/web/mobile subscription use.
- `/fellowship-licence/index.html` — dedicated Fellowship Licence page for authorised Potter's House Fellowship churches.
- `/pricing/index.html` — review-ready public Ministri Cloud plans page. It is not published until this branch is approved and merged.
- `/styles.css` — existing Ministri styling plus Cloud and Fellowship Licence page styles.
- `/script.js` — dynamic copyright year.
- `/assets/` — existing Ministri imagery.
- `/CNAME` — retains the custom domain `ministri.app`.

## Important commercial separation

The Fellowship Licence page intentionally contains **no price**. Current fees, launch offers and changing commercial terms should remain in the current Fellowship Licence information/document supplied directly to eligible churches.

The public homepage describes Ministri Cloud as being prepared for public subscription release rather than presenting it as already live.

The pricing page includes the approved Free and Starter plan information only. Growth, Established and Custom are labelled as awaiting pricing approval. The Free and Starter calls to action are prepared to enter the Cloud signup flow with a plan hint; public signup must remain closed until the separate Cloud release is approved.

## GitHub Pages upload

Replace the matching website files in the current GitHub Pages repository with the files in this package, including the new `fellowship-licence` folder. Keep `CNAME` at the repository root.

The Fellowship page will then be available at:

`https://ministri.app/fellowship-licence/`


## Fellowship Licence page

The Fellowship Licence page lives at `/fellowship-licence/`. It is intentionally not linked from the public homepage navigation or footer. Share the direct URL privately with authorised Potter's House Fellowship churches. The page includes `noindex, nofollow` to discourage search-engine indexing.

Pricing is intentionally not hard-coded on the website; current fees/offers should remain in the current Fellowship Licence document.
