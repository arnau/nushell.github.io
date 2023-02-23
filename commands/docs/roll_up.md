---
title: roll up
categories: |
  filters
version: 0.76.0
filters: |
  Roll table rows up
usage: |
  Roll table rows up
---

# <code>{{ $frontmatter.title }}</code> for filters

<div class='command-title'>{{ $frontmatter.filters }}</div>

## Signature

```> roll up --by```

## Parameters

 -  `--by {int}`: Number of rows to roll

## Examples

Rolls rows up
```shell
> [[a b]; [1 2] [3 4] [5 6]] | roll up
```