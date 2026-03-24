# Scoop bucket for localtaskrepo CLIs

This repository hosts the Scoop manifests for the `lotar` and `autospec` CLIs.
Each tag update publishes a fresh manifest in `bucket/` that points at the signed Windows release uploaded from the matching main repository.

## Usage

```bash
scoop bucket add lotar https://github.com/localtaskrepo/scoop-lotar
scoop install lotar
scoop install autospec
```
