# npm explain

> Explain how a package is installed, detailing its dependencies and reasons for inclusion.
> More information: <https://docs.npmjs.com/cli/explain/>.

- Explain why a specific package is installed:

`npm {{[why|explain]}} {{package_name}}`

- Show explanation in JSON format:

`npm {{[why|explain]}} {{package_name}} --json`

- Explain why a specific copy of a package is installed, using its path inside `node_modules`:

`npm {{[why|explain]}} node_modules/{{path/to/package}}`
