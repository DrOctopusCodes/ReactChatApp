Client Side/ ChatApp
Server Side

ChatApp
npx create-react-app ./
npm install --save react-router socket.io-client react-scroll-to-bottom react-emoji query-string
npm install --save react-router-dom



Server
mkdir server
cd .\server\
npm init -y
npm install --save cors nodemon express socket.io




In server, "start": "nodemon index.js" : will run the server continously, no need to explicitly start

Web Sockets are faster than http requests

front end -> netlify
back end -> heroku

server
Added Procfile
Replace nodemon with node
Do git push 
Under setttings you will find the server URL.
Copy , paste the URL as endpoint in client side

Installed heroku cli

npm run build
go to netlify - drop the build folder
Thats it