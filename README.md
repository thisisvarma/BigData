[home](https://github.com/psanthoshkumar/BigDataLearning/wiki)

**Get starting learning Big Data**

#Disclaimer : this notes is taken from internet, surfing. Hence, using this notes or programs is not advisable to use in any production Environments. 

### In total training session has 7 chapters for now! Below are titles for each chapter

1. [Introduction to Big Data](https://github.com/psanthoshkumar/BigDataLearning/wiki/1.-Introduction-to-Big-Data)

2. [Hadoop Architecture](https://github.com/psanthoshkumar/BigDataLearning/wiki/2.-Hadoop-Architecture)

3. [First Week Assignment](https://github.com/psanthoshkumar/BigDataLearning/wiki/3.-First-Week-Assignment)

4. [HDFS commands](https://github.com/psanthoshkumar/BigDataLearning/wiki/4.-HDFS-commands)

5. [First Map Reduce program](https://github.com/psanthoshkumar/BigDataLearning/wiki/5.-First-Map-Reduce-program)

6. [Map Reduce practical](https://github.com/psanthoshkumar/BigDataLearning/wiki/6.-Map-Reduce-practical)

7. [Map Reduce using Maven](https://github.com/psanthoshkumar/BigDataLearning/wiki/7.-Map-Reduce-using-Maven)

# 1.Introduction to Big Data

This chapter is missing for now

# 2.Hadoop Architecture

Some part of this chapter also missed

## Hadoop node installation

### Pre-Requests are:

On test or Lab Environment, we need to get ready our laptop or machine. then after,

* Install virtual platform - Example : Vmware Workstation, virtalbox
* Create VM and install Guest Operating systems - Example : CentOS6,7 or Ubuntu
* Install Java
* Install Hadoop 2.7.x

In our scenario, I am going to use vagrant on top of virtualbox to control VBs and this notes is not going to cover how to install virtual box and vagrant. It is pretty easy and follow YouTube. 

## steps to standup Hadoop Single node are given below

Once we finished installing virtualbox and vagrant, follow below steps

* Go Environments and copy VagrantFile to you local machine
* Open Terminal(In my case, I am using ubuntu, but, use cmd for Windows machine) and navigate to VagrantFile path
* run "vagrant up" command
* do "vagrant ssh"

In ideal conditions, we should be able to login to ubuntu OS which has all packages what we need to continue with our training

### Note : vagrant box may change/remove/update from vagrant cloud storage. At this point of time, i have below features

	Single node Hadoop cluster on Ubuntu/Xenial64

	Hadoop-2.7.4
	Hive-1.2.2 on Postgresql
	Spark-2.1.1
	Git
	Postgresql-9.5
	Anaconda2-5.0.1
	Node-8.9.0





