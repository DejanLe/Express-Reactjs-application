Application from https://daveceddia.com/create-react-app-express-backend/

Create the Express App

install express
..................
npm install -g express-generator
or:  
yarn global add express-generator

create express app
................
express react-backend

 cd react-backend && npm install
 or
 cd react-backend && yarn install


run app
...............
npm start
or
yarn start

PORT=3001 node bin/www

  localhost:3001




Add React JS to Express
npm install -g create-react-app

create react app

create-react-app client

add and Configure the Proxy
 

 "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject"
  },
  "proxy": "http://localhost:3001"


Fetch the Data from React
At this point 2 servers are running: Express (on port 3001) and Create React App’s Webpack dev server (on port 3000).