# Classical Blog  
A REST application implementing a classical version of a blog site with a possibility to authenticate a user based on the roles and keeping data in a database.\
The technology used: Java + Stream API + Spring Boot + Spring Security + JPA Hibernate + Lombok + MySQL + Log4j.

## Functionality
* User can make a new account, log in to an already existing one, publish a post, add a comment, upload a picture to his/her profile, post and comment, like a post of an other user, as well as update and delete everything what he/she created. 
* Administrator has the same rights as the ordinary user with an additional possibility to delete accounts of other people.

## Additional Information
* Client part can be found here: https://github.com/Olga424/Classical_Blog_Client
* The data are kept in a MySQL database.
* The pictures and photos are commpressed before putting into the database and decompressed before uploading to the application page. 
