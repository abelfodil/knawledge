---
id: LRch2CMabBB4il6yEazmv
title: Filesystem
desc: ''
updated: 1611589251808
created: 1611439928961
---

## Rezising

- [Shrinking a root partition without liveboot](https://unix.stackexchange.com/a/227318)

- [Extending a LUKS encrypted partition](https://unix.stackexchange.com/a/322631)

## Fixing permissions

### Commands
- Recursively give directories read&execute privileges:
  
    `find . -type d -exec chmod 755 {} +`

- Recursively give files read privileges:

    `find . -type f -exec chmod 644 {} +`

### Sources

- https://superuser.com/a/91938


## inotify

- [Node.js: what is ENOSPC error and how to solve?](https://stackoverflow.com/a/32600959)

