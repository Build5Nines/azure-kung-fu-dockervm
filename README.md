# Docker for Windows Dev Environment
This one click deployment will build a Docker on Windows Development box in Azure.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FBuild5Nines%2Fazure-kung-fu-dockervm%2Fmaster%2Fazure-deploy.json" target="_blank">
    <img src="https://github.com/Build5Nines/azure-kung-fu-dockervm/blob/master/media/Deploy-to-Azure-button.png"/>
</a>

**Software included on the VM**

1. Docker for Windows Community Edition
1. Git for Windows (bash)
1. Visual Studio Code
1. Google Chrome

## Credentials
1. User: Supplied on deploy
1. Password: Supplied on deploy

## IP for NSG
1. Make sure to set your IP Address in the NSG on deploy - default is open to *

**Starting Docker**
1. Once the VM is deployed use the Azure portal to connect.
1. Open the Computer Management Tool and add yourself to the docker-users group.
![alt text](https://github.com/Build5Nines/azure-kung-fu-dockervm/blob/master/media/dockerusers.png "User ID must be in the docker-users group")
1. Logout of the VM, and then reconnect with RDP.
1. Double click the Docker for Windows shortcut on the desktop.
1. It will take a few minutes for Docker to start the first time.

![alt text](https://github.com/Build5Nines/azure-kung-fu-dockervm/blob/master/media/dockerrun.png "Docker is Running on Windows 10 in Azure!")
