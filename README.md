# test_bigdata
## Prerequistic

* hostname: master is hadoop master
* example
```
  sudo -i
  echo "111.111.111.111 master" > /etc/hosts
```

### Keyfile
* keyfile name:key_bigdata.pem

```
$ ls 
do.sh  hive_empdept.sh  mykey.pem
```
# install
```
git clone https://github.com/Finfra/testPrj.git
cd testPrj
scp ~/mykey.pem ./
. do.sh
```
# Result
```
~
~
OK
20	2518.75
10	2916.6666666666665
Time taken: 1.117 seconds, Fetched: 2 row(s)
OK
dept
emp
Time taken: 0.032 seconds, Fetched: 2 row(s)
```
