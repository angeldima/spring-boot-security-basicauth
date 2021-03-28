# spring-boot-security-basicauth
Spring security usage example with basic authentication

How to test path and roles filter:

1) curl -i http://localhost:8080/employees  --> HTTP Status 401
2) curl -i --user user1:password1 http://localhost:8080/employees  --> HTTP Status 200
3) curl -i --user user2:password2 http://localhost:8080/employees  --> HTTP Status 403