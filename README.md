# Mythos

A responsive landing page built with HTML, Sass, and JavaScript.

## Run locally

1. Install the dependencies:

   ```bash
   npm install
   ```

2. Build the CSS:

   ```bash
   npm run build
   ```

3. Open `index.html` with a local server, such as VS Code Live Server.

During development, use Sass watch mode to rebuild the CSS automatically:

```bash
npm run sass:watch
```

## Production build

Run:

```bash
npm run build
```

This compiles `app/sass/style.scss` into `dist/style.css`. Deploy `index.html`, `app/`, `img/`, and the generated `dist/` folder to your hosting provider.