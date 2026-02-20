[comment]: <> "Voter Schema Documentation"

# Voter Schema for Farmers

This document describes the Voter ID schema used for farmer identification and verification.

---

## voter_number

`voter_number` represents the Voter ID Number.

```json
"voter_number": "XYZ1234567"
```

## epic_number

`epic_number` represents the Electoral Photo Identity Card (EPIC) Number.

```json
"epic_number": "ABC1234567"
```

## voter_name

`voter_name` is the full name of the applicant as per Voter ID records.

```json
"voter_name": "Ramesh Kumar"
```

## age

`age` is the applicant's age as recorded in Voter ID.

```json
"age": 38
```

## date_of_birth

`date_of_birth` is the applicant's date of birth as per Voter ID records. The value should follow the ISO 8601 date format (`YYYYMMDD`).

```json
"date_of_birth": 19850721
```

## gender

`gender` is the applicant's gender as recorded in Voter ID.

```json
"gender": "Male"
```

## relative_name

`relative_name` is the name of the applicant's father, mother, or husband as per Voter ID records.

```json
"relative_name": "Suresh Kumar"
```

## house_no

`house_no` is the house number as per Voter ID records.

```json
"house_no": "12-3A"
```

## polling_station

`polling_station` is the polling station as per Voter ID records.

```json
"polling_station": "Primary School, Ward 5"
```

## police_station

`police_station` is the police station jurisdiction as per Voter ID records.

```json
"police_station": "Varanasi Cantt"
```

## constituency

`constituency` is the electoral constituency as per Voter ID records.

```json
"constituency": "Varanasi North"
```

## district

`district` is the district as per Voter ID records.

```json
"district": "Varanasi"
```

## state

`state` is the state as per Voter ID records.

```json
"state": "Uttar Pradesh"
```

## name_match_percentage

`name_match_percentage` indicates the percentage match between a provided name and the name on the PAN card.

```json
"name_match_percentage": 95
```
