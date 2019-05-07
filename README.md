# ![LOGO](logo.png) EventHubManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the EventHubManagementClient API (version 2017-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/eventhub-EventHub/2017-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:10+03:00

## API Description

Azure Event Hubs client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Event Hub REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API Version.

### Check the give Namespace name availability.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all the available Namespaces within a subscription, irrespective of the resource groups.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the available Regions for a given sku

*Tags:* `Regions`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `sku` - _required_ - The sku type.

### Lists the available Namespaces within a resource group.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an existing namespace. This operation also removes all associated resources under the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the description of the specified namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of authorization rules for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an AuthorizationRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an AuthorizationRule for a Namespace by rule name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an AuthorizationRule for a Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the primary and secondary connection strings for the Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the primary or secondary connection strings for the specified Namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all Alias(Disaster Recovery configurations)

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Check the give Namespace name availability.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name

### Deletes an Alias(Disaster Recovery configuration)

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Retrieves Alias(Disaster Recovery configuration) for primary or secondary namespace

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a new Alias(Disaster Recovery configuration)

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of authorization rules for a Namespace.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an AuthorizationRule for a Namespace by rule name.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the primary and secondary connection strings for the Namespace.

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### This operation disables the Disaster Recovery and stops replicating changes from primary to secondary namespaces

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Invokes GEO DR failover and reconfigure the alias to point to the secondary namespace

*Tags:* `DisasterRecoveryConfigs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `alias` - _required_ - The Disaster Recovery configuration name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the Event Hubs in a Namespace.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$skip` - _optional_ - Skip is only used if a previous operation returned a partial result. If a previous response contains a nextLink element, the value of the nextLink element will include a skip parameter that specifies a starting point to use for subsequent calls.
* `$top` - _optional_ - May be used to limit the number of results to the most recent N usageDetails.

### Deletes an Event Hub from the specified Namespace and resource group.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an Event Hubs description for the specified Event Hub.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a new Event Hub as a nested resource within a Namespace.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the authorization rules for an Event Hub.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an Event Hub AuthorizationRule.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an AuthorizationRule for an Event Hub by rule name.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an AuthorizationRule for the specified Event Hub.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the ACS and SAS connection strings for the Event Hub.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the ACS and SAS connection strings for the Event Hub.

*Tags:* `EventHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the consumer groups in a Namespace. An empty feed is returned if no consumer group exists in the Namespace.

*Tags:* `ConsumerGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$skip` - _optional_ - Skip is only used if a previous operation returned a partial result. If a previous response contains a nextLink element, the value of the nextLink element will include a skip parameter that specifies a starting point to use for subsequent calls.
* `$top` - _optional_ - May be used to limit the number of results to the most recent N usageDetails.

### Deletes a consumer group from the specified Event Hub and resource group.

*Tags:* `ConsumerGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `consumerGroupName` - _required_ - The consumer group name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a description for the specified consumer group.

*Tags:* `ConsumerGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `consumerGroupName` - _required_ - The consumer group name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an Event Hubs consumer group as a nested resource within a Namespace.

*Tags:* `ConsumerGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `eventHubName` - _required_ - The Event Hub name
* `consumerGroupName` - _required_ - The consumer group name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets messaging plan for specified namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group within the azure subscription.
* `namespaceName` - _required_ - The Namespace name
* `api-version` - _required_ - Client API Version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-eventhub-event-hub-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
