

## BigData commands


Added few documents in above directory and those are most used commands in Hadoop. If you follow/practice those, it would give good idea about how to use commands and play around in hadoop cluster(s).


in old tradition, we used to have commands like

	hadoop dfs -mkdir /DATA01
	hadoop dfs -ls


but these commands (syntax starting with hadoop) are deprecated in newer versions and advised to use hdfs instead of hadoop.

Examples :

	hdfs dfs -mkdir /DATA01
	hdfs dfs -ls

![Deprecated syntax](https://github.com/psanthoshkumar/BigDataLearning/blob/master/pictures/hadoop_commands_are_deprecated.png) 
