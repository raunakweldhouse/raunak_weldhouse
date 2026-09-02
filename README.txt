RAUNAK WELD HOUSE — WEBSITE PACKAGE
=====================================

WHAT'S INSIDE
  index.html      Homepage: about, products, contact
  privacy.html    Full privacy policy (extracted from your PDF, no PDF hosted)
  terms.html      Full terms and conditions (extracted from your PDF, no PDF hosted)
  styles.css      Single stylesheet, no external fonts or CDNs
  assets/         Logo placeholder (SVG) and your five product photos
  README.txt      This file

HOW TO VIEW LOCALLY
  1. Unzip the package.
  2. Double click index.html, or right click it and choose "Open with"
     your browser. No server or install is needed.
  3. Click through to Privacy and Terms from the footer to confirm both
     load correctly.
  4. Resize the browser window (or open on a phone) to check the menu
     collapses into a "Menu" button under about 760px width.

HOW TO DEPLOY
  Upload the whole folder, keeping the same structure, to any standard
  web host (shared hosting, Netlify, GitHub Pages, etc). index.html
  should sit at the root of the site or the folder you point your
  domain at. No build step, database, or server-side code is required.

BEFORE YOU SUBMIT FOR WHATSAPP BUSINESS APPROVAL
  [ ] Replace assets/logo.svg with your real logo if you have one on file
      (keep the filename "logo.svg" or update the <img src> in all three
      HTML files to match a new filename).
  [ ] Re-read privacy.html and terms.html end to end. They currently
      contain the exact text extracted from the PDF you supplied.
      If your lawyer or team wants different wording, edit those two
      files directly (each clause is inside its own <h2>/<p> pair).
  [ ] Confirm the phone numbers, email, address and GSTIN in the
      Contact section and in privacy.html/terms.html match your current
      records.
  [ ] If you get a final domain name, add a canonical link tag to the
      <head> of each page: <link rel="canonical" href="https://yourdomain.com/index.html">
      (this was left out because no domain was provided).

VALIDATION REPORT
  HTML structure    Parsed with Python's html.parser on all three
                     pages with no unclosed-tag or markup errors.
  Duplicate IDs      Checked per page — none found.
  Link check         Every href and src in index.html, privacy.html and
                     terms.html resolves to a real file in this package
                     (styles.css, the three HTML pages, all five product
                     images, logo.svg). tel:, mailto: and in-page #
                     anchors were excluded from the file check, as they
                     are not file links.
  PDF handling        Neither PDF you supplied is included in this
                     package or linked from any page. Their text was
                     extracted and placed directly into privacy.html
                     and terms.html as semantic HTML.
  External resources  No CDNs, external fonts, tracking scripts, or
                     analytics anywhere in the code. Only system fonts
                     are used (Segoe UI / Helvetica / Arial family).
  Accessibility       Every <img> has descriptive alt text. The mobile
                     menu button is keyboard operable and updates
                     aria-expanded. Focus states are visible (a copper
                     outline appears on keyboard focus). Body text runs
                     on a dark charcoal on warm paper background, and
                     the palette was chosen to keep normal-size text at
                     a comfortable contrast level. It's worth running a
                     contrast checker (e.g. WebAIM) once you finalize
                     any color changes, since I could not run an
                     automated contrast checker inside this environment.
  Mobile responsiveness  Layout is fluid down to small phone widths;
                     the header nav collapses into a toggle button
                     below 760px, and the about/products/contact grids
                     stack into a single column.

  NOT AUTOMATICALLY VERIFIED
  I was not able to render the page in a real browser inside this
  environment (no network access to fetch a browser), so please do a
  final manual pass on an actual phone and desktop browser before
  submitting for WhatsApp Business approval, and open the browser
  console to confirm there are no JavaScript errors (there is only one
  small script per page, for the mobile menu toggle).

CONTENT NOTES
  The About Us text, and all five product descriptions, were written
  based on: the company details visible on your business card image
  (name, contacts, address, GSTIN), and what's printed on each product's
  own box/label in the photos you supplied. Nothing was invented beyond
  that — if you want more specific technical specs (amperage ratings,
  exact size ranges, pricing) added to any product, send those details
  and I can drop them straight into the matching paragraph in
  index.html.
