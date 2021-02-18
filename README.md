# Video Chat Application
see tutorial here: [https://dev.to/nilmadhabmondal/let-s-build-a-video-chat-app-with-javascript-and-webrtc-380b](https://dev.to/nilmadhabmondal/let-s-build-a-video-chat-app-with-javascript-and-webrtc-380b)

I deployed onto Heroku here: [link](https://github.com/webtutsplus/videoChat-WebFrontend)
* Only two persons can join in one room
## Running the app on development server
* `npm install`
* `node index.js`
* open `localhost:8000`

## Obtaining TURN/STUN credentials using Xiysys
* Do not use the credentials provided
* Go to https://xirsys.com/
* Sign Up 
* Log in to your account
* Click on `+` beside `MyFirstApp`
* Click on `static TURN Credentials` Button located below `Account Type`.
* Accept the warning by click on `+` that appears just after you clicked on `static TURN Credentials`.
* Copy the text(begins with `iceservers`) that appears below `static TURN Credentials`  and paste in `config.js` as shown in `config.js`.
