# Generic

1. What is the main purpose of the intermediate certification authorities?

To find out the main purpose of an intermediate CA, you should first learn about Root CAs, Intermediate CAs, and the SSL Certificate Chain Trust.

Root CAs are primary CAs which typically don’t directly sign end entity/server certificates. They issue Root certificates which are usually pre-installed within all browsers, mobiles, and applications. The private key of these certificates is used to sign other subsequent certificates called intermediate certificates. Root CAs are usually kept "offline” and in a highly secure environment with stringently limited access.

Intermediates CAs are CAs that subordinate to the Root CA by one or more levels, being trusted by these to sign certificates on their behalf. The purpose of creating and using Intermediate CAs is primarily for security because if the intermediate private key is compromised, then the Root CA can revoke the intermediate certificate and create a new one with a new cryptographic key pair.

SSL Certificate Chain Trust is the list of SSL certificates, from the root certificate to the end entity/server certificate. For an SSL Certificate to be trusted, it must be issued by a trusted CAs which is included in the trusted CA list of the connecting device (browser, mobile, and application). Therefore, the connecting device will test the trustworthiness of each SSL Certificate in the Chain Trust until it matches the one issued by a trusted CA.

The Root-Intermediate CA structure is created by each major CA to protect against the disastrous effects of a root key compromise. If a root key is compromised, it would render the root and all subordinated certificates untrustworthy. For this reason, creating an Intermediate CA is a best practice to ensure a rigorous protection of the primary root key.



Big Data:

YARN/HDFS/MR:

YARN architecture and failure scenarios

Hadoop Distributed File System (HDFS) for storing large datasets, and run distributed computations over those datasets using MapReduce

Become familiar with Hadoop's data and I/O building blocks for compression, data integrity, serialization, and persistence

Discover common pitfalls and advanced features for writing real-world MapReduce programs

Hadoop: Definitive Guide(Book)

HDFS:

https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html

https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html

MapReduce and Failure Scenarios:

MapReduce Quick Read : https://data-flair.training/blogs/hadoop-mapreduce-tutorial/

HIVE:

Discover common pitfalls and advanced features for writing real-world MapReduce programs

Architecture and Execution plan

Optimisation Techniques

Troubleshooting

https://cwiki.apache.org/confluence/display/Hive/Design

https://cwiki.apache.org/confluence/display/Hive/HiveServer2+Overview

https://docs.cloudera.com/HDPDocuments/HDP2/HDP-2.6.5/bk_hive-performance-tuning/
https://docs.cloudera.com/HDPDocuments/HDP2/HDP-2.6.5/bk_hive-performance-tuning/content/ch_cost-based-optimizer.html

https://cwiki.apache.org/confluence/display/Hive/Vectorized+Query+Execution

Spark:

Spark Architecture Overview and job execution

Optimisation Techniques and Best Practices

Various types of Joins and how they impact the job

Troubleshooting

https://www.youtube.com/watch?v=_ArCesElWp8&t=2211s

https://mapr.com/blog/tips-and-best-practices-to-take-advantage-of-spark-2-x/

Spark application submission :

https://spark.apache.org/docs/latest/submitting-applications.html

Spark cluster mode overview

https://spark.apache.org/docs/latest/cluster-overview.html

https://medium.com/@goyalsaurabh66/spark-basics-rdds-stages-tasks-and-dag-8da0f52f0454

https://medium.com/@achilleus/https-medium-com-joins-in-apache-spark-part-1-dabbf3475690

https://medium.com/@achilleus/https-medium-com-joins-in-apache-spark-part-2-5b038bc7455b

Spark tuning :

https://spark.apache.org/docs/latest/tuning.html

https://spark.apache.org/docs/latest/sql-performance-tuning.html

https://blog.cloudera.com/how-to-tune-your-apache-spark-jobs-part-1/

https://blog.cloudera.com/how-to-tune-your-apache-spark-jobs-part-2/

HBase:

HBase Architecture and components overview

Write and Read Path

Optimisation

Troubleshooting

https://mapr.com/blog/in-depth-look-hbase-architecture/
https://blog.cloudera.com/apache-hbase-write-path/
https://hbase.apache.org/book.html

Networking -

TCP - http://www.tcpipguide.com/free/t_TCPIPArchitectureandtheTCPIPModel-2.htm

3 way handshake - https://support.microsoft.com/en-in/help/172983/explanation-of-the-three-way-handshake-via-tcp-ip

NAT - http://www.ciscopress.com/articles/article.asp?p=1725268

HTTP - http://www.windowsnetworking.com/articles-tutorials/network-protocols/Understanding-HTTP-Protocol-Part1.html

Basics/Fundamentals on Linux/Ubuntu/Solaris/Any other flavours

https://access.redhat.com/documentation/en/red-hat-enterprise-linux/

Memory management –

http://www.tldp.org/LDP/tlk/mm/memory.html

http://linux-training.be/sysadmin/ch18.html

http://www.linuxhowtos.org/System/Linux%20Memory%20Management.htm

File System management –

http://swift.siphos.be/linux_sea/linuxfs.html

https://www.ibm.com/developerworks/library/l-journaling-filesystems/index.html

https://docstore.mik.ua/orelly/linux/run/ch06_01.htm
