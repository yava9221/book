---
layout: layout.hbs
---

# Features

## Feature: View other profiles

``` gherkin
TODO: I want to chat with another user. 

Scenario: 
	Given that there is more than one user, I want to view another profile.
	When I press the chat icon/profile image, then I can see their profile information.
	
	

```

## Feature: Search for a book 

``` gherkin
TODO: Find a book in the database.

Scenario: 
	Given that a book I want in the database, I want to be able to look it up. 
	When I enter a keyword into the search box.
	Then I should see a list of matches.

```

## Feature: Add a book to the database.

``` gherkin
TODO: As a user I want to add a new book to the database.
Scenario: 
	Given that a book is not in the database
	When I click the add book option
	Then I should be able to fill in details.
```

## Feature: Filtering through books in the database based on genre.

``` gherkin
TODO: As a user I want to be able to view books based on a specific genre. 
Scenario:
	Given that I want to view books of a certain genre
	When I click a genre option
	Then I should see books that match that genre.
```
## Feature: Discussion board

``` gherkin
TODO: As a user I want to be able to view my discussions. 
Scenario:
	Given that I have joined a discussion
	When I click on the book name
	Then I should see my messages.
```

## Feature: Editing personal profile
``` gherkin
TODO: As a user I want to be able to edit my profile at any given time.  
Scenario:
	Given that I have created an initial profile.
	When I click the edit option
	Then I should see my profile with editable text/images.
```

## Feature: Viewing activity on a book.

``` gherkin
TODO: As a user I want to be able to view incoming on a specific book. 
Scenario:
	Given that I want to view how active a book is
	When I click on the "more info" icon
	Then I should see all the activity the book has generated from users.
```

# Examples

## Feature: Usage

``` gherkin
Feature: Usage
  As a user of Cucumber.js
  I want to have documentation on Cucumber
  So that I can concentrate on building awesome applications

  Scenario: Reading documentation
    Given I am on the Cucumber.js GitHub repository
    When I go to the README file
    Then I should see "Usage" as the page title
```

## Feature: Serve Coffee

``` gherkin
Feature: Serve coffee
  Coffee should not be served until paid for
  Coffee should not be served until the button has been pressed
  If there is no coffee left then money should be refunded

  Scenario: Buy last coffee
    Given there are 1 coffees left in the machine
    And I have deposited 1$
    When I press the coffee button
    Then I should be served a coffee

  Scenario: No more coffees
    Given there is no coffee left in the machine
    And I have deposited $1
    When I press the coffee button
    Then I should be refunded $1
```
