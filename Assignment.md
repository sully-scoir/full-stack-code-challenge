# Assignment
Create a small app to keep track of a user's favorite pictures of dog breeds. 

## Resources
* Use this api as your data source: https://dog.ceo/dog-api/#all
* Use the provided [wire frame](./dogBreedsTest.pdf) for reference. This is a suggestion, feel free to make any adjustments that will improve the page.

## User Stories

### As a User, I can log in
* Accept a username and a password
    * User sign up is optional for this exercise, the user and their credentials can be seeded/hard-coded

### As a User, I want the option to specify the breed for the next dog card
* A typeahead of available breeds is provided
    * Once a breed is selected, it should populate a dog card and then clear the input.
    * User provided values (values not found in the typeahead) are not allowed.

### As a User, I can see the collection of dog cards I have requested
* Dog cards consist of the following:
    * A picture of the dog
    * The name of the breed
    * A delete button
* The order of dog cards should show the most recently added dog first.

### As a User, I can remove dog cards from my collection
* There is a mechanism to clear all dog cards from my collection
* I can remove individual dog cards

### As a User, I can log out and when I log back in, I see the dog cards that I had added before I logged out
* A database is optional for this exercise, storing user dog selections in an in-memory structure is acceptable
