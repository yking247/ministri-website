# Ministri Public Website

This package updates the existing GitHub Pages website for `ministri.app`.

## Structure

- `/index.html` — public Ministri marketing site for Ministri Cloud web access; the mobile app is described as a future release.
- `/fellowship-licence/index.html` — dedicated Fellowship Licence page for authorised Potter's House Fellowship churches.
- `/pricing/index.html` — review-ready public Ministri Cloud plans page. It is not published until this branch is approved and merged.
- `/subscription-information/index.html` — agreed Cloud seller, non-VAT, subscription, cancellation, refund and privacy-summary wording; unpublished pending launch approval.
- `/styles.css` — existing Ministri styling plus Cloud and Fellowship Licence page styles.
- `/script.js` — dynamic copyright year.
- `/assets/` — existing Ministri imagery.
- `/CNAME` — retains the custom domain `ministri.app`.

## Important commercial separation

The Fellowship Licence page intentionally contains **no price**. Current fees, launch offers and changing commercial terms should remain in the current Fellowship Licence information/document supplied directly to eligible churches.

The public homepage describes Ministri Cloud as being prepared for public subscription release rather than presenting it as already live.

The pricing page includes the approved Free and Starter plan information only. Growth, Established and Custom are labelled as awaiting pricing approval. The Free and Starter calls to action are prepared to enter the Cloud signup flow with a plan hint; public signup must remain closed until the separate Cloud release is approved.

The subscription information identifies Yolanda King, trading as iDesign Labs, using the supplied correspondence address and support email. It states that iDesign Labs is not VAT registered and no VAT is charged. This is customer-facing copy only: no Stripe tax, account-wide branding or billing settings are changed by this branch.

The existing Cloud Data Processing Agreement remains a draft, without an effective date or acceptance. Adding the subscription summary does not approve or activate that agreement. Privacy and data-processing documents still need their separate pre-launch approval.

The account-closure section remains a proposed policy, not yet in effect. The separate Cloud account-closure review implements Owner/MFA verification, a 90-calendar-day recovery request, paused normal access with Owner recovery/export/billing access, withdrawal, queued notifications and manual-deletion review safeguards. Exports and permanent deletion are operator-assisted, not automatic. The migration, rollout, notification delivery and operator/backup/exception arrangements require separate approval before publication. Paid-subscription cancellation continues to preserve church data and never requests closure. The proposed recovery period does not override existing Sunday School retention policies or individual data-protection rights.

## GitHub Pages upload

Replace the matching website files in the current GitHub Pages repository with the files in this package, including the new `fellowship-licence` folder. Keep `CNAME` at the repository root.

The Fellowship page will then be available at:

`https://ministri.app/fellowship-licence/`


## Fellowship Licence page

The Fellowship Licence page lives at `/fellowship-licence/`. It is intentionally not linked from the public homepage navigation or footer. Share the direct URL privately with authorised Potter's House Fellowship churches. The page includes `noindex, nofollow` to discourage search-engine indexing.

Pricing is intentionally not hard-coded on the website; current fees/offers should remain in the current Fellowship Licence document.
