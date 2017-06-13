0. Reference -
	http://www.concretepage.com/spring-boot/spring-boot-rest-jpa-hibernate-mysql-example
	
1. GET all articles

	http://localhost:8080/user/articles
	response - 
	[{"articleId":1,"title":"Java Concurrency","category":"Java"},{"articleId":2,"title":"Hibernate HQL ","category":"Hibernate"},{"articleId":3,"title":"Spring MVC with Hibernate","category":"Spring"}]

2. Get article by id
	http://localhost:8080/user/article/1
	response -
	{"articleId":1,"title":"Java Concurrency","category":"Java"}
	
3.  Add article
	http://localhost:8080/user/article
	body - {"title":"Spring boot","category":"Spring"}
	response - header - uri and status code 201

4. 