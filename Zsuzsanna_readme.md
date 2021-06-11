# RPS Challenge
This is a solo project created for the Makers Academy week 3 weekend challenge.

This project was built using Ruby, and was structured around the Sinatra framework. The Rspec testing framework was implemented to provide feature and unit testing capabilities, and Capybara was included to allow for testing of front-end elements.

## Basic Rules
Task is to provide a _Rock, Paper, Scissors_ game.

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock


### User stories

```
As a marketeer
So that I can see my name in lights
I would like to register my name before playing an online game

As a marketeer
So that I can enjoy myself away from the daily grind
I would like to be able to play rock/paper/scissors
```
### Require
```ruby
require 'simplecov'
require 'simplecov-console'

SimpleCov.formatter = SimpleCov::Formatter::MultiFormatter.new([
  SimpleCov::Formatter::Console,
  # Want a nice code coverage website? Uncomment this next line!
  # SimpleCov::Formatter::HTMLFormatter
])
SimpleCov.start
```
