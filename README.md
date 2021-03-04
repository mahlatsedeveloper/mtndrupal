
CONTENTS OF THIS FILE
---------------------

 * About project
 * How to install
 * How to query the api


ABOUT Project
------------

The project is supposed to use custom entity type to create entities that will be used with API:JSON module so that the website content can be exposed through the api.


How to install
--------------------------

Clone the link (https://github.com/mahlatsedeveloper/mtndrupal.git) on local using git and then install using lando.

run lando start and the project will run using sqlite database and drupal9


How to query the api
---------------------

The entity types can be queried using the following examples of the 2 custom entities created.

The base_url is the url with a port number ie. http://localhost:55008/jsonapi/node/restaurants that lando generated when you ran lando start

http://{base_url}/jsonapi/node/restaurants ( this will query all restaurants )
