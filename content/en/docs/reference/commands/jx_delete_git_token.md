---
date: 2020-06-19T00:57:42Z
title: "jx delete git token"
slug: jx_delete_git_token
url: /commands/jx_delete_git_token/
description: list of jx commands
---
## jx delete git token

Deletes one or more API tokens for a user on a Git server

### Synopsis

Deletes one or more git tokens from your local settings

```
jx delete git token [flags]
```

### Examples

```
  # Deletes a Git user token
  jx delete git token -n local myusername
```

### Options

```
  -h, --help          help for token
  -n, --name string   The name of the Git server to add a user
  -u, --url string    The URL of the Git server to add a user
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx delete git](/commands/jx_delete_git/)	 - Deletes one or more Git resources

###### Auto generated by spf13/cobra on 19-Jun-2020
