# publishing-to-npm
Notes for publishing a node package to NPM.

## Add new packages to the NPM registry

https://docs.npmjs.com/creating-and-publishing-unscoped-public-packages

## Update existing published public packages

https://docs.npmjs.com/updating-your-published-package-version-number

To change the version number in package.json, on the command line, in the package root directory, run the following command, replacing <update_type> with one of the semantic versioning release types (patch, major, or minor):

```bash
npm version <update_type>
```
