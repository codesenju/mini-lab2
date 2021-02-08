# mini-lab2
## How to run:
```bash
docker run --name lab-1 --net devops --restart always -h lab-1 -v C:\Temp\Docker\lab-4\opt:/opt -v C:\Temp\Docker\lab-4\etc\systemd\system:/etc/systemd/system -p 8280-8281:8280-8281  -ti -d mini-lab2/centos:7
bck-i-search: lab-4
```
