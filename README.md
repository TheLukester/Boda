# Brenda & Lucas — GitHub Pages ONLY

This package replaces the previous Cloudflare version. All website files are at the archive root. No Worker, server, password, secret key, Node.js installation, or build step is required.

## Privacy
THIS SITE IS PUBLIC. There is no shared-password gate or protected QR access. Search indexing opt-outs are included but do not prevent scraping. Anyone who has the address can view or copy the pages. A private repository does not automatically make a published Pages site private. Review all names and content before publishing. Do not upload secrets, private editing notes, or personal photos you do not want publicly accessible.

## Publish
1. Unzip the archive locally.
2. Open or create the GitHub repository you want to use. Free GitHub Pages is available for public repositories; other repository types depend on your plan.
3. Upload index.html, menu.html, drinks.html, schedule.html, party.html, couple.html, styles.css, robots.txt and .nojekyll into the root of your publishing branch (normally main). Do not upload just the ZIP, and do not place these inside an extra folder. README.md is optional.
4. In Settings > Pages, select Deploy from a branch, then main and /(root). Save.
5. Wait for GitHub to display the published URL. Open it and test each page on your phone.
6. Enable Enforce HTTPS if available. If replacing an existing site, remove obsolete Worker files/configuration from the publishing branch to avoid confusion.

All navigation links are relative, so both user sites and project/repository sites work. To preview before publishing, open index.html locally.

## QR code
After the final site address is published, create a STATIC website QR code whose destination is your site's menu.html page. For a project site this looks like https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/menu.html . For a user site it is https://YOUR-USERNAME.github.io/menu.html . Use your ACTUAL published address. Do not use the repository's github.com file-view URL. No QR is generated in this archive because the address is not known yet.

No password or access token belongs in this URL. Test the QR from a printed sample and keep the destination address unchanged when updating content. Put the readable address next to the QR as a fallback. The QR links directly to the public food menu, with navigation to drinks and other pages.

## Editing
Edit the HTML files with any text editor or GitHub's editor and commit changes. Colors and layout are in styles.css. To add photos, create an assets/ directory, upload optimized images, and add img elements with descriptive alt text. No external fonts, analytics, or third-party browser resources are loaded.

Food: burgundy arch and cream text, actual supplied dishes. Drinks: ivory/gold design and supplied ingredients. The original cocktail illustrations are not included. Script-font appearance varies by device. Schedule retains approved Spanish activity labels; general navigation is English.

## Content still to confirm — keep these notes off the live site if desired
- Bride surname undecided; displayed simply as Brenda.
- Isabella's Rodriquez spelling is preserved as supplied; confirm.
- Six damas' names pending; not displayed yet.
- Icha is listed as Bride's Aunt. Her uncertain lazo role is not displayed yet.
- Grandma Rose displayed as supplied; full name optional.
- Estrella's role is provisionally Flowers for the Virgin Mary.
- No ingredients invented for Michelada or Mimosas. Piña Colada retains the supplied ingredient list without adding rum. No allergy or alcohol-free guarantees made.
- Couple page contains a generic welcome, not an invented relationship history. Add approved story/photos later.
- The 5–6 p.m. schedule gap remains. Ceremony starts 1:30 p.m.; reception ends 9:55 p.m.
- Date is November 21, 2026, superseding the old date on the printed menu.

This README, if uploaded, is public like all other files. For a public repository, private notes are not private even if unlinked from navigation. Upload ONLY the nine website files listed above to avoid publishing this checklist.

Official guidance:
https://docs.github.com/en/pages/quickstart
https://developers.google.com/search/docs/crawling-indexing/robots/intro
