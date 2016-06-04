## basic twitter bot skeleton

#### add api keys to `.env`
- create an app and get api keys [here](https://apps.twitter.com/app/new)
- to see a previously created app, check [here](https://apps.twitter.com/)

#### run
- `npm i`
- `npm start`

#### make a cron job
- `crontab -e`
- add job in this format: minute, hour, day of month, month, day of week, command. to run every day at noon:

  `0 12 * * * /path/to/node /path/to/basic-twitter-bot/app.js`

#### don't forget
- add `.env` to `.gitignore`

