# GCHA User Acceptance Testing (UAT) Checklist

| Requirement ID | Test Scenario | User Role | Pass/Fail Criteria |
| :--- | :--- | :--- | :--- |
| UAT-001 | Nurse logs in and registers a new patient profile. | Ward Nurse | **PASS:** Registration is completed and saved to the Cairo database in < 30 seconds. |
| UAT-002 | Doctor enters new vitals and requests an AI risk score. | Lead Doctor | **PASS:** AI Heart Alert is received and displayed correctly in < 5 seconds. |
| UAT-003 | System handles network loss during data entry. | Mobile User | **PASS:** Data is cached locally and syncs automatically without data loss when connection returns. |
