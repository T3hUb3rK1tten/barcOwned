# barcOwned

**"Like a Rubber Ducky for barcode scanners"**

The humble barcode scanner is used in virtually every industry that deals with physical products. While it may look simple, these devices actually have a surprising amount of features and complexity hidden inside. Using esoteric programming barcodes, one can instruct a scanner to type special keys and gain keyboard-like access to a machine. This allows one to execute attacks like running commands in a shell, manipulating system objects, or even editing/creating files on disk.

This tool, barcOwned (pronounced "barc-owned" or "bar-coned") provides a simple web tool to program a barcode scanner with certain rules, or "setup scripts", that can be used to deliver a payload. The tool is easy to customize with a minimal amount of Javascript knowledge and pull requests are welcome. Different manufacturers and models of barcode scanners use different programming barcodes, but after the baseline work of adding a new model is complete, existing scripts can be ported easily.

## Documentation

Docs are available at [barcowned.com/docs](https://barcowned.com/docs).

The markdown source for the docs can be viewed offline in the [`_docs_src`](_docs_src) directory.

### Contributing + Building

barcOwned will not work when served from a local file system because it retrieves the setup scripts and payload files using AJAX. Instead, we recommend using a simple, local HTTP server for development and field execution. On Windows, we recommend [HTTP File Server](http://www.rejetto.com/hfs/).

For instructions on building barcOwned and submitting patches, see [the docs](https://barcowned.com/docs/contributing/readme.html)

## License

Open source under the [MIT License](license.md).

The project also includes the following other open source software:

|                       Project                     |    License   |
|                          -                        |       -      |
|   [BWIPJS](https://github.com/metafloor/bwip-js)  |      MIT     |
|     [jQuery](https://github.com/jquery/jquery)    |      MIT     |
|   [Bootstrap](https://github.com/twbs/bootstrap)  |      MIT     |
|  [GitBook](https://github.com/GitbookIO/gitbook)  |  Apache 2.0  |
