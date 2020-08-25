# ![LOGO](logo.png) Asset Stack API **flow**ground Connector

## Description

A generated **flow**ground connector for the Asset Stack API API (version v1).

Generated from: /localization/api/v1<br/>
Generated at: 2020-08-25T13:35:32+00:00

## API Description

<br/>

## Authorization

Supported authorization schemes:
- OAuth2 - Please enter JWT with Bearer into field

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get all area types

*Tags:* `Area Types`

#### Input Parameters
* `page` - _optional_ - Page number<br/>
* `numberOfItems` - _optional_ - Number of items per page<br/>

### Create area type

*Tags:* `Area Types`

### Get area type

*Tags:* `Area Types`

#### Input Parameters
* `type` - _required_ - Area type<br/>

### Update area type

*Tags:* `Area Types`

#### Input Parameters
* `type` - _required_ - Area type<br/>

### Delete area type

*Tags:* `Area Types`

#### Input Parameters
* `type` - _required_ - Area type<br/>

### Patch area type

*Tags:* `Area Types`

#### Input Parameters
* `type` - _required_ - Area type<br/>

### Get all areas

*Tags:* `Areas`

#### Input Parameters
* `query` - _optional_ - Search query<br/>
* `types` - _optional_ - Area types<br/>
* `coordinateSystems` - _optional_ - Coordinate system ids<br/>
* `fromDateTime` - _optional_ - Start point of date time to query from<br/>
* `toDateTime` - _optional_ - End point of date time to query to<br/>
* `latestData` - _optional_ - Flag to return latest data<br/>
* `names` - _optional_ - Query based on area names<br/>
* `page` - _optional_ - Page number<br/>
* `numberOfItems` - _optional_ - Number of items per page<br/>

### Create area

*Tags:* `Areas`

### Get area by id

*Tags:* `Areas`

#### Input Parameters
* `areaId` - _required_ - Area id<br/>
* `query` - _optional_ - Search query<br/>
* `fromDateTime` - _optional_ - Start point of date time to query from<br/>
* `toDateTime` - _optional_ - End point of date time to query to<br/>
* `latestData` - _optional_ - Flag to return latest data<br/>

### Update area

*Tags:* `Areas`

#### Input Parameters
* `areaId` - _required_ - Area id<br/>

### Patch area

*Tags:* `Areas`

#### Input Parameters
* `areaId` - _required_ - Area id<br/>

### Delete area

*Tags:* `Areas`

#### Input Parameters
* `areaId` - _required_ - Area id<br/>

### Get all asset types

*Tags:* `Asset Types`

#### Input Parameters
* `page` - _optional_ - Page number<br/>
* `numberOfItems` - _optional_ - Number of items per page<br/>

### Create asset type

*Tags:* `Asset Types`

### Get asset type

*Tags:* `Asset Types`

#### Input Parameters
* `type` - _required_ - Asset type<br/>

### Update asset type

*Tags:* `Asset Types`

#### Input Parameters
* `type` - _required_ - Asset type<br/>

### Delete asset type

*Tags:* `Asset Types`

#### Input Parameters
* `type` - _required_ - Asset type<br/>

### Patch asset type

*Tags:* `Asset Types`

#### Input Parameters
* `type` - _required_ - Asset type<br/>

### Get assets

*Tags:* `Assets`

#### Input Parameters
* `query` - _optional_ - Search query<br/>
* `types` - _optional_ - Asset types<br/>
* `coordinateSystems` - _optional_ - Coordinate system ids<br/>
* `fromDateTime` - _optional_ - Start point of date time to query from<br/>
* `toDateTime` - _optional_ - End point of date time to query to<br/>
* `latestData` - _optional_ - Flag to return latest data<br/>
* `names` - _optional_ - Query based on asset names<br/>
* `filter` - _optional_ - List of properties included in payload<br/>
* `page` - _optional_ - Page number<br/>
* `numberOfItems` - _optional_ - Number of items per page<br/>

### Create asset

*Tags:* `Assets`

### Get asset by id

*Tags:* `Assets`

#### Input Parameters
* `assetId` - _required_ - Asset id<br/>
* `query` - _optional_ - Search query<br/>
* `coordinateSystems` - _optional_ - Coordinate system ids<br/>
* `fromDateTime` - _optional_ - Start point of date time to query from<br/>
* `toDateTime` - _optional_ - End point of date time to query to<br/>
* `latestData` - _optional_ - Flag to return latest data<br/>
* `filter` - _optional_ - List of properties included in payload<br/>

### Update asset

*Tags:* `Assets`

#### Input Parameters
* `assetId` - _required_ - Asset id<br/>

### Patch asset

*Tags:* `Assets`

#### Input Parameters
* `assetId` - _required_ - Asset id<br/>

### Delete asset

*Tags:* `Assets`

#### Input Parameters
* `assetId` - _required_ - Asset id<br/>

### Get local coordinate systems

*Tags:* `Coordinate Systems`

#### Input Parameters
* `page` - _optional_ - Page number<br/>
* `numberOfItems` - _optional_ - Number of items per page<br/>

### Save coordinate system

*Tags:* `Coordinate Systems`

### Get coordinate system by id

*Tags:* `Coordinate Systems`

#### Input Parameters
* `coordinateSystemId` - _required_ - Coordinate system id<br/>

### Update coordinate system

*Tags:* `Coordinate Systems`

#### Input Parameters
* `coordinateSystemId` - _required_ - Coordinate system id<br/>

### Delete coordinate system

*Tags:* `Coordinate Systems`

#### Input Parameters
* `coordinateSystemId` - _required_ - Coordinate system id<br/>

### Patch coordinate system

*Tags:* `Coordinate Systems`

#### Input Parameters
* `coordinateSystemId` - _required_ - Coordinate system id<br/>

### Get coordinate systems

*Tags:* `Coordinate Systems`

#### Input Parameters
* `page` - _optional_ - Page number<br/>
* `numberOfItems` - _optional_ - Number of items per page<br/>

## License

**flow**ground :- Telekom iPaaS / asset-stack-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
