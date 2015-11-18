## Predix UAA Security

Use the [Predix Security Starter Kit](https://github.com/PredixDev/security-starter) along with this tutorial to quickly secure your Predix application.

<section>
#### Create UAA service instance
`cf create-service predix-uaa`

Remember your admin secret!
</section>

<section>
#### Bind an app to UAA service
```
git clone some-project
cd some-project
cf push
cf bind-service ...
```
</section>

<section>
#### Find URL for your UAA service
`cf env some-project`
</section>

<section>
#### Download & Configure Security Starter Kit
`git clone https://github.com/PredixDev/security-starter.git`

Open security-starter/app/uaaConfig.json and enter the UAA URL.
</section>

<section>
#### Run Security Starter Kit
```
npm install -g bower gulp
gulp serve
```
</section>

<section>
#### Login as Admin
Enter the admin secret you created earlier.  After logging in, you'll be able to configure your instance of UAA .
</section>

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

dfs
