# Theme "A"

## Styles and JS
SCSS and JS should be written to the "_prebuilt-assets" directory.
There are two npm scripts that compile both SCSS and JS and move the corresponding files into "assets/".
It seems that Shopify does not allow subdirectories inside "assets", so we use "_prebuilt-assets" with appropriate subdirectories for scss and js.

### Conventions:
Regardless of whether it is SCSS or JS, sections and components must be created in the appropriate directory and have the suffix "sections" or "component".

### Compile & Preview changes
`compile-styles` => compiles and compresses SCSS files

`compile-js` => NOTHING YET

`serve` => compiles both SCSS and JS and serves the theme via Shopify-CLI as a preview. Once its done, a preview link will appear in the terminal

## Deployment
...


-----
Theme based on Dawn by Shopify