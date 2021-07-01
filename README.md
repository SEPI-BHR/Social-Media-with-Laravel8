# Social Network


We created this website as our final project in Internet Engineering course 992.
Memebers:
- Sepideh Bahrami
- Tahere Hemmati
- Amir Abbasi

## About Project 
This project is a social media demo doing the following functionalities:
- Register/Login 
- Search in members
- Send a friendship request
- Accept/Ignore requests
- A specific friend page to show authenticated user's friends
- Create a post
- Write posts for your friends 
- See all posts in dashboard page including comment sections
- Suggests random users for friendship in dashboard page
- Like, dislike, and delete posts

## How to Run This Website

To download and run this application in your localhost you can follow these steps:
- Create a directory in htdocs folder if you use xampp
- Open your text editor in that directory
- Create a database named ```social_network_demo``` in phpMysql
- Import the [sql file](social-network-demo/social-network-demo.sql) into the database above 
- Open your terminal to run following commands : 
```
$git clone {the url to the GitHub repo} 
```

```
$ cd social-network-demo
```

```
$ composer install
```

```
$ mv .env.example .env
```

```
$ php artisan key:generate
```

```
$ php artisan storage:link
```

```
$ php artisan serve
```

## Used Technologies
- Laravel 8
- Vue.js 3
- Inertia.js
- Tailwind CSS

