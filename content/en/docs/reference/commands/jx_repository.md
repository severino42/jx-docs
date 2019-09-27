---
date: 2019-09-27T11:47:19Z
title: "jx repository"
slug: jx_repository
url: /commands/jx_repository/
---
## jx repository

Opens the web page for the current Git repository in a browser

### Synopsis

Opens the web page for the current Git repository in a browser 

You can use the '--url' argument to just display the URL without opening it

```
jx repository [flags]
```

### Examples

```
  # Open the Git repository in a browser
  jx repo
  
  # Print the URL of the Git repository
  jx repo -u
  
  # Use the git URL in a script/pipeline
  export URL="$(jx repo -q -b)"
```

### Options

```
  -h, --help    help for repository
  -q, --quiet   Quiet mode just displays the git URL only for use in scripts
  -u, --url     Only displays and the URL and does not open the browser
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 27-Sep-2019