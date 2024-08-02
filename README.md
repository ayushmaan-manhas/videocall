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
