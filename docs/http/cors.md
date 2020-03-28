---
id: cors
title: CORS
---

Cross-Origin Resource Sharing (CORS) is a mechanism that uses additional HTTP headers to tell browsers to give a web application running at one origin, access to selected resources from a different origin. A web application executes a cross-origin HTTP request when it requests a resource that has a different origin (domain, protocol, or port) from its own.

CORS（跨域资源共享）: 用额外的http headers告诉浏览器, 给予运行在某个origin的app权限，让其访问位于另一个orgin的资源。这样发送的请求叫做跨域请求。

处于安全原因，浏览器限制了从脚本中发起的跨域请求，因此网页APP只能访问同一origin的资源，除非另一个origin的服务器response包含了正确的跨域header。

![cors principle](assets/cors-principle.png)