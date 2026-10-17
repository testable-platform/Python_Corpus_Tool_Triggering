# Python Corpus -- Tool Triggering (Synthetic Data)

`main` carries only this overview -- it holds no project code. Every other
branch in this repository is one cell of `testable-platform/python-corpus`, split out to carry
only the `Tool Triggering (Synthetic Data)/` folder (plus that branch's own build scaffolding).

This repository was produced by splitting `testable-platform/python-corpus` by task folder.
`testable-platform/python-corpus` itself was not modified by this split and still holds the
full combined corpus.

## Scope

This repo covers every version/build-tool/package-manager/architecture combination (216 branches).

## Branch naming

Branch names are unchanged from `testable-platform/python-corpus`:

```
PY_V{ver}_{BUNDLER}_{PKGMGR}_{ARCH}
```

## Finding a branch

Each branch's own `README.md` describes its exact cell (version, bundler,
package manager, architecture) and its tool roster, trimmed to the parts
relevant to `Tool Triggering (Synthetic Data)/`. `dataset.json` on each branch is the
machine-readable answer key for that cell.

## History

Each branch's commit history is carried over unchanged from `testable-platform/python-corpus`,
with one additional commit on top that removes the folders not relevant to
this repo. Nothing was squashed or rewritten.
