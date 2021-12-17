# Idea distribution to download through proxy with file size limit

File splitted by
```
split -b 5m ideaIU-2021.3.tar.gz ideaIU-2021.3.tar.gz.part-
```

Use following command to join files back to one
```
cat ideaIU-2021.3.tar.gz.part-* > ideaIU-2021.3.tar.gz
```
