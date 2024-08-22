# Linux-job-script-file
Sometimes shell script files edited on Windows cannot work in Linux system, partly because of the code is not in unix format, the method of changing format is shown as below: 


Using vi to open any shell script in Linux system:
```
vi Sample.sh
```
In the editing page, type in the following command:
```
:set fileformat=unix
```
Then press Enter key,
```
:wq
```
save the setting. Then you should be able to get a file in unix format.
