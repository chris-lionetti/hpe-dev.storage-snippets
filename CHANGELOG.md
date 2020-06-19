# Change Log
All notable changes to the "hpe-dev.storage-snippets" extension will be documented in this file.

## Initial release
The following snippets were incorporated into the initial release.
* Nimble Install PSTK - Downloads and Installs the latest HPE Nimble PowerShell Toolkit
* Nimble Install NWT - Downloads and Installs the latest HPE Nimble Windows Toolkit
* Nimble Add NWT PSPath - Fixes a problem where the NWT PowerShell commands are not discoverable from any powershell window. This change is persistent.
* Nimble Config NWT - Connects the Nimble Windows Toolkit PowerShell session to the array.
* Nimble CredObj - How to create a persistent credential object that can be used to connect a to a Nimble array using the Connect-NSGroup command
* Nimble AutoLogon - Allows credentials to be stored in your script and uses it to automatically connect to a Nimble Array
* Nimble Create iSCSI InititatorGroup - Creates an Initiator and Initiator Group for the localhost. Will not create new Initiator or InitiatorGroup if those entities already exist. No fields in this snippet need to be changed.
* Nimble Create FC InititatorGroup - Creates an Initiator and Initiator Group for the localhost. Will not create new Initiator if entities already exist and will use existing. If no Initiator Group exists with this hostname, will create a new Initiator Group for this host.
* Nimble Add New FC Drive - Creates a new Volume and exposes that Volume to this host via the assigned drive letter.
* Nimble Add New iSCSI Volume - Creates a new Volume and exposes that Volume to this host via the assigned drive letter.
* Nimble Store Creds In Registry - Will prompt the user for a username and password to store encrypted in the current user section of the Registry.
* Nimble Retrieve Creds from Registry - Will retrieve previously saved username and encrypted password from registry and place items into a credential object. 

