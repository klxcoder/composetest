# Docker compose quickstart

https://docs.docker.com/compose/gettingstarted/

# docker compose up

```bash
docker compose up
```

# docker image ls

```bash
(base) ┌──(klx㉿kali)-[~/composetest]
└─$ docker image ls  
REPOSITORY                           TAG            IMAGE ID       CREATED         SIZE
composetest-web                      latest         a7a922c03828   2 minutes ago   243MB
redis                                alpine         8f5c54441eb9   7 weeks ago      41.4MB

(base) ┌──(klx㉿kali)-[~/composetest]
└─$ 
```

# docker compose ls

```bash
(base) ┌──(klx㉿kali)-[~/composetest]
└─$ docker compose ls
NAME                STATUS              CONFIG FILES
composetest         running(2)          /home/klx/composetest/compose.yaml

(base) ┌──(klx㉿kali)-[~/composetest]
└─$ 
```

# docker compose down

```bash
(base) ┌──(klx㉿kali)-[~/composetest]
└─$ docker compose down 
[+] Running 3/3
 ✔ Container composetest-web-1    Removed                                                                                                                                                                     0.3s 
 ✔ Container composetest-redis-1  Removed                                                                                                                                                                     0.2s 
 ✔ Network composetest_default    Removed                                                                                                                                                                     0.4s 
                                                                                                                                                                                                                   
(base) ┌──(klx㉿kali)-[~/composetest]
└─$ 
```