# Lorem Minds Server 

Please follow the instructions..

Install the  [Node](https://nodejs.dev/en/download/)

## Available Scripts

In the project directory, you can install the npm packages:

### `npm install`

Install the  [PostgreSQL database Application](https://www.postgresql.org/download/)

Open PG ADMIN application on your computer and create a new database 

Delete migrations folder and files in prisma folder

Create a .env file  and copy paste the below 

________________________________________________________________

DATABASE_URL="postgres://<USER_NAME>:<YOUR_PASSWORD>@localhost:5432/<DATABASE_NAME>"
(IT should be like this => postgres://postgres:12345678@localhost:5432/loremMinds)

PORT = 5000

ACTIVE_TOKEN_SECRET = ???DalgalanSendeSafaklarGibiEySanliHilal_10!!!
ACCESS_TOKEN_SECRET = !$%KorkmASonMezBUsafaKLArda15%Yuze12nAlS!!ancak?
REFRESH_TOKEN_SECRET = &&SuEZanlarki87$SehadetLERI34DINI3NTEM!!EL?I!$

BASE_URL= http://localhost:3000
NODE_ENV = production

EMAIL = lorem.minds@gmail.com
PASS = uvxswpcjbcowujhe

________________________________________________________________

In the project directory, you can init your database:

### `npx prisma migrate dev --name init`


In the project directory, you can run the application:

### `npm run start`

If you see the "Server at listening on port 5000" 
The application works correctly..

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
And go to registration page and register to application.
Please give your real email address to get an activation email.
After activation you can login to your account

Than you can open your databese interface to add multiple recordings 

### `npx prisma studio`

Note: When you register to application, your  password will be hashed and saved to the database. Therefore use hashed password in the prisma studio.
