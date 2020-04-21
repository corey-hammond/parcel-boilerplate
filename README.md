# Parcel Boilerplate

### To start:

Run npm install to install dependencies

Installed packages:

```
npm i -D parcel-bundler sass @babel/core @babel/plugin-transform-runtime @babel/runtime-corejs2
```

Scripts:

```
"dev": "rm -rf ./development && rm -rf ./.cache && parcel public/index.html --out-dir development -p 3000",
"build": "parcel build public/index.html --out-dir dist --public-url ./"
```

