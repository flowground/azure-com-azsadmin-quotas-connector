# ![LOGO](logo.png) Compute Admin Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Compute Admin Client API (version 2018-02-09).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-Quotas/2018-02-09/swagger.json<br/>
Generated at: 2019-06-11T18:13:40+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all Compute quotas.

> Get a list of existing Compute quotas.

*Tags:* `Quotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `api-version` - _required_ - Client API Version.

### Deletes specified Compute quota

> Delete an existing Compute quota.

*Tags:* `Quotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `quotaName` - _required_ - Name of the quota.
* `api-version` - _required_ - Client API Version.

### Returns the requested Compute quota.

> Get an existing Compute Quota.

*Tags:* `Quotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `quotaName` - _required_ - Name of the quota.
* `api-version` - _required_ - Client API Version.

### Creates or Updates a Compute Quota.

> Creates or Updates a Compute Quota with the provided quota parameters.

*Tags:* `Quotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `quotaName` - _required_ - Name of the quota.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-quotas-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
