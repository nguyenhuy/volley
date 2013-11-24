volley
======
Add Gradle task to build source jar and instruction to build jar file. This is a mirror of https://android.googlesource.com/platform/frameworks/volley/

Build jar:
==========
```
$ android update project -p .
$ ant jar
```
Reference: https://gist.github.com/mediavrog/6302510

Build source jar:
=================
```
$ gradle sourceJar
```
