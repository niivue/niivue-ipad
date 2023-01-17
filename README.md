# NiiVue iPad

This is the repo for the NiiVue iPad app. The app is compiled to a native iPadOS applicaiton using Capacitor.js

## Development setup and installation

Make sure you have the **latest** Xcode version installed, and the **latest** iOS SDK versions

### clone the repo and git submodules

```
git clone --recurse-submodules git@github.com:niivue/niivue-ipad.git
```

### Run NPM install

```
cd niivue-ipad
npm install
```

### Running in dev mode with hot reload in a browser

```
npm run dev
```

### Building for ipad

```
npm run build
npx cap sync 
npx cap open ios
```

Then run from Xcode with the Play button