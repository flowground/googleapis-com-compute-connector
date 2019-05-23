# ![LOGO](logo.png) Compute Engine **flow**ground Connector

## Description

A generated **flow**ground connector for the Compute Engine API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/compute/v1/swagger.json<br/>
Generated at: 2019-05-23T12:13:11+03:00

## API Description

Creates and runs virtual machines on Google Cloud Platform.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns the specified Project resource.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of accelerator types.

*Tags:* `acceleratorTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of addresses.

*Tags:* `addresses`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of autoscalers.

*Tags:* `autoscalers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of all BackendService resources, regional and global, available to the specified project.

*Tags:* `backendServices`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Name of the project scoping this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of commitments.

*Tags:* `regionCommitments`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of disk types.

*Tags:* `diskTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of persistent disks.

*Tags:* `disks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of forwarding rules.

*Tags:* `forwardingRules`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of managed instance groups and groups them by zone.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of instance groups and sorts them by zone.

*Tags:* `instanceGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves aggregated list of all of the instances in your project across all regions and zones.

*Tags:* `instances`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of interconnect attachments.

*Tags:* `interconnectAttachments`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of machine types.

*Tags:* `machineTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of node groups. Note: use nodeGroups.listNodes for more details about each group.

*Tags:* `nodeGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of node templates.

*Tags:* `nodeTemplates`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of node types.

*Tags:* `nodeTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of all operations.

*Tags:* `globalOperations`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of routers.

*Tags:* `routers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of subnetworks.

*Tags:* `subnetworks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of usable subnetworks.

*Tags:* `subnetworks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of target instances.

*Tags:* `targetInstances`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of target pools.

*Tags:* `targetPools`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of target VPN gateways.

*Tags:* `targetVpnGateways`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an aggregated list of VPN tunnels.

*Tags:* `vpnTunnels`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Disable this project as a shared VPC host project.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Disable a serivce resource (a.k.a service project) associated with this host project.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Enable this project as a shared VPC host project.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Enable service resource (a.k.a service project) for a host project, so that subnets in the host project can be used by instances in the service project.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the shared VPC host project that this project links to. May be empty if no link exists.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets service resources (a.k.a service project) associated with this host project.

*Tags:* `projects`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `order_by` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of global addresses.

*Tags:* `globalAddresses`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an address resource in the specified project using the data included in the request.

*Tags:* `globalAddresses`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified address resource.

*Tags:* `globalAddresses`

#### Input Parameters
* `address` - _required_ - Name of the address resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified address resource. Gets a list of available addresses by making a list() request.

*Tags:* `globalAddresses`

#### Input Parameters
* `address` - _required_ - Name of the address resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of BackendBucket resources available to the specified project.

*Tags:* `backendBuckets`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a BackendBucket resource in the specified project using the data included in the request.

*Tags:* `backendBuckets`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified BackendBucket resource.

*Tags:* `backendBuckets`

#### Input Parameters
* `backendBucket` - _required_ - Name of the BackendBucket resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified BackendBucket resource. Gets a list of available backend buckets by making a list() request.

*Tags:* `backendBuckets`

#### Input Parameters
* `backendBucket` - _required_ - Name of the BackendBucket resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified BackendBucket resource with the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `backendBuckets`

#### Input Parameters
* `backendBucket` - _required_ - Name of the BackendBucket resource to patch.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified BackendBucket resource with the data included in the request.

*Tags:* `backendBuckets`

#### Input Parameters
* `backendBucket` - _required_ - Name of the BackendBucket resource to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds a key for validating requests with signed URLs for this backend bucket.

*Tags:* `backendBuckets`

#### Input Parameters
* `backendBucket` - _required_ - Name of the BackendBucket resource to which the Signed URL Key should be added. The name should conform to RFC1035.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a key for validating requests with signed URLs for this backend bucket.

*Tags:* `backendBuckets`

#### Input Parameters
* `backendBucket` - _required_ - Name of the BackendBucket resource to which the Signed URL Key should be added. The name should conform to RFC1035.
* `keyName` - _required_ - The name of the Signed URL Key to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of BackendService resources available to the specified project.

*Tags:* `backendServices`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a BackendService resource in the specified project using the data included in the request. There are several restrictions and guidelines to keep in mind when creating a backend service. Read  Restrictions and Guidelines for more information.

*Tags:* `backendServices`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified BackendService resource.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified BackendService resource. Gets a list of available backend services.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches the specified BackendService resource with the data included in the request. There are several restrictions and guidelines to keep in mind when updating a backend service. Read  Restrictions and Guidelines for more information. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to patch.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified BackendService resource with the data included in the request. There are several restrictions and guidelines to keep in mind when updating a backend service. Read  Restrictions and Guidelines for more information.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds a key for validating requests with signed URLs for this backend service.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to which the Signed URL Key should be added. The name should conform to RFC1035.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a key for validating requests with signed URLs for this backend service.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to which the Signed URL Key should be added. The name should conform to RFC1035.
* `keyName` - _required_ - The name of the Signed URL Key to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the most recent health check results for this BackendService.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to which the queried instance belongs.
* `project` - _required_
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the security policy for the specified backend service.

*Tags:* `backendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to which the security policy should be set. The name should conform to RFC1035.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of firewall rules available to the specified project.

*Tags:* `firewalls`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a firewall rule in the specified project using the data included in the request.

*Tags:* `firewalls`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified firewall.

*Tags:* `firewalls`

#### Input Parameters
* `firewall` - _required_ - Name of the firewall rule to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified firewall.

*Tags:* `firewalls`

#### Input Parameters
* `firewall` - _required_ - Name of the firewall rule to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified firewall rule with the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `firewalls`

#### Input Parameters
* `firewall` - _required_ - Name of the firewall rule to patch.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified firewall rule with the data included in the request. The PUT method can only update the following fields of firewall rule: allowed, description, sourceRanges, sourceTags, targetTags.

*Tags:* `firewalls`

#### Input Parameters
* `firewall` - _required_ - Name of the firewall rule to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of GlobalForwardingRule resources available to the specified project.

*Tags:* `globalForwardingRules`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a GlobalForwardingRule resource in the specified project using the data included in the request.

*Tags:* `globalForwardingRules`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified GlobalForwardingRule resource.

*Tags:* `globalForwardingRules`

#### Input Parameters
* `forwardingRule` - _required_ - Name of the ForwardingRule resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified GlobalForwardingRule resource. Gets a list of available forwarding rules by making a list() request.

*Tags:* `globalForwardingRules`

#### Input Parameters
* `forwardingRule` - _required_ - Name of the ForwardingRule resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes target URL for the GlobalForwardingRule resource. The new target should be of the same type as the old target.

*Tags:* `globalForwardingRules`

#### Input Parameters
* `forwardingRule` - _required_ - Name of the ForwardingRule resource in which target is to be set.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of HealthCheck resources available to the specified project.

*Tags:* `healthChecks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a HealthCheck resource in the specified project using the data included in the request.

*Tags:* `healthChecks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified HealthCheck resource.

*Tags:* `healthChecks`

#### Input Parameters
* `healthCheck` - _required_ - Name of the HealthCheck resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified HealthCheck resource. Gets a list of available health checks by making a list() request.

*Tags:* `healthChecks`

#### Input Parameters
* `healthCheck` - _required_ - Name of the HealthCheck resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a HealthCheck resource in the specified project using the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `healthChecks`

#### Input Parameters
* `healthCheck` - _required_ - Name of the HealthCheck resource to patch.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a HealthCheck resource in the specified project using the data included in the request.

*Tags:* `healthChecks`

#### Input Parameters
* `healthCheck` - _required_ - Name of the HealthCheck resource to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of HttpHealthCheck resources available to the specified project.

*Tags:* `httpHealthChecks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a HttpHealthCheck resource in the specified project using the data included in the request.

*Tags:* `httpHealthChecks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified HttpHealthCheck resource.

*Tags:* `httpHealthChecks`

#### Input Parameters
* `httpHealthCheck` - _required_ - Name of the HttpHealthCheck resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified HttpHealthCheck resource. Gets a list of available HTTP health checks by making a list() request.

*Tags:* `httpHealthChecks`

#### Input Parameters
* `httpHealthCheck` - _required_ - Name of the HttpHealthCheck resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a HttpHealthCheck resource in the specified project using the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `httpHealthChecks`

#### Input Parameters
* `httpHealthCheck` - _required_ - Name of the HttpHealthCheck resource to patch.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a HttpHealthCheck resource in the specified project using the data included in the request.

*Tags:* `httpHealthChecks`

#### Input Parameters
* `httpHealthCheck` - _required_ - Name of the HttpHealthCheck resource to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of HttpsHealthCheck resources available to the specified project.

*Tags:* `httpsHealthChecks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a HttpsHealthCheck resource in the specified project using the data included in the request.

*Tags:* `httpsHealthChecks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified HttpsHealthCheck resource.

*Tags:* `httpsHealthChecks`

#### Input Parameters
* `httpsHealthCheck` - _required_ - Name of the HttpsHealthCheck resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified HttpsHealthCheck resource. Gets a list of available HTTPS health checks by making a list() request.

*Tags:* `httpsHealthChecks`

#### Input Parameters
* `httpsHealthCheck` - _required_ - Name of the HttpsHealthCheck resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a HttpsHealthCheck resource in the specified project using the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `httpsHealthChecks`

#### Input Parameters
* `httpsHealthCheck` - _required_ - Name of the HttpsHealthCheck resource to patch.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a HttpsHealthCheck resource in the specified project using the data included in the request.

*Tags:* `httpsHealthChecks`

#### Input Parameters
* `httpsHealthCheck` - _required_ - Name of the HttpsHealthCheck resource to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of custom images available to the specified project. Custom images are images you create that belong to your project. This method does not get any images that belong to other projects, including publicly-available images, like Debian 8. If you want to get a list of publicly-available images, use this method to make a request to the respective image project, such as debian-cloud or windows-cloud.

*Tags:* `images`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an image in the specified project using the data included in the request.

*Tags:* `images`

#### Input Parameters
* `forceCreate` - _optional_ - Force image creation if true.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the latest image that is part of an image family and is not deprecated.

*Tags:* `images`

#### Input Parameters
* `family` - _required_ - Name of the image family to search for.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified image.

*Tags:* `images`

#### Input Parameters
* `image` - _required_ - Name of the image resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified image. Gets a list of available images by making a list() request.

*Tags:* `images`

#### Input Parameters
* `image` - _required_ - Name of the image resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the deprecation status of an image.<br/>
> <br/>
> If an empty request body is given, clears the deprecation status instead.

*Tags:* `images`

#### Input Parameters
* `image` - _required_ - Image name.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `images`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `images`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the labels on an image. To learn more about labels, read the Labeling Resources documentation.

*Tags:* `images`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `images`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of instance templates that are contained within the specified project.

*Tags:* `instanceTemplates`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an instance template in the specified project using the data that is included in the request. If you are creating a new template to update an existing instance group, your new instance template must use the same network or, if applicable, the same subnetwork as the original template.

*Tags:* `instanceTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified instance template. Deleting an instance template is permanent and cannot be undone. It is not possible to delete templates that are already in use by a managed instance group.

*Tags:* `instanceTemplates`

#### Input Parameters
* `instanceTemplate` - _required_ - The name of the instance template to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified instance template. Gets a list of available instance templates by making a list() request.

*Tags:* `instanceTemplates`

#### Input Parameters
* `instanceTemplate` - _required_ - The name of the instance template.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `instanceTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `instanceTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `instanceTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of interconnect locations available to the specified project.

*Tags:* `interconnectLocations`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the details for the specified interconnect location. Gets a list of available interconnect locations by making a list() request.

*Tags:* `interconnectLocations`

#### Input Parameters
* `interconnectLocation` - _required_ - Name of the interconnect location to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of interconnect available to the specified project.

*Tags:* `interconnects`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a Interconnect in the specified project using the data included in the request.

*Tags:* `interconnects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified interconnect.

*Tags:* `interconnects`

#### Input Parameters
* `interconnect` - _required_ - Name of the interconnect to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified interconnect. Get a list of available interconnects by making a list() request.

*Tags:* `interconnects`

#### Input Parameters
* `interconnect` - _required_ - Name of the interconnect to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified interconnect with the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `interconnects`

#### Input Parameters
* `interconnect` - _required_ - Name of the interconnect to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the interconnectDiagnostics for the specified interconnect.

*Tags:* `interconnects`

#### Input Parameters
* `interconnect` - _required_ - Name of the interconnect resource to query.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Return a specified license code. License codes are mirrored across all projects that have permissions to read the License Code.

*Tags:* `licenseCodes`

#### Input Parameters
* `licenseCode` - _required_ - Number corresponding to the License code resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `licenseCodes`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of licenses available in the specified project. This method does not get any licenses that belong to other projects, including licenses attached to publicly-available images, like Debian 9. If you want to get a list of publicly-available licenses, use this method to make a request to the respective image project, such as debian-cloud or windows-cloud.

*Tags:* `licenses`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Create a License resource in the specified project.

*Tags:* `licenses`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified license.

*Tags:* `licenses`

#### Input Parameters
* `license` - _required_ - Name of the license resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified License resource.

*Tags:* `licenses`

#### Input Parameters
* `license` - _required_ - Name of the License resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `licenses`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `licenses`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `licenses`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of networks available to the specified project.

*Tags:* `networks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a network in the specified project using the data included in the request.

*Tags:* `networks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified network.

*Tags:* `networks`

#### Input Parameters
* `network` - _required_ - Name of the network to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified network. Gets a list of available networks by making a list() request.

*Tags:* `networks`

#### Input Parameters
* `network` - _required_ - Name of the network to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches the specified network with the data included in the request. Only the following fields can be modified: routingConfig.routingMode.

*Tags:* `networks`

#### Input Parameters
* `network` - _required_ - Name of the network to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds a peering to the specified network.

*Tags:* `networks`

#### Input Parameters
* `network` - _required_ - Name of the network resource to add peering to.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Removes a peering from the specified network.

*Tags:* `networks`

#### Input Parameters
* `network` - _required_ - Name of the network resource to remove peering from.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Switches the network mode from auto subnet mode to custom subnet mode.

*Tags:* `networks`

#### Input Parameters
* `network` - _required_ - Name of the network to be updated.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of Operation resources contained within the specified project.

*Tags:* `globalOperations`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified Operations resource.

*Tags:* `globalOperations`

#### Input Parameters
* `operation` - _required_ - Name of the Operations resource to delete.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the specified Operations resource. Gets a list of operations by making a list() request.

*Tags:* `globalOperations`

#### Input Parameters
* `operation` - _required_ - Name of the Operations resource to return.
* `project` - _required_ - Project ID for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of Route resources available to the specified project.

*Tags:* `routes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a Route resource in the specified project using the data included in the request.

*Tags:* `routes`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified Route resource.

*Tags:* `routes`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `route` - _required_ - Name of the Route resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified Route resource. Gets a list of available routes by making a list() request.

*Tags:* `routes`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `route` - _required_ - Name of the Route resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all the policies that have been configured for the specified project.

*Tags:* `securityPolicies`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a new policy in the specified project using the data included in the request.

*Tags:* `securityPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified policy.

*Tags:* `securityPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `securityPolicy` - _required_ - Name of the security policy to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the ordered rules present in a single specified policy.

*Tags:* `securityPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `securityPolicy` - _required_ - Name of the security policy to get.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches the specified policy with the data included in the request.

*Tags:* `securityPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `securityPolicy` - _required_ - Name of the security policy to update.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Inserts a rule into a security policy.

*Tags:* `securityPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `securityPolicy` - _required_ - Name of the security policy to update.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets a rule at the specified priority.

*Tags:* `securityPolicies`

#### Input Parameters
* `priority` - _optional_ - The priority of the rule to get from the security policy.
* `project` - _required_ - Project ID for this request.
* `securityPolicy` - _required_ - Name of the security policy to which the queried rule belongs.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches a rule at the specified priority.

*Tags:* `securityPolicies`

#### Input Parameters
* `priority` - _optional_ - The priority of the rule to patch.
* `project` - _required_ - Project ID for this request.
* `securityPolicy` - _required_ - Name of the security policy to update.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a rule at the specified priority.

*Tags:* `securityPolicies`

#### Input Parameters
* `priority` - _optional_ - The priority of the rule to remove from the security policy.
* `project` - _required_ - Project ID for this request.
* `securityPolicy` - _required_ - Name of the security policy to update.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of Snapshot resources contained within the specified project.

*Tags:* `snapshots`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `snapshots`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `snapshots`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the labels on a snapshot. To learn more about labels, read the Labeling Resources documentation.

*Tags:* `snapshots`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `snapshots`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified Snapshot resource. Keep in mind that deleting a single snapshot might not necessarily delete all the data on that snapshot. If any data on the snapshot that is marked for deletion is needed for subsequent snapshots, the data will be moved to the next corresponding snapshot.<br/>
> <br/>
> For more information, see Deleting snapshots.

*Tags:* `snapshots`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `snapshot` - _required_ - Name of the Snapshot resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified Snapshot resource. Gets a list of available snapshots by making a list() request.

*Tags:* `snapshots`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `snapshot` - _required_ - Name of the Snapshot resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of SslCertificate resources available to the specified project.

*Tags:* `sslCertificates`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a SslCertificate resource in the specified project using the data included in the request.

*Tags:* `sslCertificates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified SslCertificate resource.

*Tags:* `sslCertificates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `sslCertificate` - _required_ - Name of the SslCertificate resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified SslCertificate resource. Gets a list of available SSL certificates by making a list() request.

*Tags:* `sslCertificates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `sslCertificate` - _required_ - Name of the SslCertificate resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all the SSL policies that have been configured for the specified project.

*Tags:* `sslPolicies`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified SSL policy resource. Gets a list of available SSL policies by making a list() request.

*Tags:* `sslPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all features that can be specified in the SSL policy when using custom profile.

*Tags:* `sslPolicies`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified SSL policy. The SSL policy resource can be deleted only if it is not in use by any TargetHttpsProxy or TargetSslProxy resources.

*Tags:* `sslPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `sslPolicy` - _required_ - Name of the SSL policy to delete. The name must be 1-63 characters long, and comply with RFC1035.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all of the ordered rules present in a single specified policy.

*Tags:* `sslPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `sslPolicy` - _required_ - Name of the SSL policy to update. The name must be 1-63 characters long, and comply with RFC1035.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches the specified SSL policy with the data included in the request.

*Tags:* `sslPolicies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `sslPolicy` - _required_ - Name of the SSL policy to update. The name must be 1-63 characters long, and comply with RFC1035.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of TargetHttpProxy resources available to the specified project.

*Tags:* `targetHttpProxies`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a TargetHttpProxy resource in the specified project using the data included in the request.

*Tags:* `targetHttpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified TargetHttpProxy resource.

*Tags:* `targetHttpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetHttpProxy` - _required_ - Name of the TargetHttpProxy resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified TargetHttpProxy resource. Gets a list of available target HTTP proxies by making a list() request.

*Tags:* `targetHttpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `targetHttpProxy` - _required_ - Name of the TargetHttpProxy resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of TargetHttpsProxy resources available to the specified project.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a TargetHttpsProxy resource in the specified project using the data included in the request.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified TargetHttpsProxy resource.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetHttpsProxy` - _required_ - Name of the TargetHttpsProxy resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified TargetHttpsProxy resource. Gets a list of available target HTTPS proxies by making a list() request.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `targetHttpsProxy` - _required_ - Name of the TargetHttpsProxy resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the QUIC override policy for TargetHttpsProxy.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetHttpsProxy` - _required_ - Name of the TargetHttpsProxy resource to set the QUIC override policy for. The name should conform to RFC1035.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the SSL policy for TargetHttpsProxy. The SSL policy specifies the server-side support for SSL features. This affects connections between clients and the HTTPS proxy load balancer. They do not affect the connection between the load balancer and the backends.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetHttpsProxy` - _required_ - Name of the TargetHttpsProxy resource whose SSL policy is to be set. The name must be 1-63 characters long, and comply with RFC1035.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of TargetSslProxy resources available to the specified project.

*Tags:* `targetSslProxies`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a TargetSslProxy resource in the specified project using the data included in the request.

*Tags:* `targetSslProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified TargetSslProxy resource.

*Tags:* `targetSslProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetSslProxy` - _required_ - Name of the TargetSslProxy resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified TargetSslProxy resource. Gets a list of available target SSL proxies by making a list() request.

*Tags:* `targetSslProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `targetSslProxy` - _required_ - Name of the TargetSslProxy resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the BackendService for TargetSslProxy.

*Tags:* `targetSslProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetSslProxy` - _required_ - Name of the TargetSslProxy resource whose BackendService resource is to be set.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the ProxyHeaderType for TargetSslProxy.

*Tags:* `targetSslProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetSslProxy` - _required_ - Name of the TargetSslProxy resource whose ProxyHeader is to be set.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes SslCertificates for TargetSslProxy.

*Tags:* `targetSslProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetSslProxy` - _required_ - Name of the TargetSslProxy resource whose SslCertificate resource is to be set.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the SSL policy for TargetSslProxy. The SSL policy specifies the server-side support for SSL features. This affects connections between clients and the SSL proxy load balancer. They do not affect the connection between the load balancer and the backends.

*Tags:* `targetSslProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetSslProxy` - _required_ - Name of the TargetSslProxy resource whose SSL policy is to be set. The name must be 1-63 characters long, and comply with RFC1035.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of TargetTcpProxy resources available to the specified project.

*Tags:* `targetTcpProxies`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a TargetTcpProxy resource in the specified project using the data included in the request.

*Tags:* `targetTcpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified TargetTcpProxy resource.

*Tags:* `targetTcpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetTcpProxy` - _required_ - Name of the TargetTcpProxy resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified TargetTcpProxy resource. Gets a list of available target TCP proxies by making a list() request.

*Tags:* `targetTcpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `targetTcpProxy` - _required_ - Name of the TargetTcpProxy resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the BackendService for TargetTcpProxy.

*Tags:* `targetTcpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetTcpProxy` - _required_ - Name of the TargetTcpProxy resource whose BackendService resource is to be set.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the ProxyHeaderType for TargetTcpProxy.

*Tags:* `targetTcpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetTcpProxy` - _required_ - Name of the TargetTcpProxy resource whose ProxyHeader is to be set.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of UrlMap resources available to the specified project.

*Tags:* `urlMaps`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a UrlMap resource in the specified project using the data included in the request.

*Tags:* `urlMaps`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified UrlMap resource.

*Tags:* `urlMaps`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `urlMap` - _required_ - Name of the UrlMap resource to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified UrlMap resource. Gets a list of available URL maps by making a list() request.

*Tags:* `urlMaps`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `urlMap` - _required_ - Name of the UrlMap resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches the specified UrlMap resource with the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `urlMaps`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `urlMap` - _required_ - Name of the UrlMap resource to patch.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified UrlMap resource with the data included in the request.

*Tags:* `urlMaps`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `urlMap` - _required_ - Name of the UrlMap resource to update.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Initiates a cache invalidation operation, invalidating the specified path, scoped to the specified UrlMap.

*Tags:* `urlMaps`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `urlMap` - _required_ - Name of the UrlMap scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Runs static validation for the UrlMap. In particular, the tests of the provided UrlMap will be run. Calling this method does NOT create the UrlMap.

*Tags:* `urlMaps`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `urlMap` - _required_ - Name of the UrlMap resource to be validated as.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all shared VPC host projects visible to the user in an organization.

*Tags:* `projects`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `order_by` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Moves a persistent disk from one zone to another.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Moves an instance and its attached persistent disks from one zone to another.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of region resources available to the specified project.

*Tags:* `regions`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified Region resource. Gets a list of available regions by making a list() request.

*Tags:* `regions`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of addresses contained within the specified region.

*Tags:* `addresses`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an address resource in the specified project using the data included in the request.

*Tags:* `addresses`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified address resource.

*Tags:* `addresses`

#### Input Parameters
* `address` - _required_ - Name of the address resource to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified address resource.

*Tags:* `addresses`

#### Input Parameters
* `address` - _required_ - Name of the address resource to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of autoscalers contained within the specified region.

*Tags:* `regionAutoscalers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates an autoscaler in the specified project using the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `regionAutoscalers`

#### Input Parameters
* `autoscaler` - _optional_ - Name of the autoscaler to patch.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an autoscaler in the specified project using the data included in the request.

*Tags:* `regionAutoscalers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates an autoscaler in the specified project using the data included in the request.

*Tags:* `regionAutoscalers`

#### Input Parameters
* `autoscaler` - _optional_ - Name of the autoscaler to update.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified autoscaler.

*Tags:* `regionAutoscalers`

#### Input Parameters
* `autoscaler` - _required_ - Name of the autoscaler to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified autoscaler.

*Tags:* `regionAutoscalers`

#### Input Parameters
* `autoscaler` - _required_ - Name of the autoscaler to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of regional BackendService resources available to the specified project in the given region.

*Tags:* `regionBackendServices`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a regional BackendService resource in the specified project using the data included in the request. There are several restrictions and guidelines to keep in mind when creating a regional backend service. Read  Restrictions and Guidelines for more information.

*Tags:* `regionBackendServices`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified regional BackendService resource.

*Tags:* `regionBackendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified regional BackendService resource.

*Tags:* `regionBackendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified regional BackendService resource with the data included in the request. There are several restrictions and guidelines to keep in mind when updating a backend service. Read  Restrictions and Guidelines for more information. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `regionBackendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to patch.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified regional BackendService resource with the data included in the request. There are several restrictions and guidelines to keep in mind when updating a backend service. Read  Restrictions and Guidelines for more information.

*Tags:* `regionBackendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource to update.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the most recent health check results for this regional BackendService.

*Tags:* `regionBackendServices`

#### Input Parameters
* `backendService` - _required_ - Name of the BackendService resource for which to get health.
* `project` - _required_
* `region` - _required_ - Name of the region scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of commitments contained within the specified region.

*Tags:* `regionCommitments`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a commitment in the specified project using the data included in the request.

*Tags:* `regionCommitments`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified commitment resource. Gets a list of available commitments by making a list() request.

*Tags:* `regionCommitments`

#### Input Parameters
* `commitment` - _required_ - Name of the commitment to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of regional disk types available to the specified project.

*Tags:* `regionDiskTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified regional disk type. Gets a list of available disk types by making a list() request.

*Tags:* `regionDiskTypes`

#### Input Parameters
* `diskType` - _required_ - Name of the disk type to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of persistent disks contained within the specified region.

*Tags:* `regionDisks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a persistent regional disk in the specified project using the data included in the request.

*Tags:* `regionDisks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `sourceImage` - _optional_ - Optional. Source image to restore onto a disk.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified regional persistent disk. Deleting a regional disk removes all the replicas of its data permanently and is irreversible. However, deleting a disk does not delete any snapshots previously made from the disk. You must separately delete snapshots.

*Tags:* `regionDisks`

#### Input Parameters
* `disk` - _required_ - Name of the regional persistent disk to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns a specified regional persistent disk.

*Tags:* `regionDisks`

#### Input Parameters
* `disk` - _required_ - Name of the regional persistent disk to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a snapshot of this regional disk.

*Tags:* `regionDisks`

#### Input Parameters
* `disk` - _required_ - Name of the regional persistent disk to snapshot.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Resizes the specified regional persistent disk.

*Tags:* `regionDisks`

#### Input Parameters
* `disk` - _required_ - Name of the regional persistent disk.
* `project` - _required_ - The project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the labels on the target regional disk.

*Tags:* `regionDisks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `resource` - _required_ - Name or id of the resource for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `regionDisks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of ForwardingRule resources available to the specified project and region.

*Tags:* `forwardingRules`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a ForwardingRule resource in the specified project and region using the data included in the request.

*Tags:* `forwardingRules`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified ForwardingRule resource.

*Tags:* `forwardingRules`

#### Input Parameters
* `forwardingRule` - _required_ - Name of the ForwardingRule resource to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified ForwardingRule resource.

*Tags:* `forwardingRules`

#### Input Parameters
* `forwardingRule` - _required_ - Name of the ForwardingRule resource to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes target URL for forwarding rule. The new target should be of the same type as the old target.

*Tags:* `forwardingRules`

#### Input Parameters
* `forwardingRule` - _required_ - Name of the ForwardingRule resource in which target is to be set.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of managed instance groups that are contained within the specified region.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a managed instance group using the information that you specify in the request. After the group is created, instances in the group are created using the specified instance template. This operation is marked as DONE when the group is created even if the instances in the group have not yet been created. You must separately verify the status of the individual instances with the listmanagedinstances method.<br/>
> <br/>
> A regional managed instance group can contain up to 2000 instances.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified managed instance group and all of the instances in that group.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - Name of the managed instance group to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns all of the details about the specified managed instance group.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - Name of the managed instance group to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a managed instance group using the information that you specify in the request. This operation is marked as DONE when the group is patched even if the instances in the group are still in the process of being patched. You must separately verify the status of the individual instances with the listmanagedinstances method. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the instance group manager.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Flags the specified instances to be immediately removed from the managed instance group. Abandoning an instance does not delete the instance, but it does remove the instance from any target pools that are applied by the managed instance group. This method reduces the targetSize of the managed instance group by the number of instances that you abandon. This operation is marked as DONE when the action is scheduled even if the instances have not yet been removed from the group. You must separately verify the status of the abandoning action with the listmanagedinstances method.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.<br/>
> <br/>
> You can specify a maximum of 1000 instances with this method per request.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - Name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Flags the specified instances in the managed instance group to be immediately deleted. The instances are also removed from any target pools of which they were a member. This method reduces the targetSize of the managed instance group by the number of instances that you delete. The deleteInstances operation is marked DONE if the deleteInstances request is successful. The underlying actions take additional time. You must separately verify the status of the deleting action with the listmanagedinstances method.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.<br/>
> <br/>
> You can specify a maximum of 1000 instances with this method per request.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - Name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the instances in the managed instance group and instances that are scheduled to be created. The list includes any current actions that the group has scheduled for its instances.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `order_by` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.

### Flags the specified instances in the managed instance group to be immediately recreated. The instances are deleted and recreated using the current instance template for the managed instance group. This operation is marked as DONE when the flag is set even if the instances have not yet been recreated. You must separately verify the status of the recreating action with the listmanagedinstances method.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.<br/>
> <br/>
> You can specify a maximum of 1000 instances with this method per request.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - Name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the intended size of the managed instance group. If you increase the size, the group creates new instances using the current instance template. If you decrease the size, the group deletes one or more instances.<br/>
> <br/>
> The resize operation is marked DONE if the resize request is successful. The underlying actions take additional time. You must separately verify the status of the creating or deleting actions with the listmanagedinstances method.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - Name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `size` - _required_ - Number of instances that should exist in this instance group manager.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the instance template to use when creating new instances or recreating instances in this group. Existing instances are not affected.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Modifies the target pools to which all new instances in this group are assigned. Existing instances in the group are not affected.

*Tags:* `regionInstanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - Name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of instance group resources contained within the specified region.

*Tags:* `regionInstanceGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified instance group resource.

*Tags:* `regionInstanceGroups`

#### Input Parameters
* `instanceGroup` - _required_ - Name of the instance group resource to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the instances in the specified instance group and displays information about the named ports. Depending on the specified options, this method can list all instances or only the instances that are running.

*Tags:* `regionInstanceGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `instanceGroup` - _required_ - Name of the regional instance group for which we want to list the instances.
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.

### Sets the named ports for the specified regional instance group.

*Tags:* `regionInstanceGroups`

#### Input Parameters
* `instanceGroup` - _required_ - The name of the regional instance group where the named ports are updated.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of interconnect attachments contained within the specified region.

*Tags:* `interconnectAttachments`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an InterconnectAttachment in the specified project using the data included in the request.

*Tags:* `interconnectAttachments`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified interconnect attachment.

*Tags:* `interconnectAttachments`

#### Input Parameters
* `interconnectAttachment` - _required_ - Name of the interconnect attachment to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified interconnect attachment.

*Tags:* `interconnectAttachments`

#### Input Parameters
* `interconnectAttachment` - _required_ - Name of the interconnect attachment to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified interconnect attachment with the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `interconnectAttachments`

#### Input Parameters
* `interconnectAttachment` - _required_ - Name of the interconnect attachment to patch.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of node templates available to the specified project.

*Tags:* `nodeTemplates`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a NodeTemplate resource in the specified project using the data included in the request.

*Tags:* `nodeTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified NodeTemplate resource.

*Tags:* `nodeTemplates`

#### Input Parameters
* `nodeTemplate` - _required_ - Name of the NodeTemplate resource to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified node template. Gets a list of available node templates by making a list() request.

*Tags:* `nodeTemplates`

#### Input Parameters
* `nodeTemplate` - _required_ - Name of the node template to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `nodeTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `nodeTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `nodeTemplates`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of Operation resources contained within the specified region.

*Tags:* `regionOperations`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified region-specific Operations resource.

*Tags:* `regionOperations`

#### Input Parameters
* `operation` - _required_ - Name of the Operations resource to delete.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the specified region-specific Operations resource.

*Tags:* `regionOperations`

#### Input Parameters
* `operation` - _required_ - Name of the Operations resource to return.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of Router resources available to the specified project.

*Tags:* `routers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a Router resource in the specified project and region using the data included in the request.

*Tags:* `routers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified Router resource.

*Tags:* `routers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `router` - _required_ - Name of the Router resource to delete.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified Router resource. Gets a list of available routers by making a list() request.

*Tags:* `routers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `router` - _required_ - Name of the Router resource to return.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches the specified Router resource with the data included in the request. This method supports PATCH semantics and uses JSON merge patch format and processing rules.

*Tags:* `routers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `router` - _required_ - Name of the Router resource to patch.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified Router resource with the data included in the request.

*Tags:* `routers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `router` - _required_ - Name of the Router resource to update.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves runtime Nat mapping information of VM endpoints.

*Tags:* `routers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `router` - _required_ - Name of the Router resource to query for Nat Mapping information of VM endpoints.

### Retrieves runtime information of the specified router.

*Tags:* `routers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `router` - _required_ - Name of the Router resource to query.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Preview fields auto-generated during router create and update operations. Calling this method does NOT create or update the router.

*Tags:* `routers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `router` - _required_ - Name of the Router resource to query.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of subnetworks available to the specified project.

*Tags:* `subnetworks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a subnetwork in the specified project using the data included in the request.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - The name of the region for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified subnetwork.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `subnetwork` - _required_ - Name of the Subnetwork resource to delete.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified subnetwork. Gets a list of available subnetworks list() request.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `subnetwork` - _required_ - Name of the Subnetwork resource to return.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Patches the specified subnetwork with the data included in the request. Only certain fields can up updated with a patch request as indicated in the field descriptions. You must specify the current fingeprint of the subnetwork resource being patched.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `subnetwork` - _required_ - Name of the Subnetwork resource to patch.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Expands the IP CIDR range of the subnetwork to a specified value.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `subnetwork` - _required_ - Name of the Subnetwork resource to update.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Set whether VMs in this subnet can access Google services without assigning external IP addresses through Private Google Access.

*Tags:* `subnetworks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `subnetwork` - _required_ - Name of the Subnetwork resource.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of target pools available to the specified project and region.

*Tags:* `targetPools`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a target pool in the specified project and region using the data included in the request.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified target pool.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetPool` - _required_ - Name of the TargetPool resource to delete.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified target pool. Gets a list of available target pools by making a list() request.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `targetPool` - _required_ - Name of the TargetPool resource to return.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds health check URLs to a target pool.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetPool` - _required_ - Name of the target pool to add a health check to.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds an instance to a target pool.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetPool` - _required_ - Name of the TargetPool resource to add instances to.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the most recent health check results for each IP for the instance that is referenced by the given target pool.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `targetPool` - _required_ - Name of the TargetPool resource to which the queried instance belongs.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Removes health check URL from a target pool.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetPool` - _required_ - Name of the target pool to remove health checks from.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Removes instance URL from a target pool.

*Tags:* `targetPools`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetPool` - _required_ - Name of the TargetPool resource to remove instances from.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes a backup target pool's configurations.

*Tags:* `targetPools`

#### Input Parameters
* `failoverRatio` - _optional_ - New failoverRatio value for the target pool.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region scoping this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetPool` - _required_ - Name of the TargetPool resource to set a backup pool for.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of target VPN gateways available to the specified project and region.

*Tags:* `targetVpnGateways`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a target VPN gateway in the specified project and region using the data included in the request.

*Tags:* `targetVpnGateways`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified target VPN gateway.

*Tags:* `targetVpnGateways`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetVpnGateway` - _required_ - Name of the target VPN gateway to delete.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified target VPN gateway. Gets a list of available target VPN gateways by making a list() request.

*Tags:* `targetVpnGateways`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `targetVpnGateway` - _required_ - Name of the target VPN gateway to return.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of VpnTunnel resources contained in the specified project and region.

*Tags:* `vpnTunnels`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a VpnTunnel resource in the specified project and region using the data included in the request.

*Tags:* `vpnTunnels`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified VpnTunnel resource.

*Tags:* `vpnTunnels`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `vpnTunnel` - _required_ - Name of the VpnTunnel resource to delete.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified VpnTunnel resource. Gets a list of available VPN tunnels by making a list() request.

*Tags:* `vpnTunnels`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `region` - _required_ - Name of the region for this request.
* `vpnTunnel` - _required_ - Name of the VpnTunnel resource to return.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets metadata common to all instances within the specified project using the data included in the request.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the default network tier of the project. The default network tier is used when an address/forwardingRule/instance is created without specifying the network tier field.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Enables the usage export feature and sets the usage export bucket where reports are stored. If you provide an empty request body using this method, the usage export feature will be disabled.

*Tags:* `projects`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the URL map for TargetHttpProxy.

*Tags:* `targetHttpProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetHttpProxy` - _required_ - Name of the TargetHttpProxy to set a URL map for.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Replaces SslCertificates for TargetHttpsProxy.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetHttpsProxy` - _required_ - Name of the TargetHttpsProxy resource to set an SslCertificates resource for.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the URL map for TargetHttpsProxy.

*Tags:* `targetHttpsProxies`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetHttpsProxy` - _required_ - Name of the TargetHttpsProxy resource whose URL map is to be set.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of Zone resources available to the specified project.

*Tags:* `zones`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified Zone resource. Gets a list of available zones by making a list() request.

*Tags:* `zones`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - Name of the zone resource to return.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of accelerator types available to the specified project.

*Tags:* `acceleratorTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified accelerator type.

*Tags:* `acceleratorTypes`

#### Input Parameters
* `acceleratorType` - _required_ - Name of the accelerator type to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of autoscalers contained within the specified zone.

*Tags:* `autoscalers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - Name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates an autoscaler in the specified project using the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `autoscalers`

#### Input Parameters
* `autoscaler` - _optional_ - Name of the autoscaler to patch.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - Name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an autoscaler in the specified project using the data included in the request.

*Tags:* `autoscalers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - Name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates an autoscaler in the specified project using the data included in the request.

*Tags:* `autoscalers`

#### Input Parameters
* `autoscaler` - _optional_ - Name of the autoscaler to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - Name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified autoscaler.

*Tags:* `autoscalers`

#### Input Parameters
* `autoscaler` - _required_ - Name of the autoscaler to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - Name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified autoscaler resource. Gets a list of available autoscalers by making a list() request.

*Tags:* `autoscalers`

#### Input Parameters
* `autoscaler` - _required_ - Name of the autoscaler to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - Name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of disk types available to the specified project.

*Tags:* `diskTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified disk type. Gets a list of available disk types by making a list() request.

*Tags:* `diskTypes`

#### Input Parameters
* `diskType` - _required_ - Name of the disk type to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of persistent disks contained within the specified zone.

*Tags:* `disks`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a persistent disk in the specified project using the data in the request. You can create a disk with a sourceImage, a sourceSnapshot, or create an empty 500 GB data disk by omitting all properties. You can also create a disk that is larger than the default size by specifying the sizeGb property.

*Tags:* `disks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `sourceImage` - _optional_ - Optional. Source image to restore onto a disk.
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified persistent disk. Deleting a disk removes its data permanently and is irreversible. However, deleting a disk does not delete any snapshots previously made from the disk. You must separately delete snapshots.

*Tags:* `disks`

#### Input Parameters
* `disk` - _required_ - Name of the persistent disk to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns a specified persistent disk. Gets a list of available persistent disks by making a list() request.

*Tags:* `disks`

#### Input Parameters
* `disk` - _required_ - Name of the persistent disk to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a snapshot of a specified persistent disk.

*Tags:* `disks`

#### Input Parameters
* `disk` - _required_ - Name of the persistent disk to snapshot.
* `guestFlush` - _optional_
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Resizes the specified persistent disk. You can only increase the size of the disk.

*Tags:* `disks`

#### Input Parameters
* `disk` - _required_ - The name of the persistent disk.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `disks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `disks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the labels on a disk. To learn more about labels, read the Labeling Resources documentation.

*Tags:* `disks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `disks`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of managed instance groups that are contained within the specified project and zone.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a managed instance group using the information that you specify in the request. After the group is created, instances in the group are created using the specified instance template. This operation is marked as DONE when the group is created even if the instances in the group have not yet been created. You must separately verify the status of the individual instances with the listmanagedinstances method.<br/>
> <br/>
> A managed instance group can have up to 1000 VM instances per group. Please contact Cloud Support if you need an increase in this limit.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where you want to create the managed instance group.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified managed instance group and all of the instances in that group. Note that the instance group must not belong to a backend service. Read  Deleting an instance group for more information.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns all of the details about the specified managed instance group. Gets a list of available managed instance groups by making a list() request.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a managed instance group using the information that you specify in the request. This operation is marked as DONE when the group is patched even if the instances in the group are still in the process of being patched. You must separately verify the status of the individual instances with the listManagedInstances method. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the instance group manager.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where you want to create the managed instance group.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Flags the specified instances to be removed from the managed instance group. Abandoning an instance does not delete the instance, but it does remove the instance from any target pools that are applied by the managed instance group. This method reduces the targetSize of the managed instance group by the number of instances that you abandon. This operation is marked as DONE when the action is scheduled even if the instances have not yet been removed from the group. You must separately verify the status of the abandoning action with the listmanagedinstances method.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.<br/>
> <br/>
> You can specify a maximum of 1000 instances with this method per request.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Flags the specified instances in the managed instance group for immediate deletion. The instances are also removed from any target pools of which they were a member. This method reduces the targetSize of the managed instance group by the number of instances that you delete. This operation is marked as DONE when the action is scheduled even if the instances are still being deleted. You must separately verify the status of the deleting action with the listmanagedinstances method.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.<br/>
> <br/>
> You can specify a maximum of 1000 instances with this method per request.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists all of the instances in the managed instance group. Each instance in the list has a currentAction, which indicates the action that the managed instance group is performing on the instance. For example, if the group is still creating an instance, the currentAction is CREATING. If a previous action failed, the list displays the errors for that failed action.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `order_by` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone where the managed instance group is located.

### Flags the specified instances in the managed instance group to be immediately recreated. The instances are deleted and recreated using the current instance template for the managed instance group. This operation is marked as DONE when the flag is set even if the instances have not yet been recreated. You must separately verify the status of the recreating action with the listmanagedinstances method.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.<br/>
> <br/>
> You can specify a maximum of 1000 instances with this method per request.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Resizes the managed instance group. If you increase the size, the group creates new instances using the current instance template. If you decrease the size, the group deletes instances. The resize operation is marked DONE when the resize actions are scheduled even if the group has not yet added or deleted any instances. You must separately verify the status of the creating or deleting actions with the listmanagedinstances method.<br/>
> <br/>
> When resizing down, the instance group arbitrarily chooses the order in which VMs are deleted. The group takes into account some VM attributes when making the selection including:<br/>
> <br/>
> + The status of the VM instance. + The health of the VM instance. + The instance template version the VM is based on. + For regional managed instance groups, the location of the VM instance.<br/>
> <br/>
> This list is subject to change.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration has elapsed before the VM instance is removed or deleted.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `size` - _required_ - The number of running instances that the managed instance group should maintain at any given time. The group automatically adds or removes instances to maintain the number of instances specified by this parameter.
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Specifies the instance template to use when creating new instances in this group. The templates for existing instances in the group do not change unless you recreate them.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Modifies the target pools to which all instances in this managed instance group are assigned. The target pools automatically apply to all of the instances in the managed instance group. This operation is marked DONE when you make the request even if the instances have not yet been added to their target pools. The change might take some time to apply to all of the instances in the group depending on the size of the group.

*Tags:* `instanceGroupManagers`

#### Input Parameters
* `instanceGroupManager` - _required_ - The name of the managed instance group.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the managed instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of instance groups that are located in the specified project and zone.

*Tags:* `instanceGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone where the instance group is located.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an instance group in the specified project using the parameters that are included in the request.

*Tags:* `instanceGroups`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where you want to create the instance group.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified instance group. The instances in the group are not deleted. Note that instance group must not belong to a backend service. Read  Deleting an instance group for more information.

*Tags:* `instanceGroups`

#### Input Parameters
* `instanceGroup` - _required_ - The name of the instance group to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified instance group. Gets a list of available instance groups by making a list() request.

*Tags:* `instanceGroups`

#### Input Parameters
* `instanceGroup` - _required_ - The name of the instance group.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone where the instance group is located.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds a list of instances to the specified instance group. All of the instances in the instance group must be in the same network/subnetwork. Read  Adding instances for more information.

*Tags:* `instanceGroups`

#### Input Parameters
* `instanceGroup` - _required_ - The name of the instance group where you are adding instances.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the instances in the specified instance group.

*Tags:* `instanceGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `instanceGroup` - _required_ - The name of the instance group from which you want to generate a list of included instances.
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone where the instance group is located.

### Removes one or more instances from the specified instance group, but does not delete those instances.<br/>
> <br/>
> If the group is part of a backend service that has enabled connection draining, it can take up to 60 seconds after the connection draining duration before the VM instance is removed or deleted.

*Tags:* `instanceGroups`

#### Input Parameters
* `instanceGroup` - _required_ - The name of the instance group where the specified instances will be removed.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the named ports for the specified instance group.

*Tags:* `instanceGroups`

#### Input Parameters
* `instanceGroup` - _required_ - The name of the instance group where the named ports are updated.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone where the instance group is located.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of instances contained within the specified zone.

*Tags:* `instances`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates an instance resource in the specified project using the data included in the request.

*Tags:* `instances`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `sourceInstanceTemplate` - _optional_ - Specifies instance template to create the instance.

This field is optional. It can be a full or partial URL. For example, the following are all valid URLs to an instance template:  
- https://www.googleapis.com/compute/v1/projects/project/global/instanceTemplates/instanceTemplate 
- projects/project/global/instanceTemplates/instanceTemplate 
- global/instanceTemplates/instanceTemplate
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified Instance resource. For more information, see Stopping or Deleting an Instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified Instance resource. Gets a list of available instances by making a list() request.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance resource to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds an access config to an instance's network interface.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - The instance name for this request.
* `networkInterface` - _required_ - The name of the network interface to add to this instance.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Attaches an existing Disk resource to an instance. You must first create the disk before you can attach it. It is not possible to create and attach a disk at the same time. For more information, read Adding a persistent disk to your instance.

*Tags:* `instances`

#### Input Parameters
* `forceAttach` - _optional_ - Whether to force attach the disk even if it's currently attached to another instance.
* `instance` - _required_ - The instance name for this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes an access config from an instance's network interface.

*Tags:* `instances`

#### Input Parameters
* `accessConfig` - _required_ - The name of the access config to delete.
* `instance` - _required_ - The instance name for this request.
* `networkInterface` - _required_ - The name of the network interface.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Detaches a disk from an instance.

*Tags:* `instances`

#### Input Parameters
* `deviceName` - _required_ - The device name of the disk to detach. Make a get() request on the instance to view currently attached disks and device names.
* `instance` - _required_ - Instance name for this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of referrers to instances contained within the specified zone. For more information, read Viewing Referrers to VM Instances.

*Tags:* `instances`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `instance` - _required_ - Name of the target instance scoping this request, or '-' if the request should span over all instances in the container.
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.

### Performs a reset on the instance. This is a hard reset the VM does not do a graceful shutdown. For more information, see Resetting an instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the last 1 MB of serial port output from the specified instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `port` - _optional_ - Specifies which COM or serial port to retrieve data from.
* `project` - _required_ - Project ID for this request.
* `start` - _optional_ - Returns output starting from a specific byte position. Use this to page through output when the output is too large to return in a single request. For the initial request, leave this field unspecified. For subsequent calls, this field should be set to the next value returned in the previous call.
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the auto-delete flag for a disk attached to an instance.

*Tags:* `instances`

#### Input Parameters
* `autoDelete` - _required_ - Whether to auto-delete the disk when the instance is deleted.
* `deviceName` - _required_ - The device name of the disk to modify. Make a get() request on the instance to view currently attached disks and device names.
* `instance` - _required_ - The instance name for this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets labels on an instance. To learn more about labels, read the Labeling Resources documentation.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the number and/or type of accelerator for a stopped instance to the values specified in the request.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the machine type for a stopped instance to the machine type specified in the request.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets metadata for the specified instance to the data included in the request.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Changes the minimum CPU platform that this instance should use. This method can only be called on a stopped instance. For more information, read Specifying a Minimum CPU Platform.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets an instance's scheduling options.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Instance name for this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the service account on the instance. For more information, read Changing the service account and access scopes for an instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance resource to start.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets network tags for the specified instance to the data included in the request.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Simulates a maintenance event on the instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance scoping this request.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Starts an instance that was stopped using the instances().stop method. For more information, see Restart an instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance resource to start.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Starts an instance that was stopped using the instances().stop method. For more information, see Restart an instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance resource to start.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Stops a running instance, shutting it down cleanly, and allows you to restart the instance at a later time. Stopped instances do not incur VM usage charges while they are stopped. However, resources that the VM is using, such as persistent disks and static IP addresses, will continue to be charged until they are deleted. For more information, see Stopping an instance.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - Name of the instance resource to stop.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the specified access config from an instance's network interface with the data included in the request. This method supports PATCH semantics and uses the JSON merge patch format and processing rules.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - The instance name for this request.
* `networkInterface` - _required_ - The name of the network interface where the access config is attached.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates an instance's network interface. This method follows PATCH semantics.

*Tags:* `instances`

#### Input Parameters
* `instance` - _required_ - The instance name for this request.
* `networkInterface` - _required_ - The name of the network interface to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `instances`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets deletion protection on the instance.

*Tags:* `instances`

#### Input Parameters
* `deletionProtection` - _optional_ - Whether the resource should be protected against deletion.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `instances`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `instances`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of machine types available to the specified project.

*Tags:* `machineTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified machine type. Gets a list of available machine types by making a list() request.

*Tags:* `machineTypes`

#### Input Parameters
* `machineType` - _required_ - Name of the machine type to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of node groups available to the specified project. Note: use nodeGroups.listNodes for more details about each group.

*Tags:* `nodeGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a NodeGroup resource in the specified project using the data included in the request.

*Tags:* `nodeGroups`

#### Input Parameters
* `initialNodeCount` - _required_ - Initial count of nodes in the node group.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified NodeGroup resource.

*Tags:* `nodeGroups`

#### Input Parameters
* `nodeGroup` - _required_ - Name of the NodeGroup resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified NodeGroup. Get a list of available NodeGroups by making a list() request. Note: the "nodes" field should not be used. Use nodeGroups.listNodes instead.

*Tags:* `nodeGroups`

#### Input Parameters
* `nodeGroup` - _required_ - Name of the node group to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds specified number of nodes to the node group.

*Tags:* `nodeGroups`

#### Input Parameters
* `nodeGroup` - _required_ - Name of the NodeGroup resource.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes specified nodes from the node group.

*Tags:* `nodeGroups`

#### Input Parameters
* `nodeGroup` - _required_ - Name of the NodeGroup resource to delete.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists nodes in the node group.

*Tags:* `nodeGroups`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `nodeGroup` - _required_ - Name of the NodeGroup resource whose nodes you want to list.
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.

### Updates the node template of the node group.

*Tags:* `nodeGroups`

#### Input Parameters
* `nodeGroup` - _required_ - Name of the NodeGroup resource to update.
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - The name of the zone for this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the access control policy for a resource. May be empty if no such policy or resource exists.

*Tags:* `nodeGroups`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the access control policy on the specified resource. Replaces any existing policy.

*Tags:* `nodeGroups`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns permissions that a caller has on the specified resource.

*Tags:* `nodeGroups`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `resource` - _required_ - Name or id of the resource for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of node types available to the specified project.

*Tags:* `nodeTypes`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified node type. Gets a list of available node types by making a list() request.

*Tags:* `nodeTypes`

#### Input Parameters
* `nodeType` - _required_ - Name of the node type to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - The name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of Operation resources contained within the specified zone.

*Tags:* `zoneOperations`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - Name of the zone for request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified zone-specific Operations resource.

*Tags:* `zoneOperations`

#### Input Parameters
* `operation` - _required_ - Name of the Operations resource to delete.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - Name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the specified zone-specific Operations resource.

*Tags:* `zoneOperations`

#### Input Parameters
* `operation` - _required_ - Name of the Operations resource to return.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - Name of the zone for this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of TargetInstance resources available to the specified project and zone.

*Tags:* `targetInstances`

#### Input Parameters
* `filter` - _optional_ - A filter expression that filters resources listed in the response. The expression must specify the field name, a comparison operator, and the value that you want to use for filtering. The value must be a string, a number, or a boolean. The comparison operator must be either =, !=, >, or <.

For example, if you are filtering Compute Engine instances, you can exclude instances named example-instance by specifying name != example-instance.

You can also filter nested fields. For example, you could specify scheduling.automaticRestart = false to include instances only if they are not scheduled for automatic restarts. You can use filtering on nested fields to filter based on resource labels.

To filter on multiple expressions, provide each separate expression within parentheses. For example, (scheduling.automaticRestart = true) (cpuPlatform = "Intel Skylake"). By default, each expression is an AND expression. However, you can include AND and OR expressions explicitly. For example, (cpuPlatform = "Intel Skylake") OR (cpuPlatform = "Intel Broadwell") AND (scheduling.automaticRestart = true).
* `maxResults` - _optional_ - The maximum number of results per page that should be returned. If the number of available results is larger than maxResults, Compute Engine returns a nextPageToken that can be used to get the next page of results in subsequent list requests. Acceptable values are 0 to 500, inclusive. (Default: 500)
* `orderBy` - _optional_ - Sorts list results by a certain order. By default, results are returned in alphanumerical order based on the resource name.

You can also sort results in descending order based on the creation timestamp using orderBy="creationTimestamp desc". This sorts results based on the creationTimestamp field in reverse chronological order (newest result first). Use this to sort resources like operations so that the newest operation is returned first.

Currently, only sorting by name or creationTimestamp desc is supported.
* `pageToken` - _optional_ - Specifies a page token to use. Set pageToken to the nextPageToken returned by a previous list request to get the next page of results.
* `project` - _required_ - Project ID for this request.
* `zone` - _required_ - Name of the zone scoping this request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a TargetInstance resource in the specified project and zone using the data included in the request.

*Tags:* `targetInstances`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `zone` - _required_ - Name of the zone scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes the specified TargetInstance resource.

*Tags:* `targetInstances`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `requestId` - _optional_ - An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).
* `targetInstance` - _required_ - Name of the TargetInstance resource to delete.
* `zone` - _required_ - Name of the zone scoping this request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns the specified TargetInstance resource. Gets a list of available target instances by making a list() request.

*Tags:* `targetInstances`

#### Input Parameters
* `project` - _required_ - Project ID for this request.
* `targetInstance` - _required_ - Name of the TargetInstance resource to return.
* `zone` - _required_ - Name of the zone scoping this request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-compute-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
