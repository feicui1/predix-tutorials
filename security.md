## Predix UAA Security

### Prerequisites
* Predix Beta access
* Node
* Git

### Overview
Use the [Predix Security Starter Kit](https://github.com/PredixDev/security-starter) along with this tutorial to quickly secure your Predix application.

### Tutorial Steps

#### Create UAA service instance
`cf create-service predix-uaa`

Remember your admin secret!
#### Bind an app to UAA service
```
git clone some-project
cd some-project
cf push
cf bind-service ...
```
#### Find URL for your UAA service
`cf env some-project`
#### Download & Configure Security Starter Kit
`git clone https://github.com/PredixDev/security-starter.git`

Open security-starter/app/uaaConfig.json and enter the UAA URL.
#### Run Security Starter Kit
```
npm install -g bower gulp
gulp serve
```
#### Login as Admin
Enter the admin secret you created earlier.  After logging in, you'll be able to configure your instance of UAA .
#### Do more stuff

### asdf
asdf

asdf

asdf

asdf

asdf

asdf

asdf

asdf

asdfasdf

sadf

asdf

werwer

werwer

vdsf
