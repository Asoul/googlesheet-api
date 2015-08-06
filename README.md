# googlesheet-api
A simple example for retrieve google sheet via Vanillajs

## Demo

[Demo Page](http://asoul.github.io/googlesheet-api/)

## Usage

1. Create a Google Sheet

2. Publish it

3. Get the sheet key

4. Retrieve data via javascript

## Note

1. You don't have to share the sheet and can also pulish it.

## Example URL

- [Google Doc Sheet](https://docs.google.com/spreadsheets/d/1Q9zlHuTw9Bvzu6DJNQt4BgJqMmSUjLHbYmFv63koeJg)

- [Publish Sheet](https://docs.google.com/spreadsheets/d/1Q9zlHuTw9Bvzu6DJNQt4BgJqMmSUjLHbYmFv63koeJg/pubhtml)

- [JSON Response](https://spreadsheets.google.com/feeds/list/1Q9zlHuTw9Bvzu6DJNQt4BgJqMmSUjLHbYmFv63koeJg/od6/public/values?alt=json)

- [XML Response](https://spreadsheets.google.com/feeds/list/1Q9zlHuTw9Bvzu6DJNQt4BgJqMmSUjLHbYmFv63koeJg/od6/public/values)

## Syntax

```
GET https://spreadsheets.google.com/feeds/list/key/worksheetId/private/basic
```

where `key` is `1Q9zlHuTw9Bvzu6DJNQt4BgJqMmSUjLHbYmFv63koeJg`

For example,

### JSON Format

```
GET https://spreadsheets.google.com/feeds/list/1Q9zlHuTw9Bvzu6DJNQt4BgJqMmSUjLHbYmFv63koeJg/od6/public/values?alt=json
```

### XML Format

```
GET https://spreadsheets.google.com/feeds/list/1Q9zlHuTw9Bvzu6DJNQt4BgJqMmSUjLHbYmFv63koeJg/od6/public/values
```

More detail: [See Goggle Sheets API](https://developers.google.com/google-apps/spreadsheets/)

### License

See file LICENSE for more info.