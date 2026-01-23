[comment]: <> "Aadhaar Schema Documentation"

# Aadhaar Schema for Farmers

This document describes the Aadhaar-related schema used for farmer identification and verification, including personal details and verification metadata. All sensitive identifiers are stored and processed in hashed or derived form to ensure data privacy and security.

---

## aadhaar_number_hash

`aadhaar_number_hash` represents the hashed value of the Aadhaar number. The original Aadhaar number must never be stored or transmitted in plain text.

```json
"aadhaar_number_hash": "e3b0c44298fc1c149afbf4c8996fb924a27ae41e4649b934ca495991b7852b855"
```

## personal_details

`personal_details` contains basic demographic information of the applicant obtained during Aadhaar-based verification.

### personal_details.first_name

The applicant's first name as per Aadhaar records.

```json
"personal_details": {
  "first_name": "Ramesh"
}
```

### personal_details.last_name

The applicant's last name as per Aadhaar records.

```json
"personal_details": {
  "last_name": "Kumar"
}
```

### personal_details.dob

The applicant's date of birth. The value should follow the ISO 8601 date format (`YYYY-MM-DD`).

```json
"personal_details": {
  "dob": "1985-07-21"
}
```

### personal_details.gender

The applicant's gender as recorded in Aadhaar.

```json
"personal_details": {
  "gender": "Male"
}
```

### personal_details.address

`address` is an object containing the applicant's address details as per Aadhaar records.

```json
"personal_details": {
  "address": {
    "house": "12-3A",
    "street": "MG Road",
    "village": "Rampur",
    "district": "Varanasi",
    "state": "Uttar Pradesh",
    "pincode": "221001"
  }
}
```

---

## metadata

`metadata` contains system-level information related to Aadhaar verification.

### metadata.verification_source

Indicates the source or mechanism used to perform Aadhaar verification.

Example values include:

- `UIDAI`
- `Offline eKYC`
- `Registered Authentication Service Provider`

```json
"metadata": {
  "verification_source": "UIDAI"
}
```
