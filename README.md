# How to use gzip  in linux TUI(Text user interface)
On linux gzip is used to compress single file or multiple files in a folder.
Here is the command to compress a single file using gzip


And here is the command used to compress a folder:
```
$ tar -zcvf outputFileName folderToCompress

```

Example to gzip a folder named “newfolder”, and also all the files within that folder, into a single compressed file

```
$ tar -zcvf newfolder.tar.gz newrfolder/
```

To list the contents of newfolder.tar.gz

```
$ tar -tf newrelic.tar.gz
```
