| Feature                           | Data Type |
| --------------------------------- | --------- |
| Credit-Application-Result         | String    |
| Account-Balance                   | String    |
| Duration-of-Credit-Month          | Integer   |
| Payment-Status-of-Previous-Credit | String    |
| Purpose                           | String    |
| Credit-Amount                     | Integer   |
| Value-Savings-Stocks              | String    |
| Length-of-current-employment      | String    |
| Instalment-per-cent               | Integer   |
| Sex-and-Marital-Status            | String    |
| Guarantors                        | String    |
| Duration-in-Current-address       | Integer   |
| Most-valuable-available-asset     | String    |
| Age-years                         | Integer   |
| Concurrent-Credits                | String    |
| Type-of-apartment                 | String    |
| No-of-Credits-at-this-Bank        | Integer   |
| Occupation                        | String    |
| No-of-dependents                  | Integer   |
| Telephone                         | String    |
| Foreign-Worker                    | String    |

| **#** | **Column Name**                   | **Unique Values** | **Missing Values** | **Summary**                                             |
| ----- | --------------------------------- | ----------------- | ------------------ | ------------------------------------------------------- |
| 1     | Credit-Application-Result         | 2                 | 0                  | Creditworthy: 358, Non-Creditworthy: 142                |
| 2     | Account-Balance                   | 2                 | 0                  | No Account: 262, Some Balance: 238                      |
| 3     | Duration-of-Credit-Month          | 30                | 0                  | Mean: 21.43, Min: 4, Max: 60                            |
| 4     | Payment-Status-of-Previous-Credit | 3                 | 0                  | Paid Up: 260, No Problems: 204, Some Problems: 36       |
| 5     | Purpose                           | 4                 | 0                  | Home Related: 355, Used Car: 83, New Car: 47, Other: 15 |
| 6     | Credit-Amount                     | 464               | 0                  | Mean: 3199.98, Min: 276, Max: 18424                     |
| 7     | Value-Savings-Stocks              | 2                 | 298                | $100-$1000: 154, < $100: 48                             |
| 8     | Length-of-current-employment      | 3                 | 0                  | < 1yr: 279, 4-7 yrs: 124, 1-4 yrs: 97                   |
| 9     | Instalment-per-cent               | 4                 | 0                  | Mean: 3.01, Min: 1, Max: 4                              |
| 10    | Guarantors                        | 1                 | 457                | Yes: 43                                                 |
| 11    | Duration-in-Current-address       | 4                 | 344                | Mean: 2.66, Min: 1, Max: 4                              |
| 12    | Most-valuable-available-asset     | 4                 | 0                  | Mean: 2.36, Min: 1, Max: 4                              |
| 13    | Age-years                         | 53                | 12                 | Mean: 35.64, Min: 19, Max: 75                           |
| 14    | Concurrent-Credits                | 1                 | 0                  | Other Banks/Depts: 500                                  |
| 15    | Type-of-apartment                 | 3                 | 0                  | Mean: 1.93, Min: 1, Max: 3                              |
| 16    | No-of-Credits-at-this-Bank        | 2                 | 0                  | 1: 320, More than 1: 180                                |
| 17    | Occupation                        | 1                 | 0                  | Mean: 1.0, Min: 1, Max: 1                               |
| 18    | No-of-dependents                  | 2                 | 0                  | Mean: 1.15, Min: 1, Max: 2                              |
| 19    | Telephone                         | 2                 | 0                  | Mean: 1.4, Min: 1, Max: 2                               |
| 20    | Foreign-Worker                    | 2                 | 0                  | Mean: 1.04, Min: 1, Max: 2                              |
