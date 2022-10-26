# MySql-Task

An application using Node.js, Express.js and MySQL




## Features

- User can create account and login
- JWT authentication
- Admin can manage all the users


## Tech Stack
- Node.js
- Express.js
- MySQL
- jwt

## EnvironmentVariables

To run this project, you will need to add the following environment variables to your .env file

**Server:**

`PORT`
`JWT_SECRET`
`COOKIE_EXPIRE`

`MYSQL_PORT`
`MYSQL_HOST`
`MYSQL_USER`

`MYSQL_PASS`
`MYSQL_DB`
`ADMIN_EMAIL`

## req.body
/register:
`name`
`email`
`phone`
`password`
`confirmPassword`

/login:
`email`
`password`

## Run 

Clone the project

```bash
  git clone https://github.com/MohammedAlthafPP/Mysql-Task.git
```

Go to the project server directory

```bash
  cd Mysql-Task
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```


## Authors

- [@MohammedAlthaf](https://github.com/MohammedAlthafPP)


## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
