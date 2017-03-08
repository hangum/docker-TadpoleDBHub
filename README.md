Docker-Tadpole DB Hub
==
[![Join the chat at https://gitter.im/TadpoleDBHub](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/TadpoleDBHub?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Tadpole DB Hub(https://github.com/hangum/TadpoleForDBTools) is Unified infrastructure tool, various environment based interface for managing <b>Apache Hive, Apache Tajo, Amazon RDS, MySQL, MariaDB, Oracle, SQLite, MSSQL, PostgreSQL, CUBRID and MongoDB</b> databases.
It enables you to handle typical DB over the World Wide Web
![screenshot](https://sites.google.com/site/tadpolefordb/_/rsrc/1460305744502/home/TDB_main.jpg?height=309&width=400)

Original Source 
-
* https://hub.docker.com/r/library/tomcat/

Docker Hub 
- 
* https://hub.docker.com/r/hyunjongcho/tadpoledbhub/

Image build
-
* docker build -t hyunjongcho/tadpoledbhub:latest .

Image run
-
* docker run -it -p 32768:8080 hyunjongcho/tadpoledbhub:latest
* docker start tadpoledbhub

Docker push
-
* docker push hyunjongcho/tadpoledbhub:latest

Docker tag
- 
* 도커허브 계정(hyunjongcho/tadpoledbhub) 의 이름으로 tag되어 있어야 합니다. 
* docker tag 59556f5bbf7b hyunjongcho/tadpoledbhub:1.7.3

Tadpole DB Hub start
-
* http://{tomcat ip}:{tomcat port}

Download
-
* https://sourceforge.net/projects/tadpoledbhub/files/1.7.x/1.7.4/

License
-
* LGPL(Lesser General Public License)

Contacts
-
* Home : https://sites.google.com/site/tadpolefordb/
* Email: adi.tadpole@gmail.com
* google talk : hangum@gmail.com

Contributor
-
* hangum (hangum@gmail.com)

Donation
-
* Paypal(paypal.com) : hangum@gmail.com
* Donor(https://github.com/hangum/TadpoleForDBTools/wiki/Donor-List)
