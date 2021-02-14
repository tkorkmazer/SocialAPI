# SOCIAL APP API WITH LARAVEL v8.26 PHP v7.4.15

## Installation

Inside the bin folder there are bash files that used for installation, artisan and composer commands.
For usage first run the following command.

```
cd SocialAPI
chmod -R 0700 bin
```

Then run the following command for docker installation.

```
bin/start.sh
```

After docker containers are installed. Run the following command.

```
bin/composer.sh install
```

I provided the .env files for project to link with Docker.

Run following command for laravel key.

```
bin/artisan.sh key:generate
```

For creation of database tables, run the following command.

```
bin/artisan.sh migrate
```

If you like you can create 10 mock user by running following command.

```
bin/artisan.sh db:seed
```

## Usage

By using postman, you can import the SocialAPI.postman_collection.json file.

## Swagger

https://app.swaggerhub.com/apis/tkorkmazer/social-api/1.0


