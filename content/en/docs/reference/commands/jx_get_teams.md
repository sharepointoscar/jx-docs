---
date: 2020-06-19T00:57:42Z
title: "jx get teams"
slug: jx_get_teams
url: /commands/jx_get_teams/
description: list of jx commands
---
## jx get teams

Display the Team or Teams the current user is a member of

### Synopsis

Display the Team or Teams a user is a member of.

```
jx get teams [flags]
```

### Examples

```
  # List the provisioned team or teams the current user is a member of
  jx get team
  
  # List the pending Teams which are not yet provisioned and available for use
  jx get team -p
```

### Options

```
  -h, --help            help for teams
  -o, --output string   The output format such as 'yaml'
  -p, --pending         Display only pending Teams which are not yet provisioned yet
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 19-Jun-2020
