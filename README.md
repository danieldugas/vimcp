# vimcp - Batch copy files in vim

![vimcp](https://github.com/danieldugas/vimcp/raw/master/vimcp.gif "vimcp in action")

Similar to [vimv](https://github.com/thameera/vimv), but for copying instead of moving.

## Install

```
sudo cp ~/vimcp/vimcp /usr/bin/
sudo cp ~/vimcp/vimcpr /usr/bin/
```

## Usage

accepts cp command args, for example --verbose, -i, -u, etc...
```
vimcp --verbose
```
a vim session will open with the desired commands. Modify the commands as you desire, then save and exit.
If you do not save (`:w`), nothing gets executed.


## vimcpr

vimcpr is the same as vimcp, but crawls directories recursively to find *all* files below the current dir.
```
vimcpr --verbose
```

