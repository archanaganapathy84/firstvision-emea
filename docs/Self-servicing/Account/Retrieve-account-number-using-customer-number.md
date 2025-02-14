# Retrieve account number using customer number

## Description

Retrieve all account numbers belonging to a customer.

### API to use: [Customer Records > Customer Accounts List](https://docs.firstdata.com/org/global/docs/api#customer-accounts-list-v1)

#### Relevant request variables

| Field name     | Description                                                  |
|----------------|--------------------------------------------------------------|
| **custNumber** | Customer number                                              |
| **svcType**    | Service type. A value of "A" must be entered into this field |

#### Relevant response variables

| Field name     | Description                                  |
|----------------|----------------------------------------------|
| **atNbrOccur** | Number of accounts returned on the response. |
| **acctTbl**    | Table containing account information         |
| **acctNbr**    | Account number                               |
| **blkCd1**     | Block code 1                                 |
| **blkCd2**     | Block code 2                                 |
