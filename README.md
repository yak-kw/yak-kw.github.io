# Yak front door (old address)

Yak's first fixed address for its QR codes, used while the platform ran on a test computer whose address changed. Since 14 November 2026 the platform runs on its own server at **https://yak-kw.com**.

- `404.html` (and `index.html`) forward every path to the same path on https://yak-kw.com, so codes already printed with this address keep working.
- `/.well-known/apple-app-site-association` stays, so the demo app and App Clip keep opening from codes printed with this address. yak-kw.com has its own copy.
- `config.json` is no longer read. The PC test platform still rewrites it when it starts; that changes nothing.

There is nothing secret here: no keys, passwords, staff links or customer data.
