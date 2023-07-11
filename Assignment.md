# Assignment
Create a page to keep track of my favorite pictures of dog breeds.

## Resources
* Please use this api as your data source: https://dog.ceo/dog-api/#all
* Please use the provided [wire frame](./dogBreedsTest.pdf) for reference. This is a suggestion, feel free to make any adjustments that will improve the page.

## User Stories
### As a User, I want the option to specify the breed for the next dog card
* A typeahead of available breeds is provided
    * Once a breed is selected, it should populate a dog card and then clear the input.
    * User provided values (values not found in the typeahead) are not allowed.

### As a User, I want the option to request a random breed for the next dog card
* A mechanism shall allow me to easily request a random breed for the next card.
    * When activated, it will populate the next dog card.

### As a User, I can see the collection of dog cards I have requested
* Dog cards consist of the following:
    * A picture of the dog
    * The name of the breed
    * A delete button
* The order of dog cards should show the most recently added dog first.

### As a User, I can remove dog cards from my collection
* There is a mechanism to clear all dog cards from my collection
* I can remove individual dog cards
