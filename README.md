# pset
Bash, OS X: pSet - a CLI, help you manage your OSX network settings.



[<img width=589.5 height=412 src="https://asciinema.org/a/bpg5gngmuzgqr9dcu6xrtoiqw.png" />](https://asciinema.org/a/bpg5gngmuzgqr9dcu6xrtoiqw)

```
usage: sudo pset -l
       sudo pset -s
       sudo pset -e <all|web|socks>
       sudo pset -d <all|web|socks>

pSet - a CLI, help you manage your OSX network settings. <http://youdar.net>

options:

  -d disable proxy
    all   disable all
    web   disable web proxy
    socks disable socks proxy

  -e enable proxy
    all   enable all
    web   enable web proxy
    socks enable socks proxy

  -h show this help

  -l list proxies
  
  -s set all proxy (web + socks)

EXAMPLES:
    sudo pset -s
    sudo pset -l
    sudo pset -e all
    sudo pset -e web
    sudo pset -e socks
    sudo pset -d all
    sudo pset -d web
    sudo pset -d socks

pSet v0.1
```

#### Recommended:

- [Proxy settings OSX: OS X: scripts to set the proxy configuration for mvn, git, and curl](https://github.com/kontrafiktion/proxy-settings-osx)
