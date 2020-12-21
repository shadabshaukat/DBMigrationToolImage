# DBMigrationToolImage
Custom OL7 Image with OCI DB Migration Tools

Migration Tools included in the DB Migration Tools Image:


No.	Software	Version	Description
1.	Terraform	0.12.24	Provisioning OCI Infrastructure as code
2.	ZDM (Zero Downtime Migration)	19.7	Zero Downtime Migration Tool for Physical Database migrations both offline and online
3.	MV2 Utilities -
MV2ADB
MV2OCI New!!
MV2BUCKET New!!
BCK2CLOUD New!!	
2.01-115
2.0.2.6
1.0.1.4
2.0.3.24	
Move to Autonomous Database, Datapump to Autonomous
Move to OCI, Datapump to VMDB, BM and ExaCS
Move to Bucket, Copy backup from managed bucket to target user bucket
Backup to Cloud, RMAN backup to OCI OSS
4.	Oracle Clients X86-64	12.1, 12.2, 18.3, 19.3	Full Oracle client installation in different Oracle homes with source environment variable files.
5.	OCI Client	2.17.0	'ocicli' client with Python3 SDK 
6.	Python3.7	3.7	Python 3.7.2
7.	SQLcl    	20.3.0	Command line for SQL Developer, cloud native → SQLcl
Github Code:
Repo : https://github.com/shadabshaukat/OCI_DBMigrationTools_Image

$ git clone https://github.com/shadabshaukat/OCI_DBMigrationTools_Image.git

$ cd OCI_DBMigrationTools_Image


