# LumiGrid

Thai mobile-first photo grid maker built with React, TypeScript, Tailwind CSS and Canvas.

## Run locally

Requires Node.js 20.19+ or 22.12+.

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
```

Deploy `dist` to any static HTTPS hosting service. Relative asset URLs support GitHub Pages project hosting.

All photo processing runs locally in the browser. No photo upload service, database or account system is included. HEIC decoding depends on browser support. Native file sharing requires browser support and a secure context. Test touch gestures and saving on a physical iPhone before production use.

Live app: https://superboykk.github.io/lumigrid/

Push changes to main to automatically build and deploy with GitHub Actions.
