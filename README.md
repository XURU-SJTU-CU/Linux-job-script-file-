# Linux-job-script-file
Sometimes shell script files edited on Windows cannot work in Linux system, partly because of the code is not in unix format, the method of changing format is shown as below: 
对于windows上编辑过的shell script文件在linux上提交报错的问题，一部分原因是在windows上的字符格式不适用于linux，转换过程中出了问题。所以在windows上编辑过的shell script作如下的格式转换就可以了

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
