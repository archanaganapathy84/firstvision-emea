# Block a card

## Description

Apply a block code to an existing card in order to prevent spend on the card.

### API to use:[Card Maintenance > Card Block Code Update](https://docs.firstdata.com/org/global/docs/api#card-block-code-update-v1)

#### Relevant request variables

| Field Name       | Description                               |
|------------------|-------------------------------------------|
| **cardNbr**      | Card number                               |
| **blockCode**    | Block code to be set                      |
| **rsnBlockCode** | Reason code for this block code(optional) |

#### Relevant response variables

A successful update will return a response code 200.
