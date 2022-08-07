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

The options stand for:

[z]is to convert to gzip (required)

[c]Create. To create new archive (required)

[v] Verbose. To display information as the compression proceed (Not required)

[f]File. Tells tar that the next argument is the name of the tarball. (required)


To list the contents of newfolder.tar.gz

```
$ tar -tf newfolder.tar.gz
```
The options stand for 

[t]Test is to check the file intergrity (required)

[f]Tells tar that the next argument is the name of the tarball. (required)


To extract the contents of a file or folder 

```
$ tar -xvf newfolder.tar.gz
```

The options stand for

[x] extract (required)

[v]verbose. This makes tar give us feedback on its progress. (optional)

[f]Tells tar that the next argument is the name of the tarball. (required)


##Using Squashfs compression 
