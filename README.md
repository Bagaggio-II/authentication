# Documentation API
---

# Authentication

| Function        | Method | Endpoint       |           
| --------------| ------ | -------------- |
| **getToken**     | POST   | `api/auth`    |

| Field               | Type                         |
| --------------------| ---------------------------- |
| **company_access**     | string(required)          |

#### Example

```json
    POST
```

Request:
```json
{
	"company_access": "9d742dbf-b410-445f-8392-df78a81eebb5"
}
  
```
Response:
```json
{
	"company": "Zend Team",
	"token": "eyJhbGciOiJIUzs1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MywiaWF0IjoxNjg4vDgxNzEzLCJleHAiOjE3MTcyODE3MTN9.Xqr1NTaqDtqQ_bY4Y5HCPTmpwxMDe_oagrRwyfmIINU"
}
```
---
