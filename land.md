[comment]: <> "Land Schema Documentation"

# Land Schema

This document describes the Land schema used for verifying land ownership and parcel details.

---

## land_parcel_id

`land_parcel_id` represents the Unique Survey Number or ULPIN (Unique Land Parcel Identification Number).

```json
"land_parcel_id": "ULPIN123456"
```

## ownership_details

`ownership_details` contains information about the owner of the land.

### ownership_details.owner_name

The name of the owner as it appears on the title deed.

```json
"ownership_details": {
  "owner_name": "Ramesh Kumar"
}
```

### ownership_details.owner_relation

The relationship of the owner to the applicant (e.g., Self, Spouse, Parent).

```json
"ownership_details": {
  "owner_relation": "Self"
}
```

### ownership_details.share_percentage

The percentage of ownership share held by the individual (0-100%).

```json
"ownership_details": {
  "share_percentage": 100.0
}
```

## parcel_details

`parcel_details` contains specific details about the land parcel.

### parcel_details.survey_number

The official survey number of the land parcel.

```json
"parcel_details": {
  "survey_number": "123/A"
}
```

### parcel_details.total_area_acres

The total area of the land parcel in acres.

```json
"parcel_details": {
  "total_area_acres": 2.5
}
```

### parcel_details.land_type

The type of land (e.g., Irrigated, Rainfed, Dry).

```json
"parcel_details": {
  "land_type": "Irrigated"
}
```

## legal_status

`legal_status` contains information regarding the legal standing of the land.

### legal_status.is_disputed

Indicates whether the land is currently under litigation or dispute.

```json
"legal_status": {
  "is_disputed": false
}
```
