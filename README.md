# Snowflake-Linux-Build

***Building latest Snowflake on Linux***

```
apt update
apt upgrade
apt install build-essential golang git
git clone https://git.torproject.org/pluggable-transports/snowflake.git
cd snowflake/proxy
go build
./proxy
```
