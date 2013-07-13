dbs-example-jpa-complex
-------------------
Example of complex Spring Data JPA application.  Hibernate is used as JPA implementation.

Documentation:
-------------------
 * https://github.com/johntday/dbs-example-jpa-complex/wiki
 * Database diagrams:  [Overview ERD][Overview ERD], [MySQL ERD][MySQL ERD]

References:
-------------------
 * public site:  http://johntday.github.io/dbs-example-jpa-complex
 * [JPA annotation documentation][My JPA annotation documentation]

To get the code:
-------------------
Clone the repository:

    $ git clone git:/github.com/Daugherty/dbs-example-jpa-complex

If this is your first time using Github, review http://help.github.com to learn the basics.

To run the application unit-tests:
-------------------	
From the command line with Maven:

    $ cd dbs-example-jpa-complex
    $ mvn test

To install the application:
-------------------	
From the command line with Maven:

    $ cd dbs-example-jpa-complex
    $ mvn install

or

In your preferred IDE such as SpringSource Tool Suite (STS):

* Import "dbs-example-jpa-complex" as a Maven Project
* Drag-n-drop the project onto the "SpringSource tc Server Developer Edition" or another Servlet 2.5 or > Server to run, such as Tomcat.

Access the deployed web application at: http://localhost:8080/dbs-example-jpa-complex/

[My JPA annotation documentation]: http://www.evernote.com/shard/s8/sh/147ea1ec-d9d2-46fd-a0d9-3d2b819703fb/8e476ca6950c7d6c9551dbcc54d8c7f3
[Overview ERD]: https://github.com/johntday/dbs-example-jpa-complex/blob/master/src/main/resources/img/erd.png
[MySQL ERD]: https://github.com/johntday/dbs-example-jpa-complex/blob/master/src/main/resources/img/erd-detail.png