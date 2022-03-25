# Room Listing Displayed

### 

## Javascript Code
```js
window.dataLayerEdited = window.dataLayerEdited || [];
dataLayerEdited.push({
  "event": "Room Listing Displayed",
    "listingDisplayed": {
        "filterList": "<filterList>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingDisplayed.filterList|string|A twice delimited string of filterType and filterValue pairs.  Use \~ between type and value.  Use \| between pairs|sort\~price ascending\|color\~green\|size\~medium|||||||




