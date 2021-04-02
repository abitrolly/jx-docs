---
title: jx test gc
linktitle: gc
type: docs
description: 
aliases:
  - jx-test_gc
---

## jx-test gc

Garbage collects test resources

### Usage

```
jx-test gc
```

### Synopsis

Garbage collects test resources

### Examples

  jx-test gc

### Options

```
  -d, --duration duration   The maximum age of a Terraform resource before it is garbage collected (default 2h0m0s)
  -h, --help                help for gc
  -n, --ns string           the namespace to query the Terraform resources
  -l, --selector string     the selector to find the Terraform resources to remove (default "kind=jx-test")
```

### SEE ALSO

* [jx-test](jx-test)	 - Test commands

###### Auto generated by spf13/cobra on 15-Feb-2021