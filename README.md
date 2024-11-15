# generic-fast-food-menu-api

This project is an exercise from the course _Curso Completo onde aprenderemos TUDO sobre APISRestful e Microsserviços (Usaremos os serviços criados pela Netflix)_ available on Udemy.
The main goal of this exercise is creating an RESTful CRUD API, and to meet this goal, the project simulates a generic fast food menu service.

## Phase 1: Creating the Menu Item object

The menu is composed by items and each item contains the followed fields: `id`, `name`, `categories`, `price`, `quantity`, and `description`.
Actual, the allowed categories are: alcoolic drink, drink, children's snack, snack, combo, dessert, and adicional.
An menu item must have at least one category or more.
And the field price is composed by `currency` and `value`.

## Phase 2: Implementing the CRUD operations

An list of the menu items must be created to represent a database so far.
The repository layer will enable to CRUD operations over a menu item list.
This operations will occurs through the user requests.
