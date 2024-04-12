# Tracker entity data

## State code **S-06**

| activity_id | company_id | created_at | progress | status   |
| ----------- | ---------- | ---------- | -------- | -------- |
| ac-01       | cm-y01     | 2023-01-06 | 52       | Active   |
| ac-01       | cm-y01     | 2023-01-14 | 100      | Complied |

### Creation payload

**CAPACITY_STATUS_TYPE**

- Active
- Complied
- Pause
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

# 2023-01-01

![Tracker](../infographics/S-06-tracker-00.svg 'Project tracker')

# 2023-01-06

![Tracker](../infographics/S-06-tracker-01.svg 'Project tracker')
