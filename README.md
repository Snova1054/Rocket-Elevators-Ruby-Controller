# Rocket-Elevators-Ruby-Controller
## Description

This controller's whole purpose is to handle a personalized amount of elevators with a personalized amount of floors in a single column.

It can be controlled first from the outside of an elevator on each floor and after that, from the inside a specific elevator.

When used called from outside, the column sends the best elevator possible from the user's current floor and direction. Then, when used from the inside of the elevator that was selected by the column, the elevator is moved to the to the user's destination.

Elevator selection is based on the elevator's status, current floor, direction and floor request list and on the user's floor and direction.

## Dependencies

### To run the tests for this program you need to install Ruby and then you can run the following in your terminal to verify if you have Ruby installed:
```
ruby -v
```

### And now, to be able to try the program with pre-made settings you only need to follow the instructions given by the console:
#### Each scenario:
##### Keep in mind that every elevator's current floor, status, direction and destination are pre-made. As is the user's current floor, direction and destination
##### Also, every scenario has 10 floor and 2 elevators
- Scenario 1 elevator A is Idle at floor 2 and elevator B is Idle at floor 6. The user is on the 3rd floor and wants to go to the 7th floor.

- Scenario 2 elevator A is Idle at floor 10 and elevator B is Idle at floor 3. The user is on the 1st floor and wants to go to the 6th floor. Another user is on the 3rd floor and wants to go to the 5th floor. And a last user is on the 9th floor and wants to go to the 2nd floor.

- Scenario 3 elevator A is Idle at floor 10 and elevator B is moving from the 3rd floor to the 6th floor. The user is on the 3rd floor and wants to go to the 2nd floor. Another user is on the 10th floor and wants to go to the 3rd floor.