[comment]: <> "Land Schema Documentation"

# Land Schema

This document describes the Land schema used for verifying land ownership and parcel details.

---

## state_name

`state_name` represents the name of the state where the land is located.

```json
"state_name": "Uttar Pradesh"
```

## state_id

`state_id` represents the unique identifier for the state.

```json
"state_id": 9
```

## district_name

`district_name` represents the name of the district where the land is located.

```json
"district_name": "Varanasi"
```

## district_id

`district_id` represents the unique identifier for the district.

```json
"district_id": 123
```

## tehsil_name

`tehsil_name` represents the name of the tehsil (sub-district) where the land is located.

```json
"tehsil_name": "Sadar"
```

## tehsil_id

`tehsil_id` represents the unique identifier for the tehsil.

```json
"tehsil_id": 456
```

## village_name

`village_name` represents the name of the village where the land is located.

```json
"village_name": "Rampur"
```

## village_id

`village_id` represents the unique identifier for the village.

```json
"village_id": 789
```

## survey_number

`survey_number` represents the official survey number of the land parcel.

```json
"survey_number": "123/A"
```

## sub_survey_number

`sub_survey_number` represents the sub-survey number of the land parcel, if applicable.

```json
"sub_survey_number": "1"
```

## land_owner_name

`land_owner_name` represents the name of the land owner as per official records.

```json
"land_owner_name": "Ramesh Kumar"
```

## ownership_type

`ownership_type` describes the type of ownership (e.g., "Sole", "Joint", "Ancestral").

```json
"ownership_type": "Sole"
```

## owner_share

`owner_share` represents the percentage of ownership share held by the individual (e.g., 100 for 100%).

```json
"owner_share": 100
```

## irrigation_status

`irrigation_status` indicates the irrigation status of the land (e.g., "Irrigated", "Rainfed", "Dry").

```json
"irrigation_status": "Irrigated"
```

## mortgage_status

`mortgage_status` indicates whether the land is currently mortgaged (`true` or `false`).

```json
"mortgage_status": false
```

## court_case

`court_case` indicates whether the land is currently involved in a court case or dispute (`true` or `false`).

```json
"court_case": false
```

## land_area

`land_area` represents the total area of the land parcel in a specified unit (e.g., acres, hectares).

```json
"land_area": 2.5
```

## name_match_percentage

`name_match_percentage` indicates the percentage match between a provided name and the name on the PAN card.

```json
"name_match_percentage": 95
```
