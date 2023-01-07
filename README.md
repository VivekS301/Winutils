# winutils
winutils.exe hadoop.dll and hdfs.dll binaries for hadoop on windows

I've been using https://github.com/cdarlint/winutils but it stops to update
So I tried to compile myself and push binaries here for you all



## how to use

place a copy of hadoop-ver folder on your local drive
set environment vars:
```
HADOOP_HOME=<your local hadoop-ver folder>
PATH=%PATH%;%HADOOP_HOME%\bin
```
then you'll pass the "no native library" and "access0" error

Credit: https://github.com/cdarlint/winutils till versions 3.2.2
and other versions https://github.com/kontext-tech/winutils
