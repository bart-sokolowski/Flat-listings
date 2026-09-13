# Rental listings

A static rental shortlist checked against 16 Rightmove adverts on 13 September 2026.

Open `index.html` in a browser, or use the standalone `Rental-listings.html` supplied alongside this folder. Internet access is needed for the original listing images and web fonts; system fonts provide a fallback.

## GitHub Pages

1. Create a public GitHub repository, such as `flat-shortlist`.
2. Upload the files in this folder to the repository root (not the enclosing folder).
3. Go to **Settings → Pages**. Select **Deploy from a branch**, **main**, and **/(root)**, then save.
4. Open the URL shown by GitHub when deployment finishes.

Alternatively, upload the standalone HTML file and rename it `index.html`.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Favourites and sharing

Hearts save favourites in the current browser. There is no account or shared database. Use **Share favourites** on the hosted page to copy a URL containing the selected listing IDs. Opening that URL loads that selection; each person can edit their own version. A selection in the URL takes precedence when reopening that URL. A local file cannot produce a usable public sharing URL.

## Facts to confirm

- All 14 listing headers advertise 2 bedrooms and 2 bathrooms. Abbotts Wharf's description mentions one bathroom and supplies no floorplan, so it is prominently flagged for agent confirmation.
- Commercial Road is £2,250 rent plus £150/month heating and cooling; other costs are not included in the displayed £2,400 subtotal.
- Yeoman Court explicitly excludes utilities, council tax, telephone and broadband. Other listings do not explicitly confirm inclusion.
- Fizzy Stepney Green uses illustrative photos/floorplans and advertises unfurnished accommodation with furnishing options. Confirm the exact flat, balcony and package.
- Lamington Heights quotes 807 and 811 sq ft in different parts of its description. Sky View Tower lists 992 sq ft in the header and over 900 sq ft in the description.
- Deposit alternatives are not described as free. Terms and fees require confirmation.
- Council tax bands are copied from the adverts; annual charges have not been estimated.
- Dates and letting terms are advertised information; confirm current availability and tenancy terms with the agent.
- Photos/floorplans remain hosted by Rightmove and may disappear when adverts are removed. Rights belong to their respective owners. Every card links to its source advert.

Edit `listings.js` to update the snapshot. No installation or build step is required.

Added Violet Road (£2,550/month) and Maltings Close (£2,300/month). Both advertise two bedrooms, two bathrooms and a floorplan. Violet Road uses example photos and requires confirmation of the exact balcony. Maltings Close lists conflicting areas: 624 sq ft / 58 sq m in the header versus 64 sq m in the description.
