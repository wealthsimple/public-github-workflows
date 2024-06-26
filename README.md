# public-github-workflows

> Reusable GitHub Actions workflows for our public repositories

## Overview

Usage:

```yaml
jobs:
  build_and_publish:
    name: Build and Publish
    uses: wealthsimple/public-github-workflows/.github/workflows/ruby-gem-build.yaml@main
    secrets: inherit
```
