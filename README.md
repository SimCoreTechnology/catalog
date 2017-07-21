# README #

Catalog, is a bare bones Laravel application designed to be a starting place for a backend code test.

Please track your time on this project, as we will want to refine this test over time if we feel it's too much of a time commitment.

### What is this repository for? ###

Candidates for SimCore Technologies backend software engineer positions.

### How do I get set up? ###

Follow instructions at laravel.com to get everything setup and running.

### Code Test Instructions ###

The goal of this project is to create an API backend for creating and retrieving data in a product catalog. 

There should be no front end, except for raw JSON responses. 

A DB is not required. However, using sqlite, or static json files to store dummy data may make life easier. 
If you choose to use SQLite please use migrations and seeds appropriately.

While this will be an API, it does not require authentication for this test.

Please write unit tests for all end points. (again use dummy data)

Please create the following:

* Standardized API end points.
* Create an end point that will create a product of a certain type by receiving a json string.
* Create an end point that will return a list of products in the system. 
* Create an end point that will return the details of a single product.

#### Considerations ####

While this is a simple product catalog. Product Type's need to be a consideration, and each product type will have different attributes.

Product Types the system should support:

* Books
* Magazines
* Periodicles
* Academic Journals

Please be creative when coming up with unique attributes for each set.

For time consideration, stub out business logic, and add TODO's to go into more detail on what you will need to add to flesh out methods.
As time permits, go back and add in business logic to flesh out methods. Since this test isn't being judged on time spent, we want to make sure you get your thoughts and ideas in code, one way or another.

### Time of Interview ###

Please be prepared to demo this project, and be able to explain your code decisions.

### Who do I talk to? ###

Please reach out to your contact at SimCore Technologies if you have any questions, or challenges with this code test.