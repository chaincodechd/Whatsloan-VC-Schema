[comment]: <> "Aadhaar Schema Documentation"

# Aadhaar Schema for Farmers

This document describes the Aadhaar-related schema used for farmer identification and verification, including personal details and verification metadata. All sensitive identifiers are stored and processed in hashed or derived form to ensure data privacy and security.

---

## aadhaar_id

`aadhaar_id` represents the hashed value of the Aadhaar number. The original Aadhaar number must never be stored or transmitted in plain text.

```json
"aadhaar_id": "e3b0c44298fc1c149afbf4c8996fb924a27ae41e4649b934ca495991b7852b855"
```

## aadhaar_name

`aadhaar_name` is the full name of the applicant as per Aadhaar records.

```json
"aadhaar_name": "Ramesh Kumar"
```

## gender

`gender` is the applicant's gender as recorded in Aadhaar.

```json
"gender": "Male"
```

## father_or_husband_name

`father_or_husband_name` is the name of the applicant's father or husband as per Aadhaar records.

```json
"father_or_husband_name": "Suresh Kumar"
```

## date_of_birth

`date_of_birth` is the applicant's date of birth. The value should follow the ISO 8601 date format (`YYYYMMDD`).

```json
"date_of_birth": 19850721
```

## address

`address` is the full address of the applicant as a plain string text, as per Aadhaar records.

```json
"address": "12-3A, MG Road, Rampur, Varanasi, Uttar Pradesh, India, 221001"
```
