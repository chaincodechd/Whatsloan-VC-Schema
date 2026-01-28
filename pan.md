[comment]: <> "PAN Schema Documentation"

# PAN Schema for Farmers

This document describes the Permanent Account Number (PAN) schema used for farmer identification and verification.

---

## pan_number

`pan_number` represents the Permanent Account Number.

```json
"pan_number": "ABCDE1234F"
```

## pan_name

`pan_name` is the full name of the applicant as per PAN records.

```json
"pan_name": "Ramesh Kumar"
```

## date_of_birth

`date_of_birth` is the applicant's date of birth as per PAN records. The value should follow the ISO 8601 date format (`YYYYMMDD`).

```json
"date_of_birth": 19850721
```

## name_match_percentage

`name_match_percentage` indicates the percentage match between a provided name and the name on the PAN card.

```json
"name_match_percentage": 95
```
