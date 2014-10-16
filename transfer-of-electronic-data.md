Transfer of electronic data
===============

Certain study data (e.g. physiological measures such as overnight sleep testing, wrist or hip actigraphy, pulse oximetry, etc.) require additional means of transfer beyond CRF completion and entry into the EDC system. Typically the raw data will be sent to the Data Coordinating Center (DCC) for further processing and inclusion into study databases.

### Transfer method

Each study site will receive a username and password to access a DCC file server using SSH File Transfer Protocol (SFTP). This file server is setup and managed by Partners Enterprise Applications and is hosted within the Partners Healthcare data center, which affords it the same security protections as Partners clinical data. Sites will instructed on how to connect to the SFTP server using a free application such as FileZilla or WinSCP.

### File naming

Site staff will be asked to use specific naming guidelines when preparing files for transfer to the SFTP server. These names will distinguish between different types of data, the dates the data were collected, and may potentially include other relevant indicators (e.g. technician identifier).

### File encryption

Before initiating a transfer, site staff must encrypt and archive the data into a .ZIP (or similar) file. Each site will be assigned a password to use for this encryption step.

### Email receipts

A job will run on the SFTP server two times each day that will pull newly uploaded files from the server into another secure, firewalled file server hosted by Partners Research Computing. When this process runs an email will be generated and sent to DCC and site staff that indicates the file's receipt and whether or not it was successfully moved.

### Decryption and further processing

DCC staff will subsequently decrypt and process incoming study data files per protocol.
