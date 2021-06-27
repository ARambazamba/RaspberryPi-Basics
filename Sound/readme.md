# DNLA Media Server

Install minidln

```
sudo apt-get install minidlna
```

Make sure you have no whitespaces in folder names:

```
find -name "* *" -print0 | sort -rz | \
  while read -d $'\0' f; do mv -v "$f" "$(dirname "$f")/$(basename "${f// /_}")"; done
```