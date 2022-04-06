## ABOUT

Recyle is a web application that awards the users with information about the weather and climate as a reward for recycling non-biodegradable products like plasic, glass, polythene and many more. Each time a user recycles an item, they accumulate points and these are in turn used for the rewards.

## INSTALLATION

Ensure you have installed composer in your local machine. If not, follow the instructions on the link below:
https://getcomposer.org/download/

### To install the project:
On the terminal, navigate to the directory where you wish install the laravel application then clone the remote repository to your local machine using the command: `git clone https://github.com/Falcons-eco-site/new.git`

Switch to the repo folder
`cd recycleApp`

Install all the dependencies using composer
`composer install`

Copy the example .env file and make the required configuration changes in the .env file
`cp .env.example .env

Generate a new application key
`php artisan key:generate`

Create a new database in your localhost (set the database connection in .env) then run the database migrations
`php artisan migrate`

Start the local development server
`php artisan serve`

You can now access the server at http://localhost:8000




