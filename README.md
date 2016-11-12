# showpac
-------
## 1. Description

Only usable on Arch Linux.   
This shell script displays packages in your system.

## 2. Usage

```shell
./showpac
```

Displays packages not in groups base and base-devel

```shell
./showpac --description
./showpac -D
```

Displays packages not in groups base and base-devel with description

```shell
./showpac --all
./showpac -A
```

Display all packages in your system

## 3. How it works

It uses pacman to retrieve your packages installed and awk to filter them.
