# dsti-devops-2023-project

This is a Python Flask project that uses CRUD operations to store user details in a database. The project is built using the following tools and technologies:

Programming Language: Python<br>
Framework: Flask<br>
Database: SQLAlchemy/PostgreSQL
Tools: Table plus
SQLAlchemy is a popoular Python library that provides an ORM (Object-Relational Mapping) for working with SQL databases in Python. With SQLAlchemy, you can interact with SQL databases using Python classes and objects, rather than writing raw SQL queries.

Some of the key features of SQLAlchemy include:

Support for multiple SQL databases, including MySQL, PostgreSQL, SQLite, Oracle, and Microsoft SQL Server.
Comprehensive ORM features, including support for mapping classes to database tables, relationships between classes, and query building.
Advanced SQL expression language for generating complex queries.
Support for transactions, connection pooling, and other advanced database features.

### Author

-Manyank Bhandari- mayank.bhandari@edu.dsti.institute<br>
-Ramesh Singh- ramesh-kumar.singh@edu.dsti.institute

### Mentors
  - Gonzalo Etse - gonzaloetjo@gmail.com
  - Yanis Bariteau - yanis@adaltas.com
  - Guillaume Holdorf - guillaume.h@adaltas.com

### Swagger UI
http://localhost:4000/swagger/#/

## How to run the project?
1) Checkout the github repo.
2) run the below docker comand
* docker compose up -d flask_db
* docker -ps
* docker compose up --build flask_app

# How to create K8s?
* docker build -t [image_name] .
* docker run -d -p 80:5000 --name [container_name] [image_name]
* docker tag [image_name] [repo_name]/[imange_name]
* docker login
* docker push [repo_name]/[imange_name]
* kubectl apply -f deployment.yml
* kubectl get deployment
* kubectl get services
* kubectl delete services [service_name]
* kubectl delete deployment [deployment_name]

## Images of Working Project

* Create user

![post](https://user-images.githubusercontent.com/15153249/236623307-42a6c47c-4ab5-4744-a721-2c14ec71178a.png)

* Get User

![get_user](https://user-images.githubusercontent.com/15153249/236623289-2955c860-c476-4229-87b6-b50eeda54b03.png)

* Get User by id

![get_user_id](https://user-images.githubusercontent.com/15153249/236623319-ddedff0b-f6ae-45a2-b894-1f7b4e74cdef.png)

* update user

![update](https://user-images.githubusercontent.com/15153249/236623336-d23edbf7-b203-4806-a921-c97eb7010dea.png)

* delete user

![delete](https://user-images.githubusercontent.com/15153249/236623329-e957361d-2642-4413-8151-37e96eb20814.png)

* Swagger UI

![swagger ui](https://user-images.githubusercontent.com/15153249/236623960-030435da-415e-4611-8550-2dacc46e3ada.png)

* CI-CD

![CI-CD](https://user-images.githubusercontent.com/15153249/236623388-6f23ebb6-9b65-4d9d-89d5-c6b91ac994b9.png)

* Database Table

![database_table](https://user-images.githubusercontent.com/15153249/236623409-3bd2e5ed-fbde-40de-8b9c-5efa20e0ec30.png)

* Vagrant file

![vagrant_file](https://user-images.githubusercontent.com/15153249/236623856-5ab2485c-1a2c-4067-977f-005b1f674823.png)

*Docker hub

![docker_hub_image](https://user-images.githubusercontent.com/15153249/236684865-20da5b7b-700b-408b-adbb-4e76dac36b4f.png)

* k8s pods

![get_pods](https://user-images.githubusercontent.com/15153249/236623798-e4326467-1745-46f4-a475-1d6dcf9219af.png)

* k8s services

![kubctl_services](https://user-images.githubusercontent.com/15153249/236623818-4abb50e9-8d0c-488d-9c16-0cd4705b285c.png)


# THANK YOU :)




