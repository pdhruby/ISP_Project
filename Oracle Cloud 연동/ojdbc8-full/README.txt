======================================================
Oracle Free Use Terms and Conditions (FUTC) License 
======================================================
https://www.oracle.com/downloads/licenses/oracle-free-license.html
===================================================================

ojdbc8-full.tar.gz - JDBC Thin Driver and Companion JARS
========================================================
This TAR archive (ojdbc8-full.tar.gz) contains the 19.15.0.0.1 release of the Oracle JDBC Thin driver(ojdbc8.jar), the Universal Connection Pool (ucp.jar) and other companion JARs grouped by category. 

(1) ojdbc8.jar (4,473,793 bytes) - 
(SHA1 Checksum: 9bf041bd970497c57aa0b120f4527bc321a73e5f)
Oracle JDBC Driver compatible with JDK8, JDK9, and JDK11;
(2) ucp.jar (1,690,767 bytes) - (SHA1 Checksum: 9edbc163df3c5ab4c82819450a2a5c374237b912)
Universal Connection Pool classes for use with JDK8, JDK9, and JDK11 -- for performance, scalability, high availability, sharded and multitenant databases.
(3) ojdbc.policy (11,515 bytes) - Sample security policy file for Oracle Database JDBC drivers

======================
Security Related JARs
======================
Java applications require some additional jars to use Oracle Wallets. 
You need to use all the three jars while using Oracle Wallets. 

(4) oraclepki.jar (306,618 bytes) - (SHA1 Checksum: 46b5a28ca8758408950cfef46ef013ee0d70445d)
Additional jar required to access Oracle Wallets from Java
(5) osdt_cert.jar (210,336 bytes) - (SHA1 Checksum: 5e505ddfff926dba06e3f269d78e1882e9cec732)
Additional jar required to access Oracle Wallets from Java
(6) osdt_core.jar (312,281 bytes) - (SHA1 Checksum: b1c83e62bb4d174734aac19b0ddbce0ed89fb25e)
Additional jar required to access Oracle Wallets from Java

=============================
JARs for NLS and XDK support 
=============================
(7) orai18n.jar (1,663,954 bytes) - (SHA1 Checksum: 3744bc9f42a2d809f926d6d0d7ec44718d66b53f) 
Classes for NLS support
(8) xdb.jar (265,580 bytes) - (SHA1 Checksum: 23b599c8fc66ac9958ecb9fab7685e38d3df0ffd)
Classes to support standard JDBC 4.x java.sql.SQLXML interface 
(9) xmlparserv2.jar (1,935,495 bytes) - (SHA1 Checksum: 30761c81576dbdc6a9dea5e9a612c25d51bb621a)
Classes to support standard JDBC 4.x java.sql.SQLXML interface 
(10) xmlparserv2_sans_jaxp_services.jar (1,932,962 bytes) - (SHA1 Checksum: 443158bb117349e166e8c43b87943695d7159722) 
Classes to support standard JDBC 4.x java.sql.SQLXML interface

====================================================
JARs for Real Application Clusters(RAC), ADG, or DG 
====================================================
(11) ons.jar (156,244 bytes) - (SHA1 Checksum: 721b8113d2da1360ef5ee9868022bfe11a13dd1d)
for use by the pure Java client-side Oracle Notification Services (ONS) daemon
(12) simplefan.jar (32,169 bytes) - (SHA1 Checksum: fb25434cff353f9ce1ac059d403877404efb833e)
Java APIs for subscribing to RAC events via ONS; simplefan policy and javadoc

==================================================================================
NOTE: The diagnosability JARs **SHOULD NOT** be used in the production environment. 
These JARs (ojdbc8_g.jar,ojdbc8dms.jar, ojdbc8dms_g.jar) are meant to be used in the 
development, testing, or pre-production environment to diagnose any JDBC related issues. 

=====================================
OJDBC - Diagnosability Related JARs
===================================== 

(13) ojdbc8_g.jar (7,511,812 bytes) - (SHA1 Checksum: b4f095bd0ab1da16ce90998d3e0d9292fd38a524)
Same as ojdbc8.jar except compiled with "javac -g" and contains tracing code.

(14) ojdbc8dms.jar (6,243,252 bytes) - (SHA1 Checksum: cc728081f8240750b65b3ce5984cc2a4640131ee)
Same as ojdbc8.jar, except that it contains instrumentation to support DMS and limited java.util.logging calls.

(15) ojdbc8dms_g.jar (7,541,598 bytes) - (SHA1 Checksum: 50c638b1060724331eb4b0b6ff91ab641b408e71)
Same as ojdbc8_g.jar except that it contains instrumentation to support DMS.

(16) dms.jar (2,194,305 bytes) - (SHA1 Checksum: 07219d0fec3645d70a5824a803503399b74c5331)
dms.jar required for DMS-enabled JAR files.

==================================================================
Oracle JDBC and UCP - Javadoc and README
==================================================================

(17) JDBC-Javadoc-19c.jar (1,740,616 bytes) - JDBC API Reference 19c

(18) UCP-Javadoc-19c.jar (370,520 bytes) - UCP Java API Reference 19c

(19) simplefan-Javadoc-19c.jar (88,476 bytes) - Simplefan API Reference 19c 

(20) xdb-Javadoc-19c.jar (2,861,664 bytes) - XDB API Reference 19c 

(21) xmlparserv2-Javadoc-19c.jar (2,861,664 bytes) - xmlparserv2 API Reference 19c 

(22) JDBC-Readme.txt: It contains general information about the JDBC driver and bugs that have been fixed in the 19.15.0.0.1 release. 

(23) UCP-Readme.txt: It contains general information about UCP and bugs that are fixed in the 19.15.0.0.1 release. 

(24)Bugs-fixed-in-1915-PatchedRelease.txt: It contains the feature added in the 19.15.0.0.1 release. 

=================
USAGE GUIDELINES
=================
Refer to the JDBC Developers Guide (https://docs.oracle.com/en/database/oracle/oracle-database/19/jjdbc/index.html) and Universal Connection Pool Developers Guide (https://docs.oracle.com/en/database/oracle/oracle-database/19/jjucp/index.html) for more details. 