# 接口定义

核心 RESTful API：

| 接口 URL          | 方法 | 参数             | 返回示例                          |
|-------------------|------|------------------|-----------------------------------|
| /api/questions    | GET  | page, size       | ```json {"code": 0, "data": [{"question_id": 1000, "title": "正整数的和"}]} ``` |
| /api/question/{id}| GET  | id               | ```json {"code": 0, "data": {"question_id": 1004, "content": "..."}} ``` |
| /api/submit       | POST | question_id, code | ```json {"code": 0, "data": {"status": "Accepted", "time": 50}} ``` |