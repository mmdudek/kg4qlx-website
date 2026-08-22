KG4QLX LOCAL WEBSITE
=====================

This is a cleaned, Wix-free local version of the two KG4QLX Amateur Radio pages.

Files:
  index.html       Main Amateur Radio page
  cw.html          CW page
  style.css        Local styling
  widgets/         The actual embedded HTML widgets from the Wix export
  images/          Images used by the original pages

Internet-dependent pieces intentionally retained:
  - HamQSL solar/propagation image (live URL)
  - Time.is UTC widget
  - QRZ callsign lookup (opens qrz.com)
  - External links

No Wix JavaScript/runtime is required.

To view:
  Option 1: double-click index.html.
  Option 2 (recommended if a browser blocks local iframe/script behavior):
      python -m http.server 8000
  then open http://localhost:8000/

The site is not published to the Internet by this setup.
