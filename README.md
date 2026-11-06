# RAK PHUKET — Keep Phuket Beautiful

A static, ten-language waste-sorting guide for Phuket. Open `index.html` in a browser; no build step, installation or API keys are required. The existing GitHub Pages URL and QR asset are preserved.

## November 2026 content update

The update follows the supplied team messages and teacher recommendations:

- Removed the 5% electricity-bill discount, the ฿3 7-Eleven stamp promise, and the old reward-claim link.
- Replaced them with a proposed loyalty programme for residents and visitors: Green Points and future offers from participating Phuket hotels and restaurants. No active discounts, confirmed reward partners, point rate or redemption date are invented.
- Added the volunteer-team statement: members currently receive no personal payment or profit from the campaign. Future corporate sponsorship may support materials and activities. The site does not claim registered-charity status.
- Added the planned #RakPhuket content pillars, future feature ideas and a measurement plan.
- Restored a working Google Maps search for recycling collection locations in Phuket. Results are search suggestions, not a verified directory.
- Added section navigation and translated the new content into all ten supported languages.
- Fixed typing in the sorting search before selecting a bin. Search now works across all categories; clicking a bin clears the query and selects that category.

## What works now

The four-bin guide, multilingual search, language selection and saved preference, Green Stars proposal, section navigation, map search link and printable QR are available in the website files.

## Planned features and launch dependencies

Green Points, evidence submissions, reward verification/redemption, LINE integration and AI photo classification are described as future plans. They are not implemented services. The original repository has no backend, accounts, secure reward ledger, analytics service or AI integration.

Before launching rewards, confirm participating businesses, terms, funding, point rules and verification responsibility, then build the necessary service. The old Google Form was unlinked from the website; the Form itself was not modified. Revise it before reusing it.

The campaign's reach, impressions, QR visits, verified waste quantities and participating-business counts are planned measures. No live analytics or invented totals have been added. Workload allocation and creating a new physical poster remain team tasks, separate from this website update.

## Files to update

Replace `index.html`, `app.js` and `style.css`; add `campaign.js`. Keep `languages.js`, `green-stars.js`, `logo.jpg`, `qr.svg` and `.nojekyll`. Include this README for the team.

New campaign copy lives in `campaign.js`. Update every locale together. Existing sorting-guide translations remain in `app.js` and `languages.js`. Green Stars content remains in `green-stars.js`.

## Publish on the existing GitHub Pages site

Upload the files inside this folder to the root of `ThuTaZaw6823/Project-Test` (do not upload the enclosing folder or the ZIP itself). Commit to the branch used by GitHub Pages, currently the repository's `main` branch in the source checkout. Keep the existing Pages settings. GitHub Pages deployment settings were not inspected or changed in this update.

For a Git checkout, review and merge the update branch, then push using your authenticated GitHub account. A local commit or downloaded ZIP alone does not update the live website.

## Validation

- JavaScript syntax checked for all four scripts.
- Browser-checked all ten languages: all new sections and three loyalty steps render; no missing translation values or legacy reward promises appear.
- Verified initial search, no-results feedback and all four bin result counts (3 / 2 / 3 / 2).
- Reviewed the English rewards layout and checked desktop overflow in all ten languages.
- Preserved existing mobile layout rules and added single-column layouts for the new cards. A mobile-device browser check was not performed.
