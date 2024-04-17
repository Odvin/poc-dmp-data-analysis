# DynamoDB Schemas

## Site Tracker options (SiteTracker table)

### Company profile schema

| Attribute | Key | Pattern     |        Example | Type | Description           | Null |
| :-------- | :-: | :---------- | -------------: | :--: | :-------------------- | :--: |
| PK        | PK  | uuid        | 32 hexadecimal |  S   | UUID of the company   |  -   |
| SK        | SK  | profile     |        profile |  S   | Constant value for SK |  -   |
| title     |     | varchar(50) |    Cyber Crone |  S   | Company title         |  -   |
| country   |     | char(2)     |             US |  S   | Country ISO A-2 code  |  -   |
| rating    |     | dd          |             86 |  N   | Company rating score  |  -   |

#### Facets

- GetCompanyProfile `(uuid, profile) => {companyProfile}`
