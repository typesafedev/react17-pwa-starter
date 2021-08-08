# react17-pwa-starter with redux

React 17 PWA starter - CRA

## Demo built in PWA using basic CRA

``` sh
cd react17-pwa-starter
# npx create-react-app --template redux-typescript ./
npx create-react-app --template cra-template-pwa-typescript ./

# PWA enabled only in production build
# To improve developer ergonomics, install serve and serve production build
# npm i serve
# "start:pwa": "npm run build && serve -s build -l 5008"
#
# Build prod and serve prod build
# npm run start:pwa

# Now service worker continues to run even if serve is shut down!
# Go to https://localhost:5008
# To shut down service worker, in DevTools>Applications>Service Worker - Click unregister.
```
