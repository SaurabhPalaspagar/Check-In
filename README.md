# Check-In


#Inspiration

Our inspiration comes from two sources - hackathon buses and t-shirt lines. Varun and Jay have been bus captains, and keeping track of people was a nightmare. What if there was a way to quickly validate riders and keep track of them? T-Shirt giveaway lines can be long because hackathon organizers (rightfully so) confirm each attendee before handing out a shirt. Why does it have to be so cumbersome?

#What it does

Our app is simple and effective - if you are hosting an event that requires you to keep track of attendees, invite them to join Events. Each user has a QR Code generated that you can scan, quickly "checking in" the user to that event. Have users hopping onto a bus? Scan their code as they get on, you can quickly check who's there and who's not. Giving away free t-shirt? Keep track of how many times they have tried to pick one up. Make your hackathon administering experience more seamless!

#How we built it

We're writing an Android app and using a QR Code library for the scanning process. A web portal for users allows admins to create and monitor events. A PHP Laravel RESTful API on AWS / Ubuntu manages a MySQL database and securely serves data to clients. A Pebble Watch client also displays the QR Code for the scanning process.

#Challenges we ran into

Pranav: facing specific challenges with interfacing Angular.js with our RESTful API, handling asynchronous calls and managing specific data as cookies, CORS issues when integrating with Laravel!

Varun: none - he's counting his blessings!

Saurabh: Rendering QR image on Pebble Watch to match 32 bit system generated token ID.

Jay: Working on a Windows machine after forgetting his MacBook Pro charger at home, writing the entire API in VIM while SSH'd into an Amazon EC2 instance via PuTTy.

#Accomplishments that we're proud of

We're really excited that we have multiple client-facing products that we were able to integrate, making for a really cool system. We feel that it flows really nicely and we were able to do so with relatively little friction, fast debugging and overall strong teamwork! Go team!

#What we learned

Pranav: Angular.js, debugging, additional web-dev considerations!

Varun: Working fast paced in a team environment and integrating successfully.

Saurabh: Using Google API Zxing for in app QR Scanning and 32 bit QR code generation.

Jay: Being flexible with my given dev tools and getting things done!

#What's next for Check In

We'd love to try using this with a small group of people at an upcoming hackathon!

#Built With

    android
    pebble
    zxing
    angular.js
    material-design
    php
    laravel
    nginx
    amazon-ec2
    ubuntu
    mysql

