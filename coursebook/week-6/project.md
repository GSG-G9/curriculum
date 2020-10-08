# Week 6 Project

Create a **server-side rendered** web app.

Like in week 5, the app should retrieve from an API, but this time, you should use **handlebars** to render on the server, before sending files to the front end.

### Goals:
1) Write your server using expressJS & Handlebars

2) There should no heavy DOM manipulation on the front end (apart from that needed for Client side validation, below)

4) There should be some form of user input on the front end with client side validation

2) Use at least 1 API that uses an Access Key and make your API calls from the back-end (try using `node-fetch`)

3) Your server should contain a minimum of 2 routes, including one POST route

4) We expect to see lots of tests! Modularise your code and test all your pure functions. Write tests for as much of your back-end and front-end logic as you can. We don't expect tests on the DOM.

5) Test your server routes by injecting fake HTTP requests using Supertest (including testing for 404's). _Note - you are not required to test any server route that makes an API call, as this will make the test impure (a test that depends on an external factor is not reliable)_

6) Host your project on Heroku.

7) Use module.exports and require to break a single large server file into smaller modules.

8) Consider a good server file structure based on what we have discussed over the week.

9) Employ continuous integration on your project with Travis or a similar tool. (If you decide to use Travis, we strongly recommend that you host this project in your own repo rather than in your cohort's FAC repository to avoid all builds getting queued together)

10) Use CodeCov or a similar tool to report and track test coverage.

11) Include Error Handling. For example:
  - if a user attempts to make a request to a non-existent route to your server (404 - as mentioned above), provide the user with a custom response.    
  - if there is a [programmer error](https://github.com/foundersandcoders/error-handling-workshop#kinds-of-errors) on your server (e.g. a handler function does not act as intended), provide the user with a custom response (500 status code).


14) Display continuous integration and code coverage badges on your project README. 

### Stretch Goal

- During your presentation compare the "first paint" of this project, and week 5's project. Why is it different?
