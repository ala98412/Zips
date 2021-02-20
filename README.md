# Zips
Compress / Extract six kinds of compression software formats easily

```
usage: Zip/Unzip [-h] [-zip {targz,tar,gz,zip,bz2,xz} | -uzip] file

Compress / Extract six kinds of compression software formats easily.

positional arguments:
  file

optional arguments:
  -h, --help            show this help message and exit
  -zip {targz,tar,gz,zip,bz2,xz}
                        Zip file or directory
  -uzip

Contact author: ala98412@gmail.com
```

# Extract file
```
python3 -m Zips -uzip filename
```

# Compress file or directory
```
python3 -m Zips -zip [formats] file/dirname
```
targz : .tar.gz  
tar : .tar  
gz : .gz  
zip : .zip  
bz2 : .bz2  
xz : .xz  
