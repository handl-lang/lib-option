# lib-option

`option` — Option type for Handl (pure handl).

## Layout

```text
src/index.hnl         the library
src/option.test.hnl   the .hnl test suite
pkg.hnl               package manifest — modules, deps, description, license
workflows/gate.yaml                 bupha entry (handl-gates) → scripts/hnl-gate.sh
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.
