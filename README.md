## Spring Boot Microservice 2 - Transaction Service

### Endepoints

#### 1 - Save Transaction
```
POST /api/transaction HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password) 
Content-Type: application/json
Cookie: JSESSIONID=F610B952DAF296B7EAF3D556D0153138
Content-Length: 37

{
    "userId":1,
    "productId":1
}
```

#### 2 - Get Transaction Of User
```
GET /api/transaction/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)
```

#### 3 - Delete Transaction By Id
```
DELETE /api/transaction/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)
```
