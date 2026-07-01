1. add `revenue` field: for each transaction, it shows the multiplication of `unit_price` and `quantity` fields. This field will help in analyzing the total revenue generated from each transaction.

2. remove rows with:
  - invalid `unit_price`, `quantity`, `stock_code`, or `description`
  - is a cancelled transaction

3. add `is_cancelled` field: a boolean field indicating whether the transaction is cancelled or not. This will help in filtering out cancelled transactions during analysis.

4. change `invoice_date` field format: convert it to datetime format for easier date-based analysis and filtering.
