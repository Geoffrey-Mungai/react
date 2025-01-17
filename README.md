## Starting Up a React App
     First, make sure you're running a compatible version of Node. You should be using Node 16, since Node 17 has some compatibility issues with several JavaScript libraries. To check your Node version, run the following, and verify that Node 16.x.x is installed and is the default version (the -> indicates the default):

$ nvm list

->     v16.13.0
        v17.0.1
         system
default -> 16 (-> v16.13.0)
If it's not, you can install it and set it as the default with the following commands:

$ nvm install 16
$ nvm alias default 16
$ nvm use 16
 Fork and clone this lesson onto your computer, then navigate into the lesson's directory and run:

$ npm install
This will get and install all the required dependencies for React.

Next, we need to start up a server for the app to run on:

$ npm start
This will host the app and open a browser window to display it. If the server started correctly but the browser doesn't open, you can use the links that appear in the terminal to access the app. They should look something like this:

Local:            http://localhost:3000
On Your Network:  http://192.168.1.5:3000

You can use the Local link to open the app in your own browser. The second is for any other computers on your network that you want to access your app from (this is particularly useful if you want to test out your app in a mobile browser on your phone).


If we make any changes to our app while the server is running, it will 'hot reload,' and update the app in the browser. If there are app-breaking errors in your code, the browser will display those errors instead.


