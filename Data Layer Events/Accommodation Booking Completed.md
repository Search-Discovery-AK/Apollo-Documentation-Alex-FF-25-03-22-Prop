# Accommodation Booking Completed

### 

## Javascript Code
```js
window.dataLayerEdited = window.dataLayerEdited || [];
dataLayerEdited.push({
  "event": "Accommodation Booking Completed",
    "booking": {
        "roomList": [
            {
                "location": {
                    "locationId": "<locationId>"
                }
            }
        ],
        "total": {
            "currency": "<currency>"
        },
        "transactionID": "<transactionID>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|booking.roomList[n].location.locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
|booking.total.currency|string|Currency of the payment for the booking. ISO 4217 \(3 character alpha\), uppercase |USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|booking.transactionID|string|Unique identifier of the transaction. Max Length 20. Used as a key for upload of post transaction data. ||^[a-zA-Z0-9]{6,20}$|6|20||||

## Attached Notes

<p>11111</p>
