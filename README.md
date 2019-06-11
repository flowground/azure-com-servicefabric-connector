# ![LOGO](logo.png) ServiceFabricManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ServiceFabricManagementClient API (version 2017-07-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/servicefabric/2017-07-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:18+03:00

## API Description

Azure Service Fabric Resource Provider API Client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available ServiceFabric Resource Manager REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The version of the ServiceFabric resouce provider api

### List cluster resource

> List cluster resource

*Tags:* `Cluster`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

### List cluster code versions by location

> List cluster code versions by location

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions, this is different from cluster location
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

### Get cluster code versions

> Get cluster code versions by location

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions, this is different from cluster location
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier
* `clusterVersion` - _required_ - The cluster code version

### List cluster code versions by environment

> List cluster code versions by environment

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions, this is different from cluster location
* `environment` - _required_ - Cluster operating system, the default means all
    Possible values: Windows, Linux.
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

### Get cluster code versions by environment

> Get cluster code versions by environment

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions, this is different from cluster location
* `environment` - _required_ - Cluster operating system, the default means all
    Possible values: Windows, Linux.
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier
* `clusterVersion` - _required_ - The cluster code version

### Delete cluster resource

> Delete cluster resource

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

### Get cluster resource

> Get cluster resource

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

### Update cluster configuration

> Update cluster configuration

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

### Create a ServiceFabric cluster

> Create cluster resource

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

### Returns all application type names in the specified cluster.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `api-version` - _required_ - The version of the API.

### Deletes the application type name resource.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationTypeName` - _required_ - The name of the application type name resource
* `api-version` - _required_ - The version of the API.

### Returns an application type name resource.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationTypeName` - _required_ - The name of the application type name resource
* `api-version` - _required_ - The version of the API.

### Creates the application type name resource.

*Tags:* `ApplicationType`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationTypeName` - _required_ - The name of the application type name resource
* `api-version` - _required_ - The version of the API.

### Returns all versions for the specified application type.

*Tags:* `Version`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationTypeName` - _required_ - The name of the application type name resource
* `api-version` - _required_ - The version of the API.

### Unprovisions an application type version resource.

*Tags:* `Version`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationTypeName` - _required_ - The name of the application type name resource
* `version` - _required_ - The application type version.
* `api-version` - _required_ - The version of the API.

### Returns an application type version resource.

*Tags:* `Version`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationTypeName` - _required_ - The name of the application type name resource
* `version` - _required_ - The application type version.
* `api-version` - _required_ - The version of the API.

### Provisions an application type version resource.

*Tags:* `Version`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationTypeName` - _required_ - The name of the application type name resource
* `version` - _required_ - The application type version.
* `api-version` - _required_ - The version of the API.

### Returns all application resources in the specified cluster.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `api-version` - _required_ - The version of the API.

### Deletes an application resource with the specified name.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the API.

### Returns an application resource with the specified name.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the API.

### Updates an application resource with the specified name.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the API.

### Creates or updates an application resource with the specified name.

*Tags:* `Application`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the API.

### Returns all service resources in the specified application.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `api-version` - _required_ - The version of the API.

### Deletes a service resource with the specified name.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the API.

### Returns a service resource with the specified name.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the API.

### Updates a service resource with the specified name.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the API.

### Creates or updates a service resource with the specified name.

*Tags:* `Service`

#### Input Parameters
* `subscriptionId` - _required_ - The customer subscription identifier
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource
* `applicationName` - _required_ - The name of the application resource.
* `serviceName` - _required_ - The name of the service resource in the format of {applicationName}~{serviceName}.
* `api-version` - _required_ - The version of the API.

### List cluster resource by resource group

> List cluster resource by resource group

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The customer subscription identifier

## License

**flow**ground :- Telekom iPaaS / azure-com-servicefabric-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
