# Linux Operations

**`export`**

Displays all environment variables. If you want to get details of a specific variable, use `echo $VARIABLE_NAME`.

Example:

```bash
$ export
AWS_HOME=/Users/sushilparajuli/.aws
LANG=en_US.UTF-8
LC_CTYPE=en_US.UTF-8
LESS=-R

$ echo $AWS_HOME
/Users/sushilparajuli/.aws
```

**`whatis`**

whatis shows description for user commands, system calls, library functions, and others in manual pages

```text
whatis something
```

Example:

```text
$ whatis bash
bash (1)             - GNU Bourne-Again SHell
```

**`whereis`**

**`whereis`** ~~__~~searches for executables, source files, and manual pages using a database built by system automatically.

```text
whereis name
```

Example:

```text
$ whereis php
/usr/bin/php
```

#### **`clear`**

Clears content on window.

