# Anatomech — Sports and Wellness

Extract the ZIP, then open **sports.html** or **wellness.html** in your browser. Keep the folders together. No installation needed. Linked fonts and icons require internet.

These are two landing pages. The parent-company link goes to https://www.anatomech.co/. Shopping links go to https://kues.in/. No local cart, checkout, wishlist or shop page is included.

## Where to edit

| Change | File |
| --- | --- |
| Sports text, launch strip, product showcases and images | sports.html |
| Wellness text, launch panel, product showcases and images | wellness.html |
| Sports and Wellness colors | css/themes.css |
| Launch layout and size | css/launch.css |
| Shared page layout | css/styles.css |
| Navigation and footer styling | css/landing.css |
| Enquiry email destination | js/settings.js |
| Demo form fields and email handoff | js/enquiry.js |
| Shared interactions | js/main.js |

Navigation and footer markup are in both HTML files; update both when changing shared links. All visible page content is directly in HTML. Replace images in assets with the same filenames or change the relevant img src. Keep IDs and data attributes intact when editing copy.

Both headers use the KUE logo at assets/kue-logo.png, linked to the KUE store, with a separate Back to Anatomech link. Replace that image to change the logo. Header sizing is in css/landing.css.

## Demo enquiry

The form opens a prepared email to info@anatomech.com. The visitor must send the email; the form does not automatically submit or confirm a booking. Change the recipient in js/settings.js. A backend or form service can replace the email handoff later.

## Publishing later

Upload the two HTML files and their folders to your chosen host. The administrator of Anatomech can link to the live Sports and Wellness pages. This package does not change or publish the existing website.
