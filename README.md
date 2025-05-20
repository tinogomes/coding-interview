#### Ruby on Rails Code Challenge

Project Requirements:

* Ruby version: 2.7.6

#### Before the code challenge:

* Clone the repository locally and install all the dependencies
* Get familiar with the codebase
* Check the database schema

#### TODO

- [ ] 1. Users report that when filtering users by company, they still get all system users, determine the cause and fix it.
- [ ] 2. When filtering by username, no partial matchers are displayed, only full match applies. Example: ‘username_1: max‘ and ‘username_2: mathew‘ if search by ‘ma‘, ‘ma‘ , ‘Ma‘ no results are found. determine the cause and fix it.
- [ ] 3. Write specs to validate the filtering solution is valid.
- [ ] 4. Implement the tweets index endpoint using a cursor pagination/infinite scroll alike approach (no gems are valid). Sort is by most recently.
- [ ] 5. Retrieve the tweets for a specific user (using the same index function) - make sure to avoid boilerplate code. Use ‘User model‘ scopes. Adapt your solution to defined routes. Do not modify the routes file
- [ ] 6. create a Dockerfile and docker-compose to run the project
- [ ] 7. implements a simple CRUD for company (with html pages)
- [ ] 8. implements a mailer for new user
