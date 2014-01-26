scribe
======

Give each document you're working on its own directory, and keep a revision history. For use with [revcontrol](https://github.com/Antithesisx/Revcontrol.git).

Revcontrol saves a copy for each revision in the working directory. If you have a lot of files in the directory, it's going to get really cluttered up. Scribe creates a directory each of your documents, and the revision histories will be kept in their respective directories.

### Dependencies
- [revcontrol](https://github.com/Antithesisx/Revcontrol.git)

(It can be used without revcontrol, but there's not much of a point to it.)

### Installation
- Resolve the dependencies;
- copy scribe to your PATH and make sure it's executable:

```
sudo cp scribe /usr/bin/
sudo chmod +x /usr/bin/scribe
```

### Usage
`scribe <filename>`
