# Bright-Money-Assignment
## ***plaid_auth***
## ***Objective:-***
Create a project in django rest framework and celery with following APIs exposed:
* User signup, login , logout APIs

* Token exchange API : An authenticated user can submit a plaid public token that he gets post link integration. a) This public token is exchanged for access token on the backend.b) This initiates an async job on the backend for fetching account and item metadata for the access token.

* Expose a webhook for handling plaid transaction updates and fetch the transactions on receival of a webhook.

* Expose an api endpoint for fetching all transaction and account data each for a user.

* Do appropriate plaid error handling

## ***Models:-***
* ***User:*** To store user login info

* ***TokenItem:*** To store Access_token and Item_id info

* ***Log:*** To store every activity log

* ***Transactions:*** To store transactions info from Plaid API

* ***Items:*** To store info of each Items

* ***Account:*** To store bank account info
