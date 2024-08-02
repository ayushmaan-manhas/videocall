# A Collection of Laravel Projects

This repository contains a collection of applications built with Laravel.<br/>
At the moment I've been hacking around WebRTC so most of the applications are about WebRTC.<br/>
Most of them are demo applications for various Technical Articles I've written and going to
write on [Dev.to](https://dev.to/mupati) and [Medium](https://mupati.medium.com).

There are endpoints for some other applications I've built as well.

## Consider Sponsoring.
I plan to explore various Real Time Communication offerings and build demo apps and write about them. To keep me going, you may consider sponsoring so that I dedicate a enough time to it. Interestingly, it seems a lot of people have found it helpful given the number of emails and queries I receive for support in one way or the other.

[:heart: Sponsor](https://dashboard.flutterwave.com/donate/9oiquwbuo2ml)


## Project Setup

1. Clone the repository.<br/>
`git clone https://github.com/Mupati/laravel-video-chat`

2. Install dependencies<br/>
`composer install && npm install`

3. Create your env file from the example.<br/>
`cp env.example env`

4. Add your db details, pusher API keys and  TURN SERVER credentials.
   

## Running the Application

1. `php artisan serve` to start the server and `npm run start` to start the frontend.
2. Note that the register endpoint has been removed to prevent people from creating <br/> 
   a lot of users when they want to try out the online demo. In your local copy you can enable it in the `routes/web.php` file.
