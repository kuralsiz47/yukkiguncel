

## Deployment
Read [Docs](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/requirements) for Detailed Description and Setup Guide on deploying Bot.

> Click on buttons to expand!
<details>
<summary><b>🔗 Requirements</b></summary>
<br>
    
- [Python3.9](https://www.python.org/downloads/release/python-390/)
- [Telegram API Key](https://docs.pyrogram.org/intro/setup#api-keys)
- [Telegram Bot Token](https://t.me/botfather)
- [MongoDB URI](https://telegra.ph/How-To-get-Mongodb-URI-04-06)
- [Pyrogram String Session](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/string-session)

</details>

<details>
<summary><b>🔗 String Session</b></summary>
<br>

> You'll need a [API_ID](https://notreallyshikhar.gitbook.io/yukkimusicbot/vars/mandatory-vars#1.-api_id) & [API_HASH](https://notreallyshikhar.gitbook.io/yukkimusicbot/vars/mandatory-vars#2.-api_hash) in order to generate pyrogram session. 
> Always remeber to use good API combo else your account could be deleted.
<h4> Generate Session via Repl: </h4>    
<p><a href="https://replit.com/@NotReallyShikhar/Yukki-Music-String-Gen"><img src="https://img.shields.io/badge/Generate%20On%20Repl-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a></p>

<h4> Generate Session via Telegram StringGen Bot: </h4>    
<p><a href="https://t.me/YukkiStringBot"><img src="https://img.shields.io/badge/TG%20String%20Gen%20Bot-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a></p>

</details>

<details>
<summary><b>🔗 Deploy to Heroku</b></summary>
<br>

> Heroku has two vars[ HEROKU_API_KEY & HEROKU_APP_NAME ] for Updater to work. 
> By setting those two vars you can get logs of your heroku app, set var, edit var, delete vars , check dyno usage and update bot. 
> Those two vars are not Mandatory! You can leave them blank too. 
    
<h4>Click the button below to deploy Yukki on Heroku!</h4>    
<p><a href="https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fkuralsiz47%2Fyukkiguncel"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200"/></a></p>
    

```console
shikhar@MacBook~ $ git clone https://github.com/kuralsiz47/yukkiguncel
shikhar@MacBook~ $ cd SiestaXMusic
shikhar@MacBook~ $ pip3 install -U -r requirements.txt
shikhar@MacBook~ $ cp sample.env .env
```
> Edit .env with your values and then start bot with
```console
shikhar@MacBook~ $ bash start
```
