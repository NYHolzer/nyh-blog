# Astro Routing
## No routing config. Just add a file and walla!

### Static Routes
Any page that has a `.astro` will automatically be assigned a route based on the location within the files organization within `src/pages` folder.

### Dynamic Routes
You can generate routes dynamically based on multiple matching pages. `src/pages/authors/[author].astro`