---
date: 2020-06-19T00:57:42Z
title: "jx controller"
slug: jx_controller
url: /commands/jx_controller/
description: list of jx commands
---
## jx controller

Runs a controller

### Synopsis

Runs a controller

```
jx controller <command> [flags]
```

### Examples

```
  
```

### Options

```
  -h, --help   help for controller
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X
* [jx controller backup](/commands/jx_controller_backup/)	 - Runs the backup controller
* [jx controller build](/commands/jx_controller_build/)	 - Runs the build controller
* [jx controller buildnumbers](/commands/jx_controller_buildnumbers/)	 - Runs the service to generate build numbers.
* [jx controller commitstatus](/commands/jx_controller_commitstatus/)	 - Updates commit status
* [jx controller environment](/commands/jx_controller_environment/)	 - A controller which takes a webhook and updates the environment via GitOps for remote clusters
* [jx controller pipelinerunner](/commands/jx_controller_pipelinerunner/)	 - Runs the service to generate Tekton PipelineRun resources from source code webhooks such as from Prow
* [jx controller role](/commands/jx_controller_role/)	 - Controller which mirrors Role & EnvironmentRoleBinding resources to Roles and RoleBindings in all matching Environment namespaces
* [jx controller team](/commands/jx_controller_team/)	 - Runs the team controller

###### Auto generated by spf13/cobra on 19-Jun-2020
