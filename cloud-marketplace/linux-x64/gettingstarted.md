# <img src="https://srtcdnstorage.blob.core.windows.net/software/nextgen/slserver/titansyslog48.png" alt="Titan SysLog Server logo"> Titan SysLog Server - Enterprise Cloud Edition for Linux </img>

Thank you for choosing Titan SysLog Server - Cloud Edition from South River Technologies. This is the Pay-as-you-go version of our solution, meaning that it will run fully featured without the need to purchase a license from South River Technologies. Simply fire up your Titan SysLog Server VM, and run your business.

## What's on the VM?

This Titan SysLog Server Virtual Machine (VM) contains a pre-built and pre-configured installation of the product.

## Features of Titan SysLog Server

Titan SysLog Server can be used to monitor your servers and collect, monitor and analyze syslog messages sent from clients.

## Getting Started

Once you have securely connected to the instance over SSH, the initial Titan SysLog administrator account needs to be configured. To configure the Titan SysLog administrator account, use the following command and supply your new administrator credentials. It's imporant to use a complex password consisting of a minimum of 8 characters in length, both upper and lower case, one or more numbers, and one or more special characters consisting of the following characters "(~!@#$%^&*_-+=`|\\(){}[]:;\"'<>,.?/)", and it must not included the username in the password.

```
sudo /opt/southriver/slserver/slserver /LASINIT /username=`<admin-username>` /password=`<admin-password>`
```

Once the Titan SysLog administrative credentials have been established you can now connect to the Titan SysLog web-based admin console through your web-browser by pointing it to https://`<ipaddress>`:44443.

Note that this is a secure connection. However, since Titan SysLog is using a temporary certificate, you will see a security warning in the browser. Proceed past the security warning and log in to the Titan SysLog Server Admin console. At this point you will be able to configure the Titan SysLog application including adding your own TLS certificate. To import your own certificate click on "Manage Certificate" in the "Local Domain" section to import your certificate, then select this certificate from the list in the domain dialog (click on edit action).

## Tech Support

Complimentary technical support is available on our website at https://helpdesk.southrivertech.com (use TitanSysLogPAYG as your registration code)

## WebSite(s)

South River Technologies corporate WebSite:  [https://www.southrivertech.com](https://www.southrivertech.com)<br/>
Titan MFT (Enterprise grade Managed File Transfer Solution): [https://www.TitanMFT.com](https://www.TitanMFT.com)<br/>
Titan DMZ Server (Secure reverse proxy server for Titan MFT): [https://www.TitanDMZ.com](https://www.TitanDMZ.com)<br/>
Titan SFTP Server micro site: [https://www.TitanFTP.com](https://www.TitanFTP.com)<br/>
WebDrive (Virtual Drive Mapping Client): [https://www.WebDrive.com](https://www.webdrive.com)<br/>
