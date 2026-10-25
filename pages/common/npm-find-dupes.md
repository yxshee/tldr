# npm find-dupes

> Identify duplicate dependencies in `node_modules`.
> More information: <https://docs.npmjs.com/cli/npm-find-dupes/>.

- List all duplicate packages within `node_modules`:

`npm find-dupes`

- Include `devDependencies` in duplicate detection:

`npm find-dupes --include dev`

- Exclude optional dependencies from duplicate detection:

`npm find-dupes --omit optional`

- Set the logging level for output:

`npm find-dupes --loglevel {{silent|error|warn|info|verbose}}`

- Output duplicate information in JSON format:

`npm find-dupes --json`
