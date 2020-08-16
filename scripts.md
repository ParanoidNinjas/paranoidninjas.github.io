---
title: ParanoidNinjas
---

```bash
for i in `seq 4000 100000`; do echo `echo $i | sudo ./SQL_Check | egrep "Choice" -A1 | tr -d '\n'`; done 2> /dev/null | grep -v Invalid
```


```bash
for i in `seq 15235712 17332960`; do dd if=../N777779.mp4 skip=$i bs=1 of=foo; if [[ `md5sum foo | awk '{print $1}'` == "5e1f4d6fc1557234fbfdb69bf0f31a29" ]]; then break; fi; done
```
