# Full stack Vaadin and Spring Boot demo app

![Vaadin and Spring Boot example with JPA and H2](screenshot.png)

## Running

You can run the project with 

```
gradlew bootRun
```

After application bootstrap call ...
http://localhost:8080

For debugging call ...
http://localhost:8080/?debug

I have copied this example from ...
https://github.com/marcushellberg/spring-boot-todo
(https://www.youtube.com/watch?v=qUBt8k4pQgQ)
... and optimized it:
- gradle instead of maven
- enabled browser debug window  
- Adding the new 'push' (vaadin 8) to application. Now the server can push messages over websockets - awesome!!!
  Try also to open multiple browser windows - all browser windows have same content and updated!!
  https://vaadin.com/docs/v8/framework/advanced/advanced-push.html