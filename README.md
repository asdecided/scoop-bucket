# AsDecided Scoop bucket

Official [Scoop](https://scoop.sh/) manifests for AsDecided.

## Install

```powershell
scoop bucket add asdecided https://github.com/asdecided/scoop-bucket
scoop install asdecided
```

Or, after adding the bucket, install it explicitly as
`asdecided/asdecided`.

The package installs both native executables:

- `decided`
- `decided-mcp`

## Upgrade

```powershell
scoop update
scoop update asdecided
```

The manifest follows stable GitHub releases from
[`asdecided/core`](https://github.com/asdecided/core/releases) and verifies the
Windows archive with SHA-256 before installation.
