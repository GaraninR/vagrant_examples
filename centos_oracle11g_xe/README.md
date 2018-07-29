# centos_oracle11g_xe

Links for download:

1. Oracle 11g XE: http://www.oracle.com/technetwork/database/database-technologies/express-edition/downloads/index.html
2. Java Runtime: http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
3. Oracle SQLCL: http://www.oracle.com/technetwork/developer-tools/sqlcl/downloads/index.html

Directory structure:
-/centos_oracle11g_xe ---
--/jre-8u181-linux-x64.tar.gz
--/oracle-xe-11.2.0-1.0.x86_64.rpm
--/sqlcl-18.2.0.zip
--/Vagrantfile

Run Vagrant Box (into directory with Vagrantfile):
$ vagrant up --provider=virtualbox

Connect to CentOS Vagrant Box over SSH:
$ vagrant ssh