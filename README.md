# Haku extension catalog

This repository contains the curated index for Haku extensions. Haku reads `haku-catalog.json` from the default branch. Each entry points to a public GitHub repository and recommends a tagged version. GitHub repositories publish their own manifests and artifacts.

Set the catalog URL on a Haku instance with extension support.

```sh
HAKU_V1_EXTENSION_CATALOG=https://github.com/satorusaka/haku-extension-catalog
```

The [sample storage metrics extension](https://github.com/satorusaka/haku-sample-metrics) provides a read-only JSON connector, a widget, and a local provider fixture.
