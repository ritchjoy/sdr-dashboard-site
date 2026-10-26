# SDR Dashboard (site)

Password-protected Trucker Path SDR Dashboard, served with GitHub Pages.

`index.html` holds only encrypted data (AES-256, key derived from the team password with
PBKDF2-SHA256). Without the password the page shows nothing but the unlock screen. Ask your
sales manager for the password.

This repo is generated; don't edit it by hand. It's built by `site.py` in the private
`SDR-Dashboard` repo.
