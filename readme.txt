=================================== accessing local files properties file ========================================
AppConfigServer.yml is a file which name matches with the config server.
created a bootstrap file bootstrap.yml for loading the config server properties files.
AppConfigServer.yml defined the name in bootstrap.yml file
===============================================================================================================================

=================================== accessing user specific local files properties file 
change the AppConfigServer.yml with application.yml file for generalizing services.
create a users-ws.yml file which is the name of users microsrevice.
created a bootstrap file bootstrap.yml for loading the config server properties files.
users-ws.yml file name should be mentioned in bootstrap.yml file instead previously AppConfigServer.yml 
================================================================================================================================

localhost:8089/users-ws/default (get)
localhost:8089/ConfigServer/native (get)
localhost:8089/actuator/busrefresh (get)
http://localhost:8088/users-ws/api/users/login (post)
http://localhost:8088/users-ws/api/users (post)


c:\Users\mata3\LocalConfigServer>keytool -genkeypair -alias apiEncryptionKey -keyalg RSA -dname "CN=arsalan ata,OU=API Development, O=muradee.com,L=KHI,S=Sindh,C=PK" -keypass test123 -keystore apiEncryptionKey.jks -storepass test123
Generating 2,048 bit RSA key pair and self-signed certificate (SHA256withRSA) with a validity of 90 days
        for: CN=arsalan ata, OU=API Development, O=muradee.com, L=KHI, ST=Sindh, C=PK

c:\Users\mata3\LocalConfigServer>keytool -importkeystore -srckeystore apiEncryptionKey.jks -destkeystore apiEncryptionKey.jks -deststoretype pkcs12
Enter source keystore password:
Entry for alias apiencryptionkey successfully imported.
Import command completed:  1 entries successfully imported, 0 entries failed or cancelled

Warning:
The original keystore "apiEncryptionKey.jks" is backed up as "apiEncryptionKey.jks.old"...



Payment Successful! Issuing Tickets...
Once payment is confirmed, tickets will be issued within 2 hours
Booking No. 32942508019
Karachi
New York

