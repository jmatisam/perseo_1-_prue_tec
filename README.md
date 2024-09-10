# Read Me First
The following was discovered as part of building this project:

* The original package name 'jmat.f5.perseo_1-_prue_tec' is invalid and this project uses 'jmat.f5.perseo_1__prue_tec' instead.

# Getting Started
![perseo](image.png)

## The company Perseo, known for being a technological employment portal, wants to launch a platform where it can sell online courses to programmers who use its services to look for work, so programmers can add more knowledge to their profile. To do this, Perseo needs an MVP that allows its users to register, log in, and allow them to record their work experience and the courses they have purchased in their user profile.Perseus would also like to be able to log in as admin and allow him to edit the courses.

##  The MVP must have a backend with:

CRUD user control that also allows:
* Login
* Register
* In the user profile

you must be able to see your work experience
*  Be able to register as "admin"
*  If you register as "admin" you have access to a control panel where you can edit the courses offered.
*  Be able to register as a "user"
*  (extra) Be able to register with the Linkedin/Github account
*  [extra (thanks Marta and Charneco)] Implement a shopping cart and payment gateway to purchase the courses



# Spanish Version

## La empresa Perseo, conocida por ser un portal de empleo tecnológico,  quiere lanzar una plataforma en la que poder vender cursos online a programadores que utilizan sus servicios para buscar trabajo, así los programadores podrán añadir más conocimientos a su perfil.Para ello, Perseo necesita un MVP que permita registrarse a sus usuarios, hacer login y que puedan registrar en su perfil de usuario su experiencia laboral y los cursos que ha comprado. También a Perseo le gustaría poder hacer login como admin y que le permita editar los cursos.

## El MVP ha de tener un backend con:

 Control de usuario CRUD que además permita:
* Hacer login
* Registrarse
* En el perfil de usuario se ha de poder ver su experiencia laboral
* Poder registrarse como "admin"
* Si te registras como "admin" tienes acceso a un panel de control en el que puedes editar los cursos que se ofertan.
* Poder registrarse como "usuario"
* (extra) Poder registrarse con la cuenta de Linkedin/Github
* [extra (gracias Marta y Charneco)] Implementar un carrito de compra y una pasarela de pago para comprar los cursos




### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.3.3/maven-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.3.3/maven-plugin/build-image.html)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.3.3/reference/htmlsingle/index.html#data.sql.jpa-and-spring-data)
* [Spring Security](https://docs.spring.io/spring-boot/docs/3.3.3/reference/htmlsingle/index.html#web.security)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/3.3.3/reference/htmlsingle/index.html#using.devtools)

### Guides
The following guides illustrate how to use some features concretely:

* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Securing a Web Application](https://spring.io/guides/gs/securing-web/)
* [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
* [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/)

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

