---
# Code generated by logshare-api. DO NOT EDIT.

title: Sinkhole HTTP Logs
pcx_content_type: configuration
weight: 21
---

# Sinkhole HTTP Logs

The descriptions below detail the fields available for `sinkhole_http_logs`.

{{<table-wrap>}}

| Field | Value | Type |
| -- | -- | -- |
| AccountID | The Account ID. | string |
| Body | The request body. | string |
| BodyLength | The length of request body. | int |
| DestAddr | The destination IP address of the request. | string |
| Headers | The request headers. If a header has multiple values, the values are comma separated. Each header is separated by the escaped newline character (\n). | string |
| Host | The host the request was sent to. | string |
| Method | The request method. | string |
| Password | The request password. | string |
| R2Path | The path to the object within the R2 bucket linked to this sinkhole that stores overflow body and header data. Blank if neither headers nor body was larger than 256 bytes. | string |
| Referrer | The referrer of the request. | string |
| SinkholeID | The ID of the Sinkhole that logged the HTTP Request. | string |
| SrcAddr | The sender's IP address. | string |
| Timestamp | The date and time the sinkhole HTTP request was logged. | int or string |
| URI | The request Uniform Resource Identifier. | string |
| URL | The request Uniform Resource Locator. | string |
| UserAgent | The request user agent. | string |
| Username | The request username. | string |

{{</table-wrap>}}