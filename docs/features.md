# Features
Brief description of the functionality of the app.

* **Authentication** - secure the app with a login.
* **Cloud Sync** - should be able to access the app anywhere.
* **Accounts** - see balances for each account.
    * **Budgets** - effectively sub-balances for categories within an account.
        * *forces a rebudgeting if you go overbudget*
* **Transactions** - log transactions on an account.
* **Statements** - only store the most recent transactions in the database - keep the rest in statements.
    * **Checkbook Balancing** - upload a bank statement to the app and balance the checkbook with the statement.
    * **Statement Export** - save the transactions as a csv and the statement as a PDF.
* **Reports** - generate spending reports based on transactions and assigned sub-balances.