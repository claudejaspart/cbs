# LINUX COMMANDS

### Processes

* View user processes
```
  ps
```

* View all processes
```
  ps aux
```

* Force kill a process (possible zombies)
```
  kill -9 pid
```

* Graceful kill a process
```
  kill -15 pid
```

* Run a command in the background
```
  command &
```

### Filesystem

* Search for a file

``` 
  find dirname -name foobar.txt
```

* Type of a file

``` 
  file foobar.txt
```

### Administration

* List of available sudo commands 

```
  sudo -l
```

### Remote copy / download

* Download a file in a given directory
```
  wget -P targetdir url
```

* Resume download
```
  wget -c url
```

* Secure copy
```
  scp filename user@remote_host:/targetpath/
```

### Command syntax


* Execute command2 if command1 is successful
'''
  command1 && command2
'''






