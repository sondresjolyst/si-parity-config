# si-parity-config

The [parity-cli](https://github.com/sondresjolyst/parity-cli) config for the sondresjolyst repos: `parity.yml`, `templates/` and `workflows/` define what every managed repo should look like.

Install [uv](https://docs.astral.sh/uv/), then run it from this directory:

```sh
uv run parity status
uv run parity apply
```

`uv.lock` pins the parity-cli version. Run `uv lock --upgrade-package parity-cli` to update it.
