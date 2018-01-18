
- Express-generator: Use the application generator tool, express-generator, to quickly create an application skeleton.

## Testing:
 
  - mocha: provides a very convenient way to write and run tests.
  - should.js : gives you a ton of nice methods and properties to verify that the results are what you expect
  - node-mocks-http:
  - mockery killer feature is that when a module is loaded with require it can provide a      different object instead of the one returned by the module.
  - nock: Whenever an http request is made nock intercepts it and responds with whatever you want. You can select the data it sends back, the status code and much more.

## Templates engines:

  - jade: is great for generating html pages. It makes writing html tags much shorter and more readable. It also uses JavaScript for conditions and iteration. 

  - mustache: on the other hand, is focused on rendering any kind of template and it provides the minimum logical operators as possible with very little way of processing your data. This makes it excellent for writing very clean templates, which are focused on presenting your data instead of processing it.


## Middleware:
The purpose of a middleware is to extract a common controller code, which should be executed on multiple requests and usually modifies the request and/or the response objects.

Just like a controller, a middleware should never directly access the database. Instead, it should use your models for such tasks.

##Database:
- Sequelize - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.
- Bookshelf - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
- Mongoose - Elegant MongoDB object modeling.
- Waterline - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.

## Npm: Dependency manager
- package.json
- package-lock.json 



## Callback Hell:

- async

- promises

## Libraries:

 - socket.io

 - require.js
 
 - Moment.js - Parse, validate, manipulate, and display dates.


## Others
  - https://www.loggly.com/
  - Load testing: https://locust.io/
