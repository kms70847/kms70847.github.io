Proof of concept of a pure javascript NGUI save file reader.

# Dependencies
`ngui_reader.bundled.js` is a standalone js file that requires no explicit dependencies. Include it in your html and call `decode_ngu_save(yourArrayBufFer)`.

To create the bundled js from source, you will require:
 - Node
 - [Pako](https://github.com/nodeca/pako)
 - [Browserify](https://browserify.org/)

Use `npm` to install Pako and Browserify as detailed on their documentation pages. Then run `browserify ngui_reader.js -o ngui_reader.bundled.js

# License

Pako is licensed under MIT and ZLIB.

My code is licensed under MIT.
