### Testing APIs

- Fetches list of NORMAL transactions for a user (GET)

    The api endpoint is: 
    > <localhost/domain_name>/api/v1/user/transactions/userAddress

- Fetches the total expenses and current ether price for a user (GET)

    The api endpoint is: 
    > <localhost/domain_name>/api/v1/user/expenses/userAddress

### Setup the project

- In the root directory create a `.env` file:

- Add the PORT variable
    ```
        PORT=<port number of your choice>
    ```
    ex:
    ```
        PORT=3000
    ```
    
- Add the MONGO_URL variable for connecting to the mongodb compass or atlas
  ```
      MONGO_URL=<url of your mongodb>
  ```
  ex:
  ```
      MONGO_URL="mongodb://127.0.0.1:27017/database_name"
  ```