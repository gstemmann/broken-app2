### Conceptual Exercise

Answer the following questions below:

- What is a JWT?
 it's a json webtoken
- What is the signature portion of the JWT?  What does it do?
to verify the sender of the jwt is who it says it is and to ensure that the message wasn't changed along the way
- If a JWT is intercepted, can the attacker see what's inside the payload?
yes
- How can you implement authentication with a JWT?  Describe how it works at a high level.
client application must send a json web token in the authorization header of the http request to your backend api
- Compare and contrast unit, integration and end-to-end tests.
end to end testing makes sure things are working from UI all through the database layer and they usually sit on top of the integration tests

unit tests will cover specific components to determine whether each one is fully functional (functions, individual programs, or procedures) while integration testing allows individuals the opportunity to combine all of the units within a program and test them as a group
- What is a mock? What are some things you would mock?
creates a fake version of an external service to make tests run more quickly
- What is continuous integration?
when developers regularly merge their code changes into a central repo, then tests can be run
- What is an environment variable and what are they used for?
you can use environment variables to use many cloud hosts like heroku, aws, and asure.
- What is TDD? What are some benefits and drawbacks?
test driven development - immutability and pure functions are usually the benefits. the drwabacks may be that it takes much longer but can be more satisfying
- What is the value of using JSONSchema for validation?
it generates clear, human and machine readable documentation
- What are some ways to decide which code to test?

- What does `RETURNING` do in SQL? When would you use it?
retreives values of columns that were modified by an insert, delete, or update without having to run another select statement
- What are some differences between Web Sockets and HTTP?
with http you have tot constantly request updates and web sockets are sent immediately
- Did you prefer using Flask over Express? Why or why not (there is no right flask has been slightly more human readable
  answer here --- we want to see how you think about technology)?
