ABHINANDAN BANDHEJ - static website (Hostinger / any static hosting ready)
Test locally: open this folder in a terminal and run  python -m http.server 8000  then visit http://localhost:8000/
BEFORE LAUNCH:
1. js/config.js        -> Instagram + Facebook are set. YouTube is "#" for now: paste the real channel URL when ready (also update the href in the header/footer icon if you want it to work without JS)
2. js/contact.js       -> paste Formspree (or similar) endpoint into FORM_ENDPOINT (until then the form opens WhatsApp)
3. Replace YOURDOMAIN.com in all HTML, sitemap.xml, robots.txt, .htaccess
4. Confirm the WhatsApp number (currently the same as the phone number 95125 22485)
5. Activate SSL before enabling the HTTPS redirect in .htaccess
6. Replace low-resolution photos in assets/images/ with higher quality originals (same file names) when available
