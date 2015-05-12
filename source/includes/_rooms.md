# Rooms

## Get Room List

```shell
curl "https://app.hotelrunner.com/api/v1/apps/rooms?token={TOKEN}&hr_id={HR_ID}"
```

> The above command returns JSON structured like this:

```json
[

  {
    "code": "HR_1",
    "name": "Standard Room",
    "description": "Standard Room Description",
    "policy": "Standard Room Policy",
    "room_capacity": 3,
    "adult_capacity": 2
  },
  {
    "code": "HR_2",
    "name": "Double Room",
    "description": "Double Room Description",
    "policy": "Double Room Policy",
    "room_capacity": 2,
    "adult_capacity": 2
  }
]
```

This endpoint retrieves all rooms of property.

### HTTP Request

`GET https://app.hotelrunner.com/api/v1/apps/rooms`

## Update Price & Availability

```shell
curl "https://app.hotelrunner.com/api/v1/apps/rooms?token={TOKEN}&hr_id={HR_ID}"
```

> The above command returns JSON structured like this:

```json
[

  {
    "code": "HR_1",
    "name": "Standard Room",
    "description": "Standard Room Description",
    "policy": "Standard Room Policy",
    "room_capacity": 3,
    "adult_capacity": 2
  },
  {
    "code": "HR_2",
    "name": "Double Room",
    "description": "Double Room Description",
    "policy": "Double Room Policy",
    "room_capacity": 2,
    "adult_capacity": 2
  }
]
```

This endpoint retrieves all rooms of property.

### HTTP Request

`GET https://app.hotelrunner.com/api/v1/apps/rooms`