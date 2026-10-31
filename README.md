# Mythos

A responsive landing page built with HTML, Sass, and JavaScript.

## Run locally

1. Install the dependencies:

   ```bash
   npm install
   ```

2. Start the Vite development server:

   ```bash
   npm run dev
   ```

3. Open the local URL shown in the terminal.

During development, Vite automatically compiles the Sass imported by
`app/js/main.js`. To compile Sass directly into `dist/style.css`, use:

```bash
npm run sass
```

## Project structure

- `index.html` - Main page entry point.
- `app/js/` - JavaScript source files.
- `app/sass/` - Sass source files.
- `public/` - Static assets copied directly to the production build.
- `dist/` - Generated production files created by Vite.

## Production build

Create an optimized production build:

```bash
npm run build
```

Vite bundles the JavaScript, compiles the Sass, and copies the required assets
into `dist/`.

To deploy manually, upload the contents of `dist/` to your hosting
provider.

The generated `dist/` folder contains the files required to host the finished
static site on a service such as Netlify.
