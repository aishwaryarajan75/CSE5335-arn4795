# CSE5335-arn4795
My Personal Website which has details of my academic background and the academic projects on which I have worked and and my work experience.Below are the answers for a few questions related to this website.

Q1) What server framework did you choose and why?

I have choosed Node.js as server side framework. I have used Node.js since:

*It is quite fast. It uses the V8 engine developed by Google for use in Chrome. V8 compiles and executes JavaScript at lightening speeds mainly due to the fact that V8 compiles JavaScript into native machine code. 

*It uses the concept of event loop. The event loop is a single thread that performs all I/O operations asynchronously.when a Node application needs to perform an I/O operation, it sends an asynchronous task to the event loop, along with a callback function, and then continues to execute the rest of its program. When the async operation completes, the event loop returns to the task to execute its callback. 

*The event-driven architecture of node.js is appropriate for real-time applications, especially chat applications and games. As both the client-side and the server-side are written in JavaScript, the synchronization process is better and quicker. 

*Also, since Node.js is Javascript, the same language can be used on the backend and frontend. This means it breaks down the boundaries between front- and back-end development.


Q2) What client framework did you choose and why?

AJAX and jQuery were used as client frameworks. 

The advantages of AJAX are:

*Reduce the traffic travels between the client and the server.

*Response time is faster so increases performance and speed.

*You can use JSON (JavaScript Object Notation) which is alternative to XML. JSON is key value pair and works like an array.

*Ready Open source JavaScript libraries available for use – JQuery, Prototype, Scriptaculous, etc.

The advantages of jQuery are:

*Tt is a lot more easy to use compared to standard javascript and other javascript libraries. Apart from simple syntax, it also requires much less lines of code to achieve the same feature in comparison.

*jQuery enables you to perform hordes of functions in comparison to other Javascript libraries. 

*There are hundreds of prewritten plugins available for download to instantly speed up your development process. Another advantage behind this is the efficiency and security of the script.

*The jQuery website has a comprehensive documentation and tutorials to get even an absolute beginner in programming to get the ball rolling with this library.

*jQuery lets you develop Ajax templates with ease, Ajax enables a sleeker interface where actions can be performed on pages without requiring the entire page to be reloaded.

Q3) What aspect of the implementation did you find easy, if any, and why?

I felt that the implementation of fetching the data from json file and displaying it in the form of table as eay since i just had to fetch the data from the json file using a url and create a table and populate the data into the table unlike the maps and the bar graph part where i had to add other external links and APIs. No doubt, AJAX and jQuery were used for this but implenting this part was easier than implementing maps and bar graph part.

Q4) What aspect of the implementation did you find hard, if any, and why?

For me the implementation of maps and bargraph was a bit difficult as it had more dependencies. Also, I had to write a lot of geometrical specifications for the implementation of bar graph and for Google maps too. Also, found some difficulty in implementing the marker feature of the maps initially. 

Q5) What components OTHER than your client and server framework did you install, if any, and if so, what is their purpose for your solution? 

I haven't installed any other components other that client and server framework in my project since I tried to implement it in a least complex way, as much as possible. I have used external libraries like the d3.js library for implementing bar graph and the Google Maps API for implementing or adding the Google Maps for my website's homepage.

Q6) What Ubuntu commands are required to deploy and run your server?
Since the server side framework used is Node.js, After installing node we have to install npm. So the command used is npm install.

Also, to create package.json the command npm start is used. package.json is created when you use npm start for the first time.Later, to run the files, just go to the folder in which the files are present, through command prompt and type npm start everytime. Also, command node homepage.js is given in the start section in package.json so that everytime npm start command is types it invokes node homepage.js command and the user is directed to homepage. 
