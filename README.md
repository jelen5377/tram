# TramvajHra

Projekt je pripraveny pro dve veci:

- publikaci hry na GitHub Pages z `index.html`
- vzdaleny build debug APK pres GitHub Actions a Capacitor
- automaticke generovani Android ikonky z `assets/logo.png`

## GitHub Pages

Po nahrani do repozitare a zapnuti Pages pobezi hra primo z rootu repozitare.

## Android APK

Workflow `Build Debug APK` udela vzdaleny build a vystavi artifact s APK.

Postup:

1. push do `main`
2. otevrit `Actions`
3. pockat na workflow `Build Debug APK`
4. stahnout artifact `tramvaj-hra-debug-apk`

## Soubory

- `index.html` = web pro GitHub Pages
- `www/index.html` = stejny obsah pro Capacitor Android build
- `assets/logo.png` = zdroj vlastni Android ikonky
