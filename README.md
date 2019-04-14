# Jirafeau-blueprint

This blueprint installs Jirafeau web application on Subutai P2P Cloud host. Learn more about Subutai P2P Cloud here. https://subutai.io/
Jirefeau application is a web site permitting to upload a file in a simple way and give an unique link to it. Learn more about Jirefeau here https://gitlab.com/mojo42/Jirafeau

## Installation guide


1. Fill all variables
- `maxUploadsize` is maximum upload size in Mb
- `environmentName` is a name of your environment in Subutai Bazaar
- `domainName` is your domain name
- `webContanerName` is a Subutai container hostname
- `LeaveAnsibleContainer` is a container to deploy application
- `containerSize` is a container size type
- `adminPassword` is a Jirefeau admin password

![Screenshot from 2019-04-14 15-09-15](https://user-images.githubusercontent.com/33412152/56090907-fa29ed80-5ec9-11e9-851d-c6e48ba83528.png)

2. Choose peer where your blueprint will be installed
![Screenshot from 2019-04-14 15-09-42](https://user-images.githubusercontent.com/33412152/56090912-12017180-5eca-11e9-893d-7f7977e439c0.png)

3. Press `Finish` 
![Screenshot from 2019-04-14 15-10-02](https://user-images.githubusercontent.com/33412152/56090916-17f75280-5eca-11e9-9559-4670623cd3d2.png)


Wait till the application will be installed be ready
After you can open application by your domain name address you will see such page
![Screenshot from 2019-04-14 15-30-42](https://user-images.githubusercontent.com/33412152/56090941-542ab300-5eca-11e9-9575-d63cff32fa37.png)



