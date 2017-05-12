<html>
<h3>Add the first line of the server's log</h3>
<pre>
2017-05-12 02:18:37,286 INFO main:com.cloudera.server.cmf.Main: Starting SCM Server. JVM Args: [-Dlog4j.configuration=file:/etc/cloudera-scm-server/log4j.properties, -Dfile.encoding=UTF-8, -Dcmf.root.logger=INFO,LOGFILE, -Dcmf.log.dir=/var/log/cloudera-scm-server, -Dcmf.log.file=cloudera-scm-server.log, -Dcmf.jetty.threshhold=WARN, -Dcmf.schema.dir=/usr/share/cmf/schema, -Djava.awt.headless=true, -Djava.net.preferIPv4Stack=true, -Dpython.home=/usr/share/cmf/python, -XX:+UseConcMarkSweepGC, -XX:+UseParNewGC, -XX:+HeapDumpOnOutOfMemoryError, -Xmx2G, -XX:MaxPermSize=256m, -XX:+HeapDumpOnOutOfMemoryError, -XX:HeapDumpPath=/tmp, -XX:OnOutOfMemoryError=kill -9 %p], Args: [], Version: 5.11.0 (#101 built by jenkins on 20170412-1249 git: 70cb1442626406432a6e7af5bdf206a384ca3f98)
</pre>
<h3>The log record that contains the phrase "Started Jetty server"</h3>
<pre>
2017-05-12 02:20:11,755 INFO WebServerImpl:com.cloudera.server.cmf.WebServerImpl: Started Jetty server.
</pre>
<h3>The contents of the db.properties file</h3>
<pre>
# Auto-generated by scm_prepare_database.sh on 2017年 05月 12日 星期五 02:17:19 UTC
#
# For information describing how to configure the Cloudera Manager Server
# to connect to databases, see the "Cloudera Manager Installation Guide."
#
com.cloudera.cmf.db.type=mysql
com.cloudera.cmf.db.host=p1
com.cloudera.cmf.db.name=scm
com.cloudera.cmf.db.user=scm
com.cloudera.cmf.db.setupType=EXTERNAL
com.cloudera.cmf.db.password=scm_passwd
</pre>
</html>