# Yak front door (test)

A fixed address for Yak's QR codes while the platform runs on a test computer whose address changes.

- `/.well-known/apple-app-site-association` tells Apple that this address belongs to the Yak app and its App Clip.
- `config.json` holds the platform's current address. It's updated automatically when the platform starts.
- `404.html` (and `index.html`) forward every other path to the same path on the platform, for phones without the App Clip and for Android.

There is nothing secret here: no keys, passwords, staff links or customer data.
