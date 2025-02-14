---
date: 2020-06-19T00:57:42Z
title: "jx shell"
slug: jx_shell
url: /commands/jx_shell/
description: list of jx commands
---
## jx shell

Create a sub shell so that changes to the Kubernetes context, namespace or environment remain local to the shell

### Synopsis

Create a sub shell so that changes to the Kubernetes context, namespace or environment remain local to the shell.

```
jx shell [flags]
```

### Examples

```
  # create a new shell where the context changes are local to the shell only
  jx shell
  
  # create a new shell using a specific named context
  jx shell prod-cluster
  
  # ends the current shell and returns to the previous Kubernetes context
  exit
```

### Options

```
  -f, --filter string   Filter the list of contexts to switch between using the given text
  -h, --help            help for shell
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 19-Jun-2020
