# Assignment
Create an one page application following the requirements given in this assignment.

We suggest to use create-react-app typescript for your setup.

Intermediate engineers and above are also expected to complete [backend test](https://github.com/sevenbridgesnz/recruit-backend-dotnet) to persist the data. If you are completing the backend test, please make sure both front end and backend are connected, eg front end is fetching data from the backend.

## Demonstration of Concepts
Remember this assignment is supposed to demonstrate knowledge of concepts and should be treated as such.
You are asked to write a simple ordering program that will collect order information
and when submitted, it will display list of ordered items on the main screen. We are not looking for the perfect implementation, but for demonstration of knowledge of the technologies.

## Specs
These are the only functional requirements for your implementation:

### Navigation
- Clicking on the menu will roll down and display individual menu items
  - Home
  - New Item

Selecting `Home` item will navigate to the landing page. The landing page
will display list of ordered items (Full Name, Order Description, Quantity and ability to delete an item)

Selecting 'New Item' will navigate to `\new` page where a new order item can be added.

### Inputs
- First Name
  - Optional, must not be longer than 20 characters
- Last Name
  - Must be entered, no longer than 20 characters
- Order description
  - Must be entered, no longer than 100 characters
- Quantity
  - Must be a number between 1 and 20

### Submit
- You cannot submit until input fields are valid
- Validation error shows if the input cannot be submitted
- After submitting the item, it will navigate back to the landing page where list of orders will be displayed

## Data Storage

If you have been asked, please complete the [backend assignment](https://github.com/sevenbridgesnz/recruit-backend-dotnet) as well. If the assignment is front-end only, a simple state management or
Redux store (preferable) is sufficient though mocking up the API communication with tools as [Beeceptor](https://beeceptor.com/) is highly valued.

## What is valued
- Demonstration of concepts. Even though full implementation might not be complete because of time constrains, demonstrating knowledge of patterns and technologies is highly valued.
- Clean Code
- Typescript
- State Management
- Tests
- Design (Responsive)
- Accessibility

## Duration
You are only expected to do work on
this assignment that matches the skill level of the role you are applying for, but you are welcome to do as much as you like.

# Tools & Tech
You can use any tools, plugins and technologies as required for you to complete this assignment.
We expect that you in this assignment demonstrate competencies with the following technologies:

-	React
-	Typescript
- State Management
- Integration with the API
-	CSS

# Submitting Assignment
Feel free to create a public GitHub repo or private GitHub repo where you invite [sevenbridgesnz](https://github.com/sevenbridgesnz) so we can give access to the right people.
