This project uses **MySQL** as the database, and all schema design and queries were managed through **MySQL Workbench**.

- **Database Tool:** MySQL Workbench
- **Purpose:** Used for database modeling, schema design, query execution, and data management.
- **Connection:** Localhost (default port `3306`)
- **Authentication:** Username/Password (configured in Workbench) 

Add User(POST)

http://localhost:8080/api/accounts

{
"accountHolderName" : "UserName",
"balance" : 11000
}

Get All User (GET)

http://localhost:8080/api/accounts

Get a User By ID (GET)

http://localhost:8080/api/accounts/1

Deposit Amount(PUT)

http://localhost:8080/api/accounts/1/deposit
{
"amount" : 10
}


Withdraw Amount(PUT)

http://localhost:8080/api/accounts/1/withdraw
{
"amount" : 10
}


Delete a User By ID

http://localhost:8080/api/accounts/4
