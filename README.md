# steam-lucky-bot
:cookie: some useful scripts work on Steam.



## explain
- index.js -- All lucky functions.
- addOne.js -- Add time-limited free games to your library.
- unlockAchievements.js -- Unlock [appids]`s lastest achievements.

## usage
```bash
git clone https://github.com/Realzzz1874/steam-lucky-bot.git
cd
yarn
```

Then:
```bash
vim .conf
```
Edit these fields:
```bash
account_id: // your steam account id
cookie: // your cookie (copy from steam website
appid: [] // Unlock [appids]`s lastest achievements
schedule: [cron format]
```

Now, you can:
```bash
pm2 start index.js
```
OR only:
```
pm2 start xxx.js
```
