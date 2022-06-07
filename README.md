# loginapp

```Custom Login/Sign up app```

# How To Run

## Clone the repo to local machine 
```bash
git pull https://github.com/suraj-singh12/loginapp.git
```
## Install Dependencies
```bash
cd loginapp
```
```npm
npm install
```

## Make .env file with following structure
```npm
PORT = any_port_no
localUrl = 'your_local_db_url'
liveUrl = 'your_live_db_url'
```
> Update the `db.js` `mongoose.connect()` code to use localUrl if you use local database.

> Note: The live url (heroku url) given in comments, would work perfectly, 
  and has nothing to do with your app. So check your localhost urls not live urls. They are the live APIs which are linked to this repository and not to your clone.
## Run the APP
```npm
npm start
```

## For Development
```npm
npm run dev
```