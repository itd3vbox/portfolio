# Try It - Web!

You can try this Project - Web Application.

<br>


### Step 0
---

<br>

You need to have this following Tech installed.

<br>

- Node JS
- MySQL
- Appache Server
- PHP 
- [OPTIONAL] MAMP (Mac) OR WAMP (Windows) OR LAMP (Linux)

<br>

### Step 1
---

<br>

**1 - Projects**

<br>

Get the following Projects from GitHub:

- [Project - Front End](https://github.com/itd3vbox/portfolio-webpack)
- [Project - Back End](https://github.com/itd3vbox/portfolio-laravel)

<br>

**2 - Folders Structure**

<br>

You should have this following structure to easily test this Project: 

<br>

    |- Users/Desktop/project-portfolio
    |-- project-laravel
    |-- project-webpack
    

<br>

**3 - Front End**

<br>

To prepare the Front End just do these following commands:

<br>

```
cd path/to/project-webpack
npm install
ln -s path/to/project-webpack/dist path/to/project-laravel/public
```

<br>

**4 - Back End**

<br>

If you want run the Back End follow this following steps

<br>

- You must have Virtual Host - Virutal Domaine and adapt this following line:
```    
# path/to/project-laravel/.env

...

APP_URL=http://portfolio.ldemo
APP_URL_ADMIN=http://admin.portfolio.ldemo

...

SESSION_DOMAIN=".portfolio.ldemo"

...

```
<br>

- Create a database with this following command:
```

CREATE DATABASE ldemo_portfolio;

```

<br>

- Adapt a database configuration:
```    
# path/to/project-laravel/.env

...

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=ldemo_portfolio
DB_USERNAME=root
DB_PASSWORD=root
DB_TABLE_PREFIX=ldp_

...
```

<br>

### Step 2
---

<br>

You have now a live preview ! 