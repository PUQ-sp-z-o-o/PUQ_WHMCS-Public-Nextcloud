# PUQ_WHMCS-Public-Nextcloud

Module for the WHMCS system.
For manage NextCloudab users as a product.

Functions:

- Auto create and deploy produkt
- Only Nextcloud API using
- Multilanguage
- Using disk space statistics (UsageUpdate) peer user

Admin area:

- Suspend users
- Terminate users
- Unsuspend users
- Change the NextCloud users password
- API connection status
- NextCloud Disk status

Client area:

- Change the NextCloud admin password
- NextCloud Disk status
---------------------------------------------------------------
Testing:

WHMCS: 8.1.0

NextClous: 21.0.0

--------------------------------------------------------------
### WHMCS part setup guide
1. ```git clone https://github.com/PUQ-sp-z-o-o/PUQ_WHMCS-Public-Nextcloud.git```
2. Copy "puqPublicNextcloud" to "WHMCS_WEB_DIR/modules/servers/"

2. Create new server NextCloud in WHMCS (System Settings->Products/Services->Servers)  
- Hostname: Next cloud server DNS (cloud.xxxxx.xxx)
- IP Address: IP adres Nexcloud serwer
- Module: PuqPublicNextcloud
- Username: Nextcloud admin user
- Password: Nextcloud admin user password

3. Create a new Products/Services
- Module Settings/Module Name: PuqPublicNextcloud
