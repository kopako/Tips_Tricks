If you need to set up java_home.
```
export JAVA_HOME=$(readlink -f /usr/bin/java | sed "s:bin/java::")
```
