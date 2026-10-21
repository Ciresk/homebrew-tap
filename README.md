# Ciresk Homebrew tap

```sh
brew install ciresk/tap/ciresk-ci      # Ciresk CI: `ciresk ci ...`; installs the `ciresk` umbrella as its dependency
brew upgrade ciresk-ci                 # updates (ciresk update defers to brew for this install)
```

Then `ciresk ci auth login`. The formulas download the release archives from https://get.ciresk.com with
their sha256 pinned (layout: [install/LAYOUT.md](https://github.com/Ciresk/ciresk-ci/blob/main/install/LAYOUT.md)
in Ciresk/ciresk-ci); `scripts/update-formulas.sh <ciresk tag> <ciresk-ci tag>` regenerates them after a
release. Every install method is in the
[install guide](https://github.com/Ciresk/ciresk-ci/blob/main/docs/guides/install.md).
