
Tutohub is an LMS application developed from  Ulearn opensource script,it was customized and added new features that didnt come with the scripts to it. 
It comprises of all the basic features that needed for online learning. This package includes responsive frontend website, instructor/admin dashboard with a backend template. Admin can manage every aspect of the system, while the instructors could create creative courses through an interactive curriculum with various types of course files such as audio, video, document and text.

```diff
+ Requests: 
+ 1. Kindy give us a star in github, if you like/clone our project.
```

## Key Features
1. Laravel 5.8                        
2. React JS 16.9                       
3. Hi-Tech Learning                       
4. Social Login                  
5. Responsive Design                      
6. Course Management                     
7. Curriculum                
8. Payment Gateway                   
9. SEO Friendly                
10. Videos                 
11. Instructor Credits                        
12. Instructor Module                      
13. Admin Module                   
14. Page Management                       
15. Blogs                  
16. Website Security

## Demo & Credentials
Demo Link : http://tutohub.herokuapp.com/

|    Role       |        Email ID        |   Password    |
| ------------- | ---------------------  | ------------- |
|    Admin      | admin@ulearn.com       |    secret     |
|    Instructor | instructor@ulearn.com  |    secret     |
|    Student    | student@ulearn.com     |    secret     |

## Access ReactJS Page

Login at the following link using the student credentials, username:student@ulearn.com | password:secret

```sh
https://www.ulearnpro.com/demo/login
```

Navigate to the following link, to access the course learn page directly

```sh
https://www.ulearnpro.com/demo/course-enroll/photography-become-a-better-photographer/dlhZZTZ6bmZWTGdRd3YzVWp2ZldMQT09
```

## Installation
In the root folder, find the .env file and change the following values

```sh
APP_NAME=
APP_URL=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

Through terminal or command prompt, update composer to install the dependencies:

```sh
composer update
```
Run the migration command to create the tables

```sh
php artisan migrate
```

Run the seeder to import mandatory values to the tables

```sh
php artisan db:seed
```

## License
ULEARN is open-source software licensed under the [MIT License](LICENSE).
