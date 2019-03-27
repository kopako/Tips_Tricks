If you need to set up java_home.
```
export JAVA_HOME=$(readlink -f /usr/bin/java | sed "s:bin/java::")
```

install docker 
```
sudo yum update -y
sudo yum install docker -y
sudo service docker start
sudo usermod -a -G docker ec2-user
```
