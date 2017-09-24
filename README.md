# CheatSheet
A cheat sheet for Linux programming

### Rsync
```bash
$ rsync -vazh [from] [to]
```
-v : verbose  
-a : archive mode  
-z : compress file data  
-h : human-readable 

### tar.xz
##### zip  
```bash
$ tar -cvJf [to.tar.xz] [from]
```
-c : create a new archive  
-v : verbosely list files processed  
-J : --xz  
-f : use archive file or device ARCHIVE  
##### unzip  
```bash
$ tar -xf [from.tar.xz]
```
