# Dish-Order-System
Relational Database Design Final Project

# Main components:
- Service --- services to require the related Entity and Dao to implement the logic
- Controller --- implement as router, transaction controller, user authentication
- DAO --- Data base Access Object
- DTO --- a dataModel, mapping to the front-end's data user just entered, then provide to the controller  
- Entity --- a dataModel, mapping to the database, get called in the DAO's method to implement query/updates in database

# Work flow:
- Contorller  --has_a--->   Service --has_a--->  Entity,DAO  ---called_by--->   DAO  --update--->   DB

# Contributors

* [vencci](https://github.com/vencci)
* [wikijin](https://github.com/wikijin)
* [MelodyXman](https://github.com/MelodyXman)
* [littlesnail1982](https://github.com/littlesnail1982)
* [hychrisli](https://github.com/hychrisli)



