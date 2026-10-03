# Good Goods

A simple static demo storefront with product search and an in-memory shopping bag. It is designed to look like a regular shopping site and contains no visible attack demonstrations.

## Run it

Open `index.html` directly in a browser or serve this folder with any static web server. The site has no dependencies.

## About testing

This frontend can help exercise normal browsing and static HTTP traffic in your home lab. It does not implement a backend, login, checkout, database, or payment processing, so it is not itself a vulnerable shopping application. Its product search filters the products already loaded in the browser, and its bag exists only in memory.

Use your own authorized lab setup for security validation. Keep test systems isolated and do not expose intentionally vulnerable services to the public internet.
