# PSM

Python Script Manager

A simple tool like `pipsi`, but in POSIX shell.

```
Usage: psm <command> [PARAMS...]

Commands:
    add <package>   Add script from <package>
    rm <package>    Remove scripts of <package>
    up [package]    Update <package> or all packages if <package> not given
    ls              List all installed packages
    root            Show root directory of PSM
    path <package>  Show path of a specific package
    exec <package> [subcommand...]
                    Run specific command in virtualenv of the package
    help            Show this message
```
