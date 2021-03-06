[![Build Status](https://travis-ci.org/andrsam/bookshelf.svg?branch=master)](https://travis-ci.org/andrsam/bookshelf)
[![codecov](https://codecov.io/gh/andrsam/bookshelf/branch/master/graph/badge.svg)](https://codecov.io/gh/andrsam/bookshelf)
# bookshelf
The simple library manager

Used for accounting of the books

![ScreenShot](images/screenshot.png)

#### Definitions
Book is a entity, that contains unique id, title, year of publication and author 

#### Basic operations
* Maintenance of books(add, remove, delete);
* Searching for the books by title, year of publication and author;  
* Reporting with a list of books, grouped by:
  * Author;
  * Year of publication.  

#### Used technologies
##### Backend:
* Spring MVC
* Hibernate
* Spring Data JPA
* Spring Data JPA Specification 
* Gradle 
* JaCoCo
* Travis CI
* hsqldb in memory
##### Frontend:
* Easy UI Jquery plugin
* Bootstrap

#### Run and build 
The
[gradle-cargo-plugin](https://github.com/bmuschko/gradle-cargo-plugin) 
using command:
```
gradle build cargoRunLocal
```






