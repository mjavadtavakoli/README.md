
# HTTP Status Codes

## 🔵 1xx: Informational

| Code | Meaning               | Description                                 |
|------|-----------------------|---------------------------------------------|
| 100  | Continue              | Server ready to receive the rest of the data |
| 101  | Switching Protocols   | Client requested protocol change             |
| 102  | Processing            | Request received, still processing           |

## 🟢 2xx: Success

| Code | Meaning    | Description                                     |
|------|------------|-------------------------------------------------|
| 200  | OK         | Request succeeded                               |
| 201  | Created    | Resource successfully created                   |
| 202  | Accepted   | Request accepted, processing later              |
| 204  | No Content | Successful, no response body                    |

## 🟡 3xx: Redirection

| Code | Meaning            | Description                               |
|------|--------------------|-------------------------------------------|
| 301  | Moved Permanently  | Resource moved permanently                |
| 302  | Found              | Temporary redirect                        |
| 304  | Not Modified       | Cached content still valid                |

## 🔴 4xx: Client Error

| Code | Meaning               | Description                              |
|------|-----------------------|------------------------------------------|
| 400  | Bad Request           | Malformed request                        |
| 401  | Unauthorized          | Authentication required                  |
| 403  | Forbidden             | Not allowed even if authenticated        |
| 404  | Not Found             | Resource not found                       |
| 405  | Method Not Allowed    | HTTP method not allowed                  |
| 409  | Conflict              | Conflict in request (e.g. duplicate)     |
| 422  | Unprocessable Entity  | Validation failed                        |

## 🔴🔴 5xx: Server Error

| Code | Meaning               | Description                              |
|------|-----------------------|------------------------------------------|
| 500  | Internal Server Error | Generic server error                     |
| 501  | Not Implemented       | Method not supported                     |
| 502  | Bad Gateway           | Invalid response from upstream server    |
| 503  | Service Unavailable   | Server temporarily unavailable           |
| 504  | Gateway Timeout       | Upstream server took too long to respond |
