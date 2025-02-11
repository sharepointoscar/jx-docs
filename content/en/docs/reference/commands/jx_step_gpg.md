---
date: 2020-06-19T00:57:42Z
title: "jx step gpg"
slug: jx_step_gpg
url: /commands/jx_step_gpg/
description: list of jx commands
---
## jx step gpg

Creates the GPG credentials file for GPG signing releases

### Synopsis

This pipeline step generates GPG credentials files from the jenkins-release-gpg secret

```
jx step gpg credentials [flags]
```

### Examples

```
  # generate the GPG credentials file in the canonical location
  jx step gpg credentials
  
  # generate the git credentials to a output file
  jx step gpg credentials -o /tmp/mycreds
```

### Options

```
  -h, --help            help for gpg
  -o, --output string   The output directory
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx step](/commands/jx_step/)	 - pipeline steps

###### Auto generated by spf13/cobra on 19-Jun-2020
