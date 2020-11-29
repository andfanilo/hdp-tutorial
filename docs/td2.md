# TD2 - Simulating customer behavior analytics in ecommerce

!!! warning
    Are you curious? This is still in construction though :wink:

![](./images/apache-logs.png)

## Objectives

- [ ] Structuring Apache logs
- [ ] Ingesting Apache logs into HDFS in realtime with Flume
- [ ] Building a data dashboard with Zeppelin

## 1. Structuring Apache logs

Here is a line of Apache log:

```
164.29.239.18 - - [01/Aug/2014:11:48:59 -0400] "GET /department/apparel/products HTTP/1.1" 200 991 "-" "Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.153 Safari/537.36"
```

* Copy to HDFS
* Hive external table with regex Serde
* Zeppelin for some SQL queries

## 2. Generating logs with Python

* Copy gen_logs to VM
* Run Python simulation

## 3. Ingesting data in HDFS with Flume 

* Configure Flume
* Output in external Hive table

## 4. Dashboarding with Zeppelin

* TODO

## Conclusion