---
date: 2020-06-19T00:57:42Z
title: "jx get storage"
slug: jx_get_storage
url: /commands/jx_get_storage/
description: list of jx commands
---
## jx get storage

Display the storage configuration for different classifications

### Synopsis

Display the storage configuration for different classifications.
  
Currently Jenkins X supports storing files into a branch of a git repository or in cloud blob storage like S3, GCS, Azure blobs etc. 

When using Cloud Storage we use URLs like 's3://nameOfBucket' on AWS, 'gs://anotherBucket' on GCP or on Azure 'azblob://thatBucket' 

See Also: 

  * jx step stash : https://jenkins-x.io/commands/jx_step_stash  
  * jx edit storage : https://jenkins-x.io/commands/jx_edit_storage

```
jx get storage [flags]
```

### Examples

```
  # List the storage configurations for different classifications for the current team
  jx get storage
```

### Options

```
  -h, --help            help for storage
  -o, --output string   The output format such as 'yaml'
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warning, info, debug, trace
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 19-Jun-2020
