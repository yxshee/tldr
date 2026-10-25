# npm dedupe

> Reduce duplication in the `node_modules` directory.
> More information: <https://docs.npmjs.com/cli/npm-dedupe/>.

- Deduplicate packages in `node_modules`:

`npm {{[ddp|dedupe]}}`

- Simulate deduplication, showing what would be removed or changed:

`npm {{[ddp|dedupe]}} --dry-run`

- Skip optional/peer dependencies during deduplication:

`npm {{[ddp|dedupe]}} --omit {{optional|peer}}`

- Enable detailed logging for troubleshooting:

`npm {{[ddp|dedupe]}} --loglevel verbose`
