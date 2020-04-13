---
id: http/methods
title: methods
---

1. GET 用于获取资源，也应该只获取资源，没有副作用。

2. HEAD 和GET请求一样获取response, 但是response只有headers，没有body

3. POST 提交信息到指定URL，通常会改变服务器状态或者产生副作用。

4. PUT replaces all current representations of the target resource with the request payload.

5. DELETE deletes the specified resource.

6. CONNECT establishes a tunnel to the server identified by the target resource.

7. OPTIONS used to describe the communication options for the target resource.

8. TRACE performs a message loop-back test along the path to the target resource.

9. PATCH is used to apply partial modifications to a resource.