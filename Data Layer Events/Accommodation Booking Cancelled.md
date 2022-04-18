# Accommodation Booking Cancelled

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Accommodation Booking Cancelled",
    "booking": {
        "roomList": [
            {
                "location": {
                    "locationId": "<locationId>"
                },
                "room": {
                    "typeCode": "<typeCode>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|booking.roomList[n].location.locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
|booking.roomList[n].room.typeCode|string|A code describing the room features. Often indicates number of beds, smoking or non-smoking, ADA accessibility and so on.|1-K-NS, 2-Q-S, S-K-NS-City|||||||




