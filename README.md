# Hypernova Landing Page

<img src="https://i.imgur.com/PGYf67C.png" width="100%">

## Basic Customization

At the top of `./assets/js/main.js`, adjust the title and URLs in the config section.

### Server Status URL

The URL must be the **entire** URL that is returned when loading Plex from an external network, not through plex.tv. For example, if a Plex server is hosted at IP `1.1.1.1` or at URL `test.com`, the input would be valid and invalid:

`1.1.1.1:32400/web/index.html` or `test.com:32400/web/index.html` are CORRECT.
`1.1.1.1:32400` or `test.com:32400` are INCORRECT.

## External Scripts
- [Bootstrap](https://getbootstrap.com/)
- [JQuery](https://jquery.com/)
- [Popper.JS](https://popper.js.org/)
- [Scroll Reveal](https://github.com/jlmakes/scrollreveal)

## Images Used
- Any logos are taken from their respective sites
- The icon/logo for Hypernova is taken from [here](https://twitter.com/hypernovaserver)
  - (An attempt was made to contact the Twitter account, with no response. If there is ever an issue with the use with the logo, please let me know!)

## Docker
- Hypernova can be hosted on port 8080 with no additional modification by running `docker-compose up -d`
