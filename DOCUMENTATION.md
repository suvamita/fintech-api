| Endpoint                  | Description                            | Parameters                                              |
|---------------------------|----------------------------------------|---------------------------------------------------------|
| GET /simple_interest_rate | Calculate simple interest rates        | - `amount_paid` (float): The amount paid.               |
|                           |                                        | - `principle_amount` (float): The principle amount.     |
|                           |                                        | - `months` (int): The number of months.                 |
| GET /future_sip           | Calculate Future Value of SIP          | - `interval_investment` (float): The interval investment|
|                           |                                        | - `rate_of_return` (float): The rate of return.         |
|                           |                                        | - `number_of_payments` (int): The number of payments.   |
