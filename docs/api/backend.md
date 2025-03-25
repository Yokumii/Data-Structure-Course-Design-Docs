# 后端API文档

## 景点接口
### GET /api/attractions
**请求参数**:
```http
GET /api/attractions?page=1&size=10 HTTP/1.1
```

**响应示例**:
```json
{
  "data": [
    {
      "id": 1,
      "name": "颐和园",
      "rating": 4.8
    }
  ]
}
```