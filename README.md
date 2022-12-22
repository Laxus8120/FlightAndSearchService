# WELCOME TO FLIGHT SERVICE 
##
![flightSearch](https://previews.123rf.com/images/visivasnc/visivasnc1710/visivasnc171000047/87935861-booking-and-search-flight-ticket-air-travel-trip-vacation-concept-banner-web-template-.jpg)
### PROJECT SETUP
##

> Clone the Project .
> Execute npm install on the same path of your root directory of the downloaded Project.
>Create a `.env` file in the root directory and add the following enviroment variable .

    *PORT = 3000;
> Insider the `src/config` folder create a new file `config.json` and then add the following piece of json
```json
  "development": {
    "username": "YOUR_DB_LOGIN_NAME",
    "password": "YOUR_DB_PASSWORD",
    "database": "Flight_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
    }
```
>Once you added your DB config as listed above , go to the src folder from your terminal and execute `npx sequelize db:create`


