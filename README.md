# Dead By Daylight Modding Documentation

Pull requests should target the `dev` branch.

Before you submit changes,
you should probably follow the Development Setup directions below
to verify that the pages are displaying as expected.

Documentation for other mods is also served through the same site.
If you have written documentation for your mod and would like it to be added, contact us.

## Development Setup

Although you can edit the `.adoc` files with just about any editor out there,
we suggest either Visual Studio Code (with the
[Asciidoc](https://marketplace.visualstudio.com/items?itemName=asciidoctor.asciidoctor-vscode)
and [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) plugins)
or IntelliJ.

In order to see what the pages will look like on the live site before being deployed,
follow the below directions.

### Installing

1. Install [Node.js](https://nodejs.org/en/download/) and [Yarn Package Manager](https://classic.yarnpkg.com/en/docs/install) through your preferred method

2. Use Yarn to install dependencies

```bash
yarn install
```

### Building

To build the docs:

```bash
yarn run build
```


The output HTML files can be found in `\build\site`.
