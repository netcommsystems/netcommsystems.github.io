# NetComm Systems Website

Static one-page website for GitHub Pages.

## Before publishing

Edit `index.html` and replace:

- `XXX-XXX-XXXX` with your phone number as visible text
- `+10000000000` with your phone number in tel format, for example `+16025551234`
- `Arizona ROC: XXXXXXX` with your ROC number
- `mark@netcommsystems.com` if your email is different

## Files included

- `index.html` — website content
- `style.css` — website styling using your colors: `#0A2E6F`, `#0066D6`, and `#FFFFFF`
- `assets/logo.svg` — your NCS logo in the header and hero section
- `assets/favicon.svg` — browser tab icon
- `bimi.svg` — BIMI logo file for email logo setup

## GitHub Pages

Upload the contents of this folder to a GitHub repository, then enable:

Settings → Pages → Deploy from branch → main → root

## BIMI

After the site is live, your BIMI SVG should be available at:

`https://netcommsystems.com/bimi.svg`

Then add this DNS TXT record:

Host: `default._bimi`

Value: `v=BIMI1; l=https://netcommsystems.com/bimi.svg;`
