# aws-cli-aux
AWS CLI Auxiliary tools


* Download files from GitHub

```
$ git clone https://github.com/yoheia/aws-cli-aux.git
$ chmod u+x aws-cli-aux/bin/*
```

* Add the following line to ~/.bash_profile 

```
export PATH=$PATH:~/Documents/src/github/aws-cli-aux/bin
```
 
 * Load ~/.bash_profile
 
 ```
 $ source ~/.bash_profile
 ```
 
* How to use

```
$ ec2ls
------------------------------------------------------------------------------
|                              DescribeInstances                             |
+---------------+-----------------------+-------+----------------+-----------+
|   GlobalIP    |      InstanceId       | Name  |   PrivateIp    |   State   |
+---------------+-----------------------+-------+----------------+-----------+
|  13.***.***.60|  i-i-049***********b89  |  None |  172.**.**.228 |  running  |
+---------------+-----------------------+-------+----------------+-----------+
```


