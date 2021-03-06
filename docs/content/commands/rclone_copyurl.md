---
date: 2020-02-01T10:26:53Z
title: "rclone copyurl"
slug: rclone_copyurl
url: /commands/rclone_copyurl/
---
## rclone copyurl

Copy url content to dest.

### Synopsis


Download a URL's content and copy it to the destination without saving
it in temporary storage.

Setting --auto-filename will cause the file name to be retreived from
the from URL (after any redirections) and used in the destination
path.

Setting --stdout or making the output file name "-" will cause the
output to be written to standard output.


```
rclone copyurl https://example.com dest:path [flags]
```

### Options

```
  -a, --auto-filename   Get the file name from the URL and use it for destination file path
  -h, --help            help for copyurl
      --stdout          Write the output to stdout rather than a file
```

See the [global flags page](/flags/) for global options not listed here.

### SEE ALSO

* [rclone](/commands/rclone/)	 - Show help for rclone commands, flags and backends.

