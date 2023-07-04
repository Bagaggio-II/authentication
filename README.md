# Documentation API
---

# Authentication

| Função        | Método | Endpoint       |           
| --------------| ------ | -------------- |
| **getToken**     | POST   | `api/auth`    |

| Campo               | Tipo                         |
| --------------------| ---------------------------- |
| **company_access**     | string(required)          |

#### Example

```json
    POST
```

Request:
```json
{
	"company_access": "TESTE"
}
  
```
Response:
```json
{
	"company": "TESTE",
	"token": "eyJhbGciOiJIUzs1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MywiaWF0IjoxNjg4vDgxNzEzLCJleHAiOjE3MTcyODE3MTN9.Xqr1NTaqDtqQ_bY4Y5HCPTmpwxMDe_oagrRwyfmIINU"
}
```
---
