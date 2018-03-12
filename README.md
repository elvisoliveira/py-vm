# py-vm
Simple CLI wrapper for VirtualBox.

Usage:
```
vm list
vm start <name>
vm stop <name>
vm rename <src> <dst>
vm clone <src> <dst>
vm export <name> <file.ova>
vm import <name> <file.ova>
```

For proper bash completion add to your ~/.bashrc:
```
complete -W 'list start stop delete rename clone export import' vm
```

Reddit discussion: [https://redd.it/5ab2th](https://redd.it/5ab2th).
