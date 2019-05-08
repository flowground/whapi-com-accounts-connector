# ![LOGO](logo.png) Accounts **flow**ground Connector

## Description

A generated **flow**ground connector for the Accounts API (version 2.0.0).

Generated from: https://api.apis.guru/v2/specs/whapi.com/accounts/2.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:52+03:00

## API Description

The Accounts API is a collection of methods used to query a customer account. It allows the developer to retrieve account-related data such as the user account balance.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Retrieves details of a customers account

> Retrieves a limited set of customer account details. For security purposes, only a subset is supplied, which does not include fields such as security questions and answers.

*Tags:* `Accounts`

#### Input Parameters
* `apiSecret` - _required_ - Another unique identifier for your application.
* `apiTicket` - _required_ - Ticket Granting Ticket obtained from a previous request
* `fields` - _optional_ - Specify an absolute field list to return (Comma-Separated List)
* `include` - _optional_ - Specify fields in addition to the default to return (Comma-Separated List)
* `exclude` - _optional_ - Specify fields from the default to exclude (Comma-Separated List)

### Get a customers account balance

> This method can be used to retrieve the customer's account balance in UK Sterling.

*Tags:* `Accounts`

#### Input Parameters
* `apiSecret` - _required_ - Another unique identifier for your application.
* `apiTicket` - _required_ - Ticket Granting Ticket obtained from a previous request
* `fields` - _optional_ - Specify an absolute field list to return (Comma-Separated List)
* `include` - _optional_ - Specify fields in addition to the default to return (Comma-Separated List)
* `exclude` - _optional_ - Specify fields from the default to exclude (Comma-Separated List)

### Sets a flag based on name to value provided for the user.

*Tags:* `flags`

#### Input Parameters
* `apiSecret` - _required_ - Another unique identifier for your application.
* `apiTicket` - _required_ - Ticket Granting Ticket obtained from a previous request
* `apiCountryCode` - _optional_ - A two-character ISO 3166-1-Alpha-2 code representing the country API to use.

### Gets a customer's account payments

> Retrieves the customer's account payments in UK Sterling.

*Tags:* `Accounts`

#### Input Parameters
* `apiSecret` - _required_ - Another unique identifier for your application.
* `apiTicket` - _required_ - Ticket Granting Ticket obtained from a previous request
* `page` - _optional_ - The page number to return (Used with pageSize)
* `pageSize` - _optional_ - Specify the number of results to return per page.
* `dateFrom` - _optional_ - The FROM datetime from payments to be returned. (yyyy-MM-ddTHH:mm:ss)
* `dateTo` - _optional_ - The TO datetime for payments to be returned. (yyyy-MM-ddTHH:mm:ss)
* `sort` - _optional_ - The order the response will be retuned by. i.e. date,desc
* `transactionType` - _optional_ - Allows the user to select with they want to see withdrawls or deposits. If it is omitted from the query both types will be returned
* `fields` - _optional_ - Specify an absolute field list to return (Comma-Separated List)
* `include` - _optional_ - Specify fields in addition to the default to return (Comma-Separated List)
* `exclude` - _optional_ - Specify fields from the default to exclude (Comma-Separated List)

### Gets a customer's rewards eligibility and opt-in/out status

*Tags:* `Accounts` `Rewards`

#### Input Parameters
* `apiSecret` - _required_ - Another unique identifier for your application.
* `apiTicket` - _required_ - Ticket Granting Ticket obtained from a previous request

## License

**flow**ground :- Telekom iPaaS / whapi-com-accounts-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
