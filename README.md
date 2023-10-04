## du -h (disk usage) option will print file size in human readable format (e.g., 1K,234M,2G).
* Change into the directory where the file is located
### Type du -h (file name)
      du -h test
output 

      8.0K    test
## all the files under the current directory, you can use this command:
      du -h *
output 
 
    16K     tes1
    8.0K    test
    28K     test2
## This is the most efficient way to get the size of  a directory in Linux
      du -h /var/opt/backup/
output

      1.2G    /var/opt/backup/
