# Seneca Street Liquor one-page site

Domain used in this package:
senecastreetliquor.com

Files that belong in the ROOT of the GitHub repository:
- index.html
- CNAME
- store-info-transparent.png
- presave-cover.jpg
- vinyl-preorder.jpg

## Updating the two placeholder buttons

Open index.html and search for:

REPLACE # BELOW WITH YOUR REAL PRE-SAVE URL

Change:
href="#"
to:
href="YOUR_REAL_PRESAVE_URL"

Then remove:
onclick="placeholderMessage('PRE-SAVE'); return false;"

Do the same for the vinyl button.

## Google Maps

The embedded map uses:
403 N Seneca St, Wichita, KS 67203

The OPEN IN GOOGLE MAPS button uses the supplied short Google Maps link.
