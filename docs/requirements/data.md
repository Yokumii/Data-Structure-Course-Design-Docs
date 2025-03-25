# 数据规范

## 1. 数据库表结构
### attractions 表
| 字段 | 类型 | 说明 |
|------|------|------|
| id | BIGINT | 主键 |
| name | VARCHAR(100) | 景点名称 |
| location | POINT | 经纬度坐标 |

## 2. 图数据结构
```json
{
  "nodes": [
    {"id": 1, "name": "北邮西门"},
    {"id": 2, "name": "图书馆"}
  ],
  "edges": [
    {"source": 1, "target": 2, "distance": 500}
  ]
}
```