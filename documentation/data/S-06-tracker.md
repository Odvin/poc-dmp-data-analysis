# Tracker entity data

## State code **S-06**

| activity_id | company_id | created_at | progress | status  |
| ----------- | ---------- | ---------- | -------- | ------- |
| ac-01       | cm-y01     | 2023-01-01 | 0        | Planned |
| ac-02       | cm-y02     | 2023-01-01 | 0        | Planned |
| ac-03       | cm-y01     | 2023-01-01 | 0        | Planned |
| ac-04       | cm-y02     | 2023-01-01 | 0        | Planned |
| ac-05       | cm-y01     | 2023-01-01 | 0        | Planned |
| ac-06       | cm-y02     | 2023-01-01 | 0        | Planned |

### Creation payload

**CAPACITY_STATUS_TYPE**

- Active
- Complied
- Pause
- Planned
- Failed

```json
{
  "activity_id": "ac-01",
  "company_id": "cm-y01",
  "created_at": "2023-01-06",
  "status": "Active",
  "progress": "52"
}
```

# Capacity

![Project capacity](../infographics/C-01-capacity-01.svg 'Company capacity for the project')

# 2023-01-01

![Tracker](../infographics/S-06-tracker-00.svg 'Project tracker')

![Job assignment](../infographics/S-06-tracker-00a-00.svg 'Job assignment')

| Company     | contract | allocation |
| ----------- | -------- | ---------- |
| Cyber Crone | 60%      | 46%        |
| Palantir    | 40%      | 54%        |

![Job assignment](../infographics/S-06-tracker-00a-01.svg 'Job assignment')

| Company     | contract | allocation |
| ----------- | -------- | ---------- |
| Cyber Crone | 60%      | 28%        |
| Palantir    | 40%      | 72%        |

![Company selection](../infographics/S-06-company-selection-ex01.svg 'Companies')

![Distribution selection](../infographics/S-06-distribution-selection-ex01.svg 'Distributions')

# 2023-01-06

| activity_id | company_id | created_at | progress | status   |
| ----------- | ---------- | ---------- | -------- | -------- |
| ac-01       | cm-y01     | 2023-01-01 | 0        | Planned  |
| ac-02       | cm-y02     | 2023-01-01 | 0        | Planned  |
| ac-03       | cm-y01     | 2023-01-01 | 0        | Planned  |
| ac-04       | cm-y02     | 2023-01-01 | 0        | Planned  |
| ac-05       | cm-y01     | 2023-01-01 | 0        | Planned  |
| ac-06       | cm-y02     | 2023-01-01 | 0        | Planned  |
| ac-01       | cm-y01     | 2023-01-06 | 52       | Active   |
| ac-01       | cm-y01     | 2023-01-14 | 100      | Complied |

![Tracker](../infographics/S-06-tracker-01.svg 'Project tracker')

# 2023-01-17

| activity_id | company_id | created_at | progress | status   |
| ----------- | ---------- | ---------- | -------- | -------- |
| ac-01       | cm-y01     | 2023-01-06 | 52       | Active   |
| ac-01       | cm-y01     | 2023-01-14 | 100      | Complied |
| ac-02       | cm-y02     | 2023-01-17 | 15       | Active   |

![Tracker](../infographics/S-06-tracker-02.svg 'Project tracker')
