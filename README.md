# HP Billing — QuickBooks connection pages

The public pages QuickBooks Online points at for Heschmeyer Pools' HP Billing app.
The app itself runs on the office computer; nothing here holds data or secrets.

- `callback.html` — the Redirect URI. Passes QuickBooks' one-time answer straight on to
  HP Billing at `http://localhost:8788/api/qbo/callback`, in the same browser.
- `index.html` — host / launch page.
- `disconnect.html` — where QuickBooks sends you after disconnecting.
- `privacy.html`, `terms.html` — privacy policy and end-user licence agreement.
