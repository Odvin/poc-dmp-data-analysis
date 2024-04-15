# Job entity data

## State code **S-02**

| id     | project_id | title     | scope   | budget | estimate |
| ------ | ---------- | --------- | ------- | ------ | -------- |
| jb-a01 | pr-a01     | Job X-00A | Inst    | 250    | 14       |
| jb-a02 | pr-a01     | Job X-10B | Inst    | 230    | 15       |
| jb-a03 | pr-a01     | Job Y-10C | Tuning  | 30     | 10       |
| jb-a04 | pr-a01     | Job Y-00D | Tuning  | 100    | 12       |
| jb-a05 | pr-a01     | Job Z-10C | Testing | 350    | 14       |
| jb-a06 | pr-a01     | Job Z-00D | Testing | 420    | 10       |

### Creation payload

**JOB_SCOPE_TYPE**

- Inst
- Tuning
- Testing

```json
{
  "id": "jb-a01",
  "project_id": "pr-a01",
  "title": "Job X-00A",
  "scope": "Inst",
  "budget": 250,
  "estimate": 8
}
```
