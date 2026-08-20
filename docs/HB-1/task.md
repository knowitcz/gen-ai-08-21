# HB-1: Online Transactions API

* Expose REST API endpoint for online transactions
* Required fields are:
  * source account
  * target account
  * amount
* Introduce new `OnlineBankService` class which will use `AccountService`