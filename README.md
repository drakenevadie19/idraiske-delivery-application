# idraiske-delivery-application

Technologies: 
- Front-end: Angular, Bootstrap 5
- Connecting Front-end and Back-end: Rest/ Restful.
- Back-end: Spring boot, Microservices, Github, Docker, Kubernetes, Junit, Sonar, AWS EKS, AWS ALB, AWS EC2, AWS RDS (SQL), Mongo Atlas (No-SQL), Jenkins, ArgoCD.

Back-end microservices: 
- Eureka Server: 
  - Monitoring current online servers.
  - Enabling LoadBalancer to inject a server's service into another server's back-end.
  - Link: https://github.com/drakenevadie19/idraiske-eureka-server.git
- Food Catalogue:
  - Managing dishes for restaurants in a MySQL database.
  - Respond to Food catalog endpoints.
  - Link: https://github.com/drakenevadie19/idraiske-Food-Catalogue-Microservice.git
- Restaurant Listing:
  - Managing a list of available restaurants in an area.
  - Store and extract them from a MySQL database.
  - Link: https://github.com/drakenevadie19/idraiske-Restaurant-listing-Microservice.git
- userInfo Management:
  - Storing, fetching, and updating users' information such as ID, name, password, and user delivery address for food delivery.
  - Managing massive info in a MySQL database.
  - Link: https://github.com/drakenevadie19/idraiske-userInfo-Microservice.git
