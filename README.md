# Tools_mistie

### №1 sshcrack

Сборка проекта
```
➜make // собираем проект
➜make clean // очистить проект от файлов *.o *.out и тд
```


```
➜./sshcrack
    Usage: ./sshcrack [OPTIONS]
    -c [payload]	Execute payload on remote server once logged in
    -h		        Display this help
    -l [threads]	Limit threads to given number. Default: 10
    -p [port]	        Specify remote port
    -P [password]	Use single password attempt
    -t [target]	    Attempt connections to this server
    -u [user]	    Attempt connection using this username
    -v		-v (Show attempts) -vv (Show debugging)
    -w [wordlist]	Use this wordlist. Defaults to wordlist.txt
  
➜./sshcrack -l 15 127.0.0.1 -v
┌──────────────────────────────────────────────────────────────────────────┐
│        #--------------------------------------------------------#        │
│        #   __        __   _ _                                   #        │
│        #   \ \      / /__| | | ___  ___  _ ___ ___  ___         #        │
│        #    \ \    / / _ \ | |/ __|/ _ \| _  _   \/ _ \         #        │
│        #     \ \/\/ /  __/ | | (__  (_) | | | | | |  __/        #        │
│        #      \_/\_/\____|_|_|\___|\___/|_| |_| |_|\___|        #        │
│        #                                                        #        │
│        #--------------------------------------------------------#        │
└──────────────────────────────────────────────────────────────────────────┘
[*] Read 30 passwords from file.
[*] Starting task manager
[*] Spawning 15 threads
[*] Starting attack on root@127.0.0.1:22
[*] Cleaning up child processes.
[!] No password matches found.
```
Tool_network_and.....
