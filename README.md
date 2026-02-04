
# dasl.ing

DASL (Data-Addressed Structures, pronounced "dazzle") is a small set of simple, standard primitives for working with content-addressed, linked data. The design is inspired by subcomponents of the [IPFS](http://ipfs.tech) universe, but simplified to improve interoperability, decrease costs, and work well with the web.

This repository generates a website containing the DASL specs and more. Go to https://dasl.ing/ to read it!

## Contributing

Contributions are welcome! Here's how you can help:

- Feedback, questions, or bugs: Create an [issue](https://github.com/darobin/dasl.ing/issues)
- Minor fixes: Feel free to open a PR directly
- Larger changes or new specs: Please start with an [issue](https://github.com/darobin/dasl.ing/issues) describing your proposal
- Join a call: [Monthly sessions on Luma](https://luma.com/cid-congress)

## Developing

Be **particularly** careful not to edit the `.html` files but rather the `.src.html`
ones. Otherwise you'll overwrite yourself.

To work on the site locally, run two commands in separate terminals:
* `npm run watch` will re-generate files on save to `.src.html` files
* `npm run dev` in a second terminal will open up a static server. The static server
  does not hot-reload, so you'll need to refresh the page to see changes.

Please note that this project follows the [IPFS Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md). Happy hacking!
