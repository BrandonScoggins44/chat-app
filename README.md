<h1>Chat App</h1>

<h2>Live Application</h2>
<p>https://scoggins-chat-app.herokuapp.com//</p>

<h2>Purpose</h2>
<p>This application allows users to enter a chat room and share messages in real time. Usernames must be unique to each chat room, and room names must be manually entered.
 User names and room names are case insensitive. While in a chat room, users can see other users that are in the same chat room, and my share messages or even their current
  location. Closing the browser window will exit the user from the chat room.</p>

<h2>Tech Stack</h2>
<p>This chat application was developed using Node.js, JavaScript, and basic HTML, and CSS. The popular Socket.IO module is used to achieve real time two way communication 
between client and server. Mustache template scripts are also used to dynamically render aspects of the user interface.</p>

<p>Some basic HTML and CSS is also used to create an intuitive and pleasant design.</p>

<p>GitHub is used for version control, and is setup to communicate with Heroku which is used to for "production" deployment.</p>

<h2>External API's</h2>
<h4>Google Maps</h4>
<p>https://google.com/maps</p>
<p>Google maps is used to allow users to share their locations if they choose. The user's latitude and longitude are accessed from their browser, and a link is created to 
a Google map pin of their location.</p>
