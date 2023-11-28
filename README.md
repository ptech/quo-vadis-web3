# Quo Vadis Web3

## Usage

### Starting the development server
Run `npm start` or `npm run dev` to start the development server (at `localhost:4321`).

### Building
Run `npm run build` to build the application. The built code will be on a `dist` folder.

Run `npm run preview` to server the built code.

## Project Structure

Inside the project, you'll see the following folders and files:

```text
/
├── public/
│   ├── fonts
│   ├── images
│   ├── logo
│   ├── media
│   ├── partner-logos
│   └── favicon.png
├── src/
│   ├── components/
│   │   ├── Footer.astro
│   │   ├── Modal.astro
│   │   ├── Nav.astro
│   │   └── Hero.astro
│   ├── content/
│   │   ├── board.json
│   │   ├── footer.json
│   │   └── partners.json
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.
