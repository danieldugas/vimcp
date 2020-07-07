# vimcp

![vimcp](https://github.com/danieldugas/vimcp/raw/master/vimcp.gif "vimcp in action")

Copy files in batch using vim.
Similar to [vimv](https://github.com/thameera/vimv), but for copying.

## Install

```
sudo ln -s -i ~/vimcp/vimcp /usr/bin/
sudo ln -s -i ~/vimcp/vimcpr /usr/bin/
```

## Usage

accepts cp command args, for example --verbose, -i, -u, etc...
```
vimcp --verbose
```

vimcpr is the same as vimcp, but crawls directories recursively to find *all* files starting from the current dir.
```
vimcpr --verbose
```

