# Capacity entity data

## State code **C-01**

| company_id | project_id | job_id | amount | status     | actual_at  | created_at | description            |
| ---------- | ---------- | ------ | ------ | ---------- | ---------- | ---------- | ---------------------- |
| cm-y01     | pr-a01     | jb-a01 | 12     | Possible   | 2023-01-01 | 2023-01-01 | Helicopter required    |
| cm-y01     | pr-a01     | jb-a03 | 10     | Difficult  | 2023-01-20 | 2023-05-01 | Weather condition      |
| cm-y01     | pr-a01     | jb-a03 | 10     | Preferably | 2023-01-20 | 2023-05-10 |                        |
| cm-y01     | pr-a01     | jb-a05 | 13     | Preferably | 2023-02-01 | 2023-01-01 |                        |
| cm-y02     | pr-a01     | jb-a01 | 10     | Preferably | 2023-01-01 | 2023-01-01 |                        |
| cm-y02     | pr-a01     | jb-a02 | 12     | Possible   | 2023-01-14 | 2023-01-01 |                        |
| cm-y02     | pr-a01     | jb-a04 | 11     | Possible   | 2023-01-30 | 2023-01-01 | Accreditation missed   |
| cm-y02     | pr-a01     | jb-a04 | 11     | Possible   | 2023-01-30 | 2023-01-20 | Accreditation received |
| cm-y02     | pr-a01     | jb-a06 | 8      | Difficult  | 2023-02-14 | 2023-01-01 |                        |

### Creation payload

**CAPACITY_STATUS_TYPE**

- Preferably
- Possible
- Difficult
- Rejected

```json
{
  "company_id": "cm-y01",
  "project_id": "pr-a01",
  "job_id": "jb-a01",
  "amount": 5,
  "status": "Possible",
  "actual_at": "2023-01-01",
  "created_at": "2023-03-01",
  "description": "Helicopter required"
}
```

![Project capacity](../infographics/C-01-capacity-01.svg 'Company capacity for the project')
