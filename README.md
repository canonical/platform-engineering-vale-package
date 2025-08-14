# Platform Engineering Vale Package

This repository contains a [Vale-compatible](https://vale.sh/) implementation of the Platform Engineering Documentation Style guide.

This package enherites it's style from the [Canonical Documentation Style guide](https://github.com/canonical/documentation-style-guide).

## Getting Started

To get started, add the package to your configuration file (as shown below) and then run `vale sync`.

```ini
StylesPath = .vale/styles # Use your normal style path here.
Packages = https://github.com/canonical/platform-engineering-vale-package/releases/download/latest/pfe-vale.zip

Vocab = PFE, local

[*]
BasedOnStyles = PFE
```

See [Vale's documentation on packages](https://vale.sh/docs/topics/packages/) for more information.

