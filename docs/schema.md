# Schema

Relational data schema.

**User Credentials**

| --- | --- | --- | --- |
| **user_id** | username | email | password |

**Accounts**

| --- | --- | --- |
| **account_id** | nickname | balance |


**Budgets**

| --- | --- | --- | --- |
| **budget_id** | *account_id* | name | balance |

**Transactions**

| --- | --- | --- | --- | --- |
| **transaction_id** | *account_id* | *budget_id* | description | amount |

**Statements**

| -- | --- | --- | --- | --- | --- |
| **statement_id** | start | end | *account_id* | csv_file | pdf_file |