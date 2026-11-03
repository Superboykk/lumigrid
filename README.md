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

Deploy `dist` to any static HTTPS hosting service. The app currently uses root-relative asset URLs, so deploy at the domain root.

All photo processing runs locally in the browser. No photo upload service, database or account system is included. HEIC decoding depends on browser support. Native file sharing requires browser support and a secure context. Test touch gestures and saving on a physical iPhone before production use.

The hosted version: https://lumigrid-photo-studio.shinyscarf.chatgpt.site

