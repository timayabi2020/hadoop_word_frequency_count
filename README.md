# hadoop_word_frequency_count
#Run jar file from hadoop/sbin path if on windows platform
hadoop.cmd jar /dist/countworddemo.jar /test/dataexample /r_output
#Print the output
hadoop.cmd fs -cat /r_output/part-00000
