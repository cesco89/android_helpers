Android Helpers
===========

This repo contains some useful classes to retrieve data from files, or apply values as root users.

From AOKP repository ([AOKP] [1])
-----

* AbstractAsyncSuCMDProcessor.java
* ChildProcess.java
* CMDProcessor.java
* Helpers.java

From me ( i will add some things in future)
-----

* Extra.java


Explanation and how to:
===========

Read file content and return a String (ReadFileContent):
-----
```java
	File file = new File("/sys/devices/system/cpu/cpu0/cpufreq/scaling_available_frequencies")
	String content = ReadFileContent(file);
```

Check if File exists, returns boolean :
-----

```java
	File file = new File("/sys/devices/system/cpu/cpu0/cpufreq/scaling_available_frequencies")
	boolean fileCheck = CheckIFileExists(file)
```

Split String and return a String-array :
-----

```java
	File file = new File("/sys/devices/system/cpu/cpu0/cpufreq/scaling_available_frequencies")
	String content = ReadFileContent(file);
	String[] splittedContent = StringSplitter(content, " " );	

```
Split String that contains spaces and a value inside brackets (returns a String-array):
-----

```java
	File file = new File("/sys/block/mmcblk0/queue/scheduler"); 
	String InsideBrackets = IsInsideBrackets(file, "[", "]");

```


AOKP Uils:
===========

See the description inside every class, it's quite simple ;)

[1] https://github.com/AOKP

