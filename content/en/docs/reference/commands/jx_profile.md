---
date: 2020-06-19T00:57:42Z
title: "jx profile"
slug: jx_profile
url: /commands/jx_profile/
description: list of jx commands
---
## jx profile

Set your jx profile

### Synopsis

Sets the profile for the jx install

```
jx profile <type> [flags]
```

### Examples

```
  # Sets the profile for the jx install to cloudbees
  jx profile cloudbees
  
  # Set the profile for the jx install to open source
  jx profile oss
```

### Options

```
  -h, --help   help for profile
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 19-Jun-2020
