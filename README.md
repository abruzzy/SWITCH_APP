# Switch App

Switch end-user mobile app, shown in iOS and Android device frames.

## Run

Serve the folder over HTTP (opening the file directly from disk blocks the imports):

```
npx serve .
# or
python3 -m http.server 8080
```

Then open `index.html` (redirects to `Switch Mobile App.dc.html`).

Works as-is on GitHub Pages: Settings → Pages → deploy from the main branch root.

## Files

- `Switch Mobile App.dc.html` — main entry
- `Switch App Screens.dc.html — all app screens (imported by the main file)`
- `ios-frame.jsx / android-frame.jsx — device frames`
- `support.js` — runtime (required)
- `brand/` — logos and wallet-provider marks
- `index.html` — redirect to the main entry
