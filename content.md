# ToDo
- [x] Backend
- [ ] API
- [ ] Frontend

- [ ] Backend -> Strat -> Parser.
- [ ] alt words for Frontend and Backend.

- [ ] API: 37.
- [ ] API -> Analyzer.

- [ ] Cmd + J Navigation.


# Backend

## Integrating Backtrader

Backtrader is a python framework used for Backtesing and Trading. We are using this library to facilitate running backtests and save resources and time by reusing infrastructure.

## Creating Custom Strategy
One of the key features of Stratosphere is the flexibility it provides the user with to create their own strategy. They can choose the required indicators and tune them accordingly. The platform supports comparing indicators as well as operating on them. Apart from this, it also allows recursive usage of logical operators `and (everything)` and `or (anything)`.

> [!Note]
> Parser

## Plugins
Extending on our platform's flexibility for custom strategies, the code is modularised and organised in a comprehensible way. This facilitates addition of new, and custom plugins. 

Users can add their own indicators, comparators and operators guided by the documentation. These plugins are Dynamically fetched, thus providing protection against accidental change in the Core Functionality of the Engine.

This also offers confidentiality to the user and also allows them to operate on their own indicators and data for personalised backtests.

While addition of plugins can be done via adding `.py` files with the format specified in the documentation, addition of Asset Data and Indicator CSV Files is also supported via the UI.

Addition of custom Indicators also facilitates users in creating highly personalised strategies, further supporting our support for creating custom strategy.


***


# API

We have used Flask to aid the communication between our frontend and backend. 
Instead of sending and displaying raw results to the user, the data has been restructured to allow better readability and **Something**???


***


# Frontend

## Create Strategy
Our UI takes into account the recursive and complex nature of trading strategies and gives the user multiple channels to create them.
It also has a brief description of all the plugins that we support for user reference.
New strategies can be created either via our Form based input or by entering a Valid JSON for the same.

### Form
- Non Programming User Friendly
  - Easy to comprehend
  - Add and Remove conditions with just the click of a button.
  - provides description of the selected plugin, facilitating better usage of plugins.
- Flexible
- Recursive
- Dynamically Generates a Valid JSON Schema for the same.

### JSON
> [!Important]
> Validator

## Strategy Gallery
This allows viewing all the publicly available strategies **- DONE**.

***

