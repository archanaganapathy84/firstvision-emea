# Retrieve account limits

## Description

Retrieve financial limits for an account, including credit limits and spend limits.

### API to use: [Account Management > Account Detail Inquiry](https://docs.firstdata.com/org/global/docs/api#account-detail-inquiry-v3)

#### Relevant request variables

| Field name   | Description                   |
|--------------|-------------------------------|
| **account**  | Account number or card number |

#### Relevant response variables

| Field name          | Description                                     |
|---------------------|-------------------------------------------------|
| **crlim**           | Credit limit of account                         |
| **cashCrlim**       | Total cash credit limit for account             |
| **cashAvailCredit** | Available cash on the account                   |
| **availCredit**     | Current Open-To-Buy (OTB) amount of the account |
