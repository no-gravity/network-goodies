# Network Goodies 🌐 

## Monitor DNS queries
```
tcpdump -l port 53 2>/dev/null | grep --line-buffered ' A? '
```
