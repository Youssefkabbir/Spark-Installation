# How to install Apache Spark (version 3.5.0  ) on Ubuntu 23.04
```
$ neofetch
```
![Ubunut](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/e8dc61a1-2184-48a8-9aad-cba406d2790c)

Apache Spark is a unified analytics engine for large-scale data processing. It provides high-level APIs in Java, Scala, Python, and R, and an optimized engine that supports general execution graphs. It also supports a rich set of higher-level tools including Spark SQL for SQL and structured data processing, pandas API on Spark for pandas workloads, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for incremental computation and stream processing.I love supporting the **[Reference](https://spark.apache.org/docs/3.5.0/)**
## Step 1: Update the System
Before installing any software on Ubuntu, update the system.
```
$ sudo apt-get update 
```
![Img1](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/37e5a356-3cdd-43e4-92c7-99192683ffd4)

Step 2: Install Java 
To run Apache Spark on Ubuntu 23.04, we need to install Java  by running the following command:
```
$ sudo apt install openjdk-8-jdk -y
```
in my case, I have installed the 8 version of Java  because I want to install  Cassandra and it's  the OpenJDK-8-jdk  or OpenJDK-11-jdk.
 I already  installed Java, that's why it shows me  this 

![java](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/e8fdb78b-f9fb-4f73-8dd0-2f83503f2f75)

# How to Uninstall Apache Spark on Ubuntu 23.04?
![uninstall spark](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/265a9e06-e653-44bd-be76-060341d9bd30)
Also, remove the environment variable you set earlier:

```
$  vim ~/.bashrc
```
![variables](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/29c41583-239c-4011-9096-d40fbb165e68)
Press *ENTER*, you will get this result:
![var2](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/854ee854-5cde-4c33-a085-3b802f2c5acc)
Press *e* or *E* 
![RemovefromEnvirment](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/12b6d076-c3c2-4b4b-8e51-22f603bdafaf)
Remove this 3 lines
w![r2](https://github.com/Youssefkabbir/Spark-Installation/assets/59072693/4818565e-68e9-413d-a334-eb2d43915be2)







 

