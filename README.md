# url_shortener
This app  reduce long urls . Built in nodejs, express, postgres and sequelize as orm. 

***Usage***
npm install   ----install all dependencies
npm run dev   ----this start the app

1-Use any api tester and send  'url' in the body req and the value(any link)
2-The app will return the 'id' (short url) and by using http://localhost:3000/url/( id/link provided ), you will be redirected to the original website registered(link).
