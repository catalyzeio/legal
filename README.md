# Datica Legal Documentation

The Datica Legal Docs exist to outline Datica Health, Inc.'s terms of service as well as other legal documentation pertaining to, but not restricted to, Datica products, software, web documentation or otherwise. These docs have been open sourced in order to help the health IT community grow and improve patient care through secure, usable software.

- The license for these docs can be found [here](https://github.com/catalyzeio/legal/blob/master/LICENSE.md%20).
- The contributing guidelines can be found [here](https://github.com/catalyzeio/legal/blob/master/CONTRIBUTING.md).

### How to build the docs

- Download this repository
- cd `policies`
- `bundle install`

*Commands*
- `rake run` will run the site locally
- `rake sass` will compile any changes made to `assets/css/styles.scss`
- `rake build` will build the static site into the `build` directory
- `rake serve_static` will create a simple HTTP server for the `build` directory