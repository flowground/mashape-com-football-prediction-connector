# ![LOGO](logo.png) Football Prediction **flow**ground Connector

## Description

A generated **flow**ground connector for the Football Prediction API (version 2).

Generated from: https://api.apis.guru/v2/specs/mashape.com/football-prediction/2/openapi.json<br/>
Generated at: 2019-05-07T17:42:56+03:00

## API Description

The Football Prediction API allows developers to get predictions for upcoming football (soccer) matches, results for past matches, and performance monitoring for statistical models.

## Authorization

This API does not require authorization.

## Actions

### Returns an array of all the available federations.

#### Input Parameters
* `X-Mashape-Key` - _optional_ - Your key obtained from https://boggio-analytics.com/fp-api/

### Returns an array of all the supported prediction markets

#### Input Parameters
* `X-Mashape-Key` - _optional_ - Your key obtained from https://boggio-analytics.com/fp-api/

### Returns predictions accuracy in the last 1, 7, 14, 30 days.

#### Input Parameters
* `X-Mashape-Key` - _optional_ - Your key obtained from https://boggio-analytics.com/fp-api/

### This endpoint returns by default the next non-expired football predictions. URL parameters can be specified to show specific date in the past or future or to filter by federation and prediction market name.

#### Input Parameters
* `X-Mashape-Key` - _optional_ - Your key obtained from https://boggio-analytics.com/fp-api/

### Returns all predictions available for a match id.

#### Input Parameters
* `id` - _required_ - ID of match

## License

**flow**ground :- Telekom iPaaS / mashape-com-football-prediction-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
