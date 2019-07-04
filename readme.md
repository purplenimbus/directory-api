# Directory Api
The directory api is used to serve directory listings from the database
## Setup your Development Environment
Run`git clone git@github.com:purplenimbus/directory-api.git` to clone the repo in a directory **directory-api**
### Local Database
 1. Create a new database
 2. Open `env.example`
 3. Edit the following details
	DB_DATABASE=`your database name`
	DB_USERNAME=`database username` (Usually **root**)
	DB_PASSWORD=`database password` (Can be blank if no password is set)
 4. save the file and rename it to .env (**Super important** laravel needs and env file and wont run without it )

### Install Dependencies
Run `composer install` to install Laravel dependencies

### Run the App
 1. Run `php artisan serve` in the root directory of the
    **directory-api** folder
 2. Navigate to`http://127.0.0.1:8000`  in your browser If everything went well you should see **"Laravel"**
