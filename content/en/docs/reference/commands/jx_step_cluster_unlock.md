---
date: 2020-06-19T00:57:42Z
title: "jx step cluster unlock"
slug: jx_step_cluster_unlock
url: /commands/jx_step_cluster_unlock/
description: list of jx commands
---
## jx step cluster unlock

Unlocks the given cluster name so it joins the pool of test clusters again

### Synopsis

Unlocks the given cluster name so it joins the pool of test clusters again.

```
jx step cluster unlock [flags]
```

### Examples

```
  
```

### Options

```
      --fake                 Use the fake clusters client
      --gke-project string   The GKE project name
      --gke-region string    The GKE project name
  -h, --help                 help for unlock
  -l, --label string         The label name for the lock (default "locked")
  -n, --name string          The name of the cluster to unlock
      --test-label string    The label name for the test (default "test")
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx step cluster](/commands/jx_step_cluster/)	 - cluster [kind]

###### Auto generated by spf13/cobra on 19-Jun-2020
