to start docker compose up -d



# Problems

```
sysctl -w vm.max_map_count=262144 
or 
nano /etc/sysctl.con and append vm.max_map_count=262144

on apmserver error
chmod go-w apmserver/config/apm-server.yml
```

