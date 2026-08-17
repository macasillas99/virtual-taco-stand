# Virtual Taco Stand

This is the starter project for the WEB 425 Virtual Taco Stand. It supplies the
course environment, global styling library, image assets, and baseline Angular
configuration. The application features are implemented during the weekly
readings.

## Requirements

- NVM
- Node.js 24.18.0
- npm 11.x

The project includes an `.nvmrc` file. From the project directory, select the
supported Node.js version before installing dependencies:

```bash
nvm install
nvm use
npm install
```

## Development server

Run `npm start`, then navigate to `http://localhost:4200/`. The application
reloads automatically when source files change.

## Production build

Run `npm run build`. Build output is written to `dist/virtual-taco-stand/`.

## Unit tests

Run the complete test suite once with:

```bash
npm test -- --watch=false
```

The project uses Angular 22.0.7 and the Angular esbuild-based application builder.

## Course stylesheet

The complete visual system is contained in `src/styles/w4.css`. It is loaded
globally through `angular.json`, in the same way a project would load a CSS
framework such as Bootstrap.

Component templates use short, reusable `w4-` classes for layout, cards,
buttons, forms, navigation, and responsive behavior. Angular components do not
contain inline style definitions, so course exercises can focus on Angular
without requiring students to rebuild the finished design each week.

`src/styles.css` is reserved for optional application-specific overrides.

## Image assets

The theme-matched image set is stored in `public/assets`. Photographic assets
use optimized WebP files for responsive performance, while the wordmark and
favicon use scalable SVG artwork so the brand remains sharp at every viewport
size.
