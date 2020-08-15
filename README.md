# Art 4 The Amazon - Charity Website


## 1. About The Project

https://www.art4theamazon.org/

```
Site uses Tailwincss and pugjs. Site made for the Amazon Art initiative to help indigenous families during the world crisis.
```

## 2. Installation

```
# Install dependencies
npm install 

# Run dev server with live preview (Browsersync)
npm run watch

# Or make a production build 
npm run build
```

If you want PurgeCSS to delete unnecessary CSS classes (and create a smaller CSS file as a result) set NODE_ENV to production, e.g:

```
# Make a production build and automatically use PurgeCSS
# to remove CSS classes that aren't used.

NODE_ENV=production npm run build
```

