# Activity entity data

## State code **S-05**

| project_id | id    | job_id | country | site   | start_at   | end_at     |
| ---------- | ----- | ------ | ------- | ------ | ---------- | ---------- |
| pr-a01     | ac-01 | jb-a01 | US      | st-c01 | 2023-01-01 | 2023-01-14 |
| pr-a01     | ac-02 | jb-a02 | US      | st-x05 | 2023-01-14 | 2023-01-30 |
| pr-a01     | ac-03 | jb-a03 | US      | st-x01 | 2023-01-20 | 2023-01-30 |
| pr-a01     | ac-04 | jb-a04 | US      | st-x05 | 2023-01-30 | 2023-02-12 |
| pr-a01     | ac-05 | jb-a05 | US      | st-x01 | 2023-02-01 | 2023-02-14 |
| pr-a01     | ac-06 | jb-a06 | US      | st-x05 | 2023-02-14 | 2023-02-24 |

### Creation payload

```json
{
  "id": "ac-01",
  "project_id": "pr-a01",
  "job_id": "jb-a01",
  "country": "US",
  "site": "st-c01",
  "start_at": "2023-01-01",
  "end_at": "2023-01-14"
}
```

![Project activity](../infographics/S-05-activity-init.svg 'Activities initiation')
