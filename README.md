# FRead Scoop bucket

```powershell
scoop bucket add fread https://github.com/FRead-Now/scoop-bucket
scoop install fread-tools
```

Installs FRead's editor tools, fux and FRead's fux snippet library. See
[fread-tools](https://github.com/FRead-Now/fread-tools) for what they are and
how they are matched to the catalog.

`bucket/fread-tools.json` and `bucket/fux.json` are written by each release;
hand edits are overwritten. `fux.json` is here because fux has no bucket of its
own: it installs the fux release the tools were released against.
