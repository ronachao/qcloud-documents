## 功能描述

本接口用于删除投递配置。

## 请求

### 请求行

```
DELETE /deliverfunction
```

### 请求示例

```
DELETE /deliverfunction?topic_id=xxxx-xx-xx-xx-xxxxxxxx HTTP/1.1
Host: <Region>.cls.myqcloud.com
Authorization: <AuthorizationString>
```

### 请求头

无特殊。

### 请求参数

| 字段名        |  类型  | 位置  | 是否必须 |      含义                       |
|--------------|--------|------|---------|--------------------------------|
| topic_id   | string | query| 是      | 待删除投递的 topic_id              |

## 响应

### 响应示例

```
HTTP/1.1 200 OK
Content-Length: 0
```

### 响应头

无特殊。

### 响应参数

无。

## 错误码

参见 [错误码](https://cloud.tencent.com/document/product/614/12402)。

