# Test Capacitor App

This capacitor app has resources for Icon and Splash that can be used with @capacitor/assets.

To make this app a PWA:
```bash
npx ng add @angular/pwa --defaults --skip-confirmation true
```

Then to generate assets for the PWA:
```bash
npx @capacitor/assets generate --pwa --pwaManifestPath './src/manifest.webmanifest'
```