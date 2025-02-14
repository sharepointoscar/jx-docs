---
date: 2020-06-19T00:57:42Z
title: "jx get chat"
slug: jx_get_chat
url: /commands/jx_get_chat/
description: list of jx commands
---
## jx get chat

Display the current registered chat service URLs

### Synopsis

Display the chat server URLs.

```
jx get chat [flags]
```

### Examples

```
  # List all registered chat server URLs
  jx get chat
```

### Options

```
  -h, --help          help for chat
  -k, --kind string   Filters the chats by the kinds: slack, irc
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 19-Jun-2020
