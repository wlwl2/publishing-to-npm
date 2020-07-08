# publishing-to-npm
Notes for publishing a node package to NPM.

## Add a new package to the NPM registry

https://docs.npmjs.com/creating-and-publishing-unscoped-public-packages

See:

https://github.com/wlwl2/case-utils/blob/master/package.json

For an example of what the package.json should look like.

## Update an existing published public package

https://docs.npmjs.com/updating-your-published-package-version-number

To change the version number in package.json, on the command line, in the package root directory, run the following command, replacing <update_type> with one of the semantic versioning release types (patch, major, or minor):

```bash
npm version <update_type>
```

### Notes on semantic versioning

Given a version number MAJOR.MINOR.PATCH, increment the:

- MAJOR version when you make incompatible API changes,
- MINOR version when you add functionality in a backwards compatible manner, and
- PATCH version when you make backwards compatible bug fixes.

https://semver.org/
