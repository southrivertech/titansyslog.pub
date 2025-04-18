# <img src="https://srtcdnstorage.blob.core.windows.net/software/nextgen/slserver/titansyslog48.png" alt="Titan Syslog Server logo"> Titan Syslog Server - Cloud Edition for Linux </img>

Thank you for choosing Titan Syslog Server - Cloud Edition from South River Technologies. This is the Pay-as-you-go version of our solution, meaning that it will run fully featured without the need to purchase a license from South River Technologies. Simply fire up your Titan Syslog Server VM, and run your business.

## What's on the VM?

This Titan Syslog Server Virtual Machine (VM) contains a pre-built and pre-configured installation of the product.


## Usage Instructions / Getting Started

1) Connect securely to your vm instance over SSH using your own keypair, or via the Azure or EC2 console.
2) Once you are connected to the instance terminal session the initial Titan Syslog administrator account needs to be configured. To configure the Titan Syslog administrator account, use the following command and supply your new administrator credentials. It's imporant to use a complex password consisting of a minimum of 8 characters in length, both upper and lower case, one or more numbers, and one or more special characters consisting of the following characters "(~!@#$%^&*_-+=`|\\(){}[]:;\"'<>,.?/)", and it must not included the username in the password.

```
sudo /opt/southriver/slserver/slserver /LASINIT /username='<admin-username>' /password='<admin-password>'
```
3) After the password hase been created you can hit control+c to return to the shell.

4) Once the Titan Syslog administrative credentials have been established you can now connect to the Titan Syslog web-based admin console through your web-browser by pointing it to https://`<ipaddress>`:44443. Note that this is a secure connection. However, since Titan Syslog is using a temporary certificate, you will see a security warning in the browser. Proceed past the security warning and log in to the Titan Syslog Server Admin console. At this point you will be able to configure the Titan Syslog application including adding your own TLS certificate if you wish. To import your own certificate click on "Manage Certificate" in the "Local Domain" section to import your certificate, then select this certificate from the list in the domain dialog (click on edit action).

## Features of Titan Syslog Server

Titan Syslog Server can be used to monitor your servers and collect, monitor and analyze syslog messages sent from clients.

## Events

You can configure Titan Syslog server with events that can trigger when certain sys log messages are received that either contain a keyword or phrase, or certain error code, or error level and then perform various actions:

1. Send an email when a syslog message is received.
2. Spawn a task or script to perform an action
3. Write to a log file   

## Configuration

To configure the syslog server click on the "Services" tab node under the "Default Syslog Server" instance. From here you can see that the server is preconfigured to listen on UDP port 514 for syslog messages. You can also enable TLS logging to the server. In addition to logging to the file you can enable logging to a sqlite database. To view syslog messages in real time click on the "SysLog" node.
 
## Database and Files location

The Titan Syslog database location is /var/southriver/slserver/database. The Syslog logging locations can be configured in the Titan Administrator user interface.

## Upgrading

The Titan software will periodically check for updates to the software and allow you to download the release notes and upgrade the software. You can also trigger a check for update manually from the Product Info tab in the admin user interface.

## Tech Support

Complimentary technical support is available on our website at https://helpdesk.southrivertech.com (use TitanSysLogPAYG as your registration code)

## WebSite(s)

South River Technologies corporate WebSite:  [https://www.southrivertech.com](https://www.southrivertech.com)<br/>
Titan MFT (Enterprise grade Managed File Transfer Solution): [https://www.TitanMFT.com](https://www.TitanMFT.com)<br/>
Titan DMZ Server (Secure reverse proxy server for Titan MFT): [https://www.TitanDMZ.com](https://www.TitanDMZ.com)<br/>
Titan SFTP Server micro site: [https://www.TitanFTP.com](https://www.TitanFTP.com)<br/>
WebDrive (Virtual Drive Mapping Client): [https://www.WebDrive.com](https://www.webdrive.com)<br/>
