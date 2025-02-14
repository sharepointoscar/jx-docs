---
date: 2020-06-19T00:57:42Z
title: "jx create project"
slug: jx_create_project
url: /commands/jx_create_project/
description: list of jx commands
---
## jx create project

Create a new Project by importing code, using a Quickstart or custom wizard for Spring

### Synopsis

Create a new Project by importing code, using a Quickstart or custom wizard for Spring.
  
See Also: 

  * jx create quickstart : https://jenkins-x.io/commands/jx_create_quickstart  
  * jx create spring : https://jenkins-x.io/commands/jx_create_spring  
  * jx import : https://jenkins-x.io/commands/jx_import

```
jx create project [flags]
```

### Examples

```
  # Create a project
  jx create project
```

### Options

```
  -h, --help   help for project
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx create](/commands/jx_create/)	 - Create a new resource

###### Auto generated by spf13/cobra on 19-Jun-2020
