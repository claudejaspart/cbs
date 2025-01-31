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

### Networking

* Show ip address
```
  ip addr show
```


### Redirections

* Redirect all 
```
  &>
```

* Redirect errors to black hole
```
  2&> /dev/null
```

* Output of command 1 as input of command 2
```
 cmd1 | xargs cmd2
```

### Misc 


* Execute command2 if command1 is successful
```
  command1 && command2
```

# System date
```
  date
```







