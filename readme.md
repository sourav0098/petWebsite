## **Project Phase 4**

## Prerequisites
-   VS Code
-   XAMPP
-   Register in the **petfinder** API
-   Generate the API key and secret
-   Add the following variables to the env file

```sh
API_BASE_URL = "https://api.petfinder.com/v2/animals"
API_TOKEN_URL = "https://api.petfinder.com/v2/oauth2/token"
CLIENT_ID = Your API key
CLIENT_SECRET = Your secret
```

### Instructions to use the petfinder API

To avoid code repetition the code to call the API is in the class RequestManager.php. Just call the getRequest method with your specific query String.

### Postman

Import the PetFinder.postman_collection.json file to Postman to test the API.

## Instructions to Run the Application
clone the git repo  
Create a .env file and copy the contents of .env.example to it and enter your credentials for MySQL database

composer install  
npm install  
php artisan migrate  
php artisan db:seed  
php artisan db:seed --class=UserSeeder  
npm run dev

Open a new terminal  
php artisan serve

## Tasks

-   [x] Register and Login Page
-   [x] Admin Dashboard
-   [x] Database (Migrations and Seeders)
-   [x] Update User/Admin Profile
-   [x] Change Password
-   [x] Delete Account
-   [x] Find Pets

## Resources
-   Datbase: MySQL
-   Server: XAMPP
-   IDE: VS Code
-   Bootstrap, Laravel Breeze, DataTables, Git and GitHub

### Color
black: hsl(276, 7%, 30%);  
secondary: hsl(273, 96%, 36%);  
hoverColor: hsl(273, 70%, 45%);  
footer: hsl(260, 100%, 73%);  
border: hsl(0, 0%, 82%);

### Font
Font Family: Roboto

### Contributors
Juan Gutierrez [<img src="https://i.stack.imgur.com/gVE0j.png" alt="Linkedin">](https://www.linkedin.com/in/-juan-gutierrez/)  
Jordan Chan [<img src="https://i.stack.imgur.com/gVE0j.png" alt="Linkedin">](https://www.linkedin.com/in/jordan-chan49/)   
Rutvik Joshi [<img src="https://i.stack.imgur.com/gVE0j.png" alt="Linkedin">](https://www.linkedin.com/)  
Sourav Choudhary [<img src="https://i.stack.imgur.com/gVE0j.png" alt="Linkedin">](https://www.linkedin.com/in/sourav009/) 