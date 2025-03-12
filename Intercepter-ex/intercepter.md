## What is an Interceptor in Spring Boot?
![screenshot](/Intercepter-ex/images/inter.png)A Spring Interceptor is used to **intercept incoming HTTP requests before they reach the controller and after the response is sent to the client.** It is useful for logging, authentication, request modification, and response handling.

Spring Boot provides HandlerInterceptor, which you can implement to perform tasks before and after request processing.