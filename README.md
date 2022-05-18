# The Lift kata
https://kata-log.rocks/lift-kata

##Description
Since lifts are everywhere and they contain software, how easy would it be to write a basic one? Let’s TDD a lift, starting with simple behaviors and working toward complex ones. Assume good input from calling code and concentrate on the main flow.

###Suggested features:

- A lift responds to calls containing a source floor and direction
- A lift has an attribute floor, which describes it’s current location
- A lift delivers passengers to requested floors
- You may implement current floor monitor
- You may implement direction arrows
- You may implement doors (opening and closing)
- You may implement DING!
- There can be more than one lift

###Advanced Requirements
A lift does not respond immediately. Consider options to simulate time, possibly a tick method.
Lift calls are queued, and executed only as the lift passes a floor