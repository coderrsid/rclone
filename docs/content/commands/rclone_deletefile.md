---
date: 2020-02-01T10:26:53Z
title: "rclone deletefile"
slug: rclone_deletefile
url: /commands/rclone_deletefile/
---
## rclone deletefile

Remove a single file from remote.

### Synopsis


Remove a single file from remote.  Unlike `delete` it cannot be used to
remove a directory and it doesn't obey include/exclude filters - if the specified file exists,
it will always be removed.


```
rclone deletefile remote:path [flags]
```

### Options

```
  -h, --help   help for deletefile
```

See the [global flags page](/flags/) for global options not listed here.

### SEE ALSO

* [rclone](/commands/rclone/)	 - Show help for rclone commands, flags and backends.

