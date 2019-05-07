# ![LOGO](logo.png) NetworkManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NetworkManagementClient API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/network-expressRouteGateway/2018-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:31+03:00

## API Description

The Microsoft Azure Network management API provides a RESTful set of web services that interact with Microsoft Azure Networks service to manage your network resources. The API has entities that capture the relationship between an end user and the Microsoft Azure Networks service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists ExpressRoute gateways under a given subscription.

*Tags:* `ExpressRouteGateways`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists ExpressRoute gateways in a given resource group.

*Tags:* `ExpressRouteGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified ExpressRoute gateway in a resource group. An ExpressRoute gateway resource can only be deleted when there are no connection subresources.

*Tags:* `ExpressRouteGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRouteGatewayName` - _required_ - The name of the ExpressRoute gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Fetches the details of a ExpressRoute gateway in a resource group.

*Tags:* `ExpressRouteGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRouteGatewayName` - _required_ - The name of the ExpressRoute gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a ExpressRoute gateway in a specified resource group.

*Tags:* `ExpressRouteGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRouteGatewayName` - _required_ - The name of the ExpressRoute gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists ExpressRouteConnections.

*Tags:* `ExpressRouteConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRouteGatewayName` - _required_ - The name of the ExpressRoute gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a connection to a ExpressRoute circuit.

*Tags:* `ExpressRouteConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRouteGatewayName` - _required_ - The name of the ExpressRoute gateway.
* `connectionName` - _required_ - The name of the connection subresource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the specified ExpressRouteConnection.

*Tags:* `ExpressRouteConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRouteGatewayName` - _required_ - The name of the ExpressRoute gateway.
* `connectionName` - _required_ - The name of the ExpressRoute connection.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a connection between an ExpressRoute gateway and an ExpressRoute circuit.

*Tags:* `ExpressRouteConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `expressRouteGatewayName` - _required_ - The name of the ExpressRoute gateway.
* `connectionName` - _required_ - The name of the connection subresource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-network-express-route-gateway-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
