# Field Extraction Notes

## 1. Objective
To ensure important fields from logs are correctly extracted and searchable in the SIEM.

---

## 2. Key Fields Extracted

- source_ip
- destination_ip
- username
- event_id
- timestamp
- action (success/failure)
- severity

---

## 3. Extraction Method

- Used default field extraction provided by SIEM.
- Verified field mapping during log ingestion.
- Created custom field extraction where required.

---

## 4. Validation

- Searched logs using extracted fields.
- Confirmed correct values are displayed.
- Ensured no missing or incorrectly parsed fields.

---

## 5. Status
Field extraction completed successfully and ready for alert rule creation.
