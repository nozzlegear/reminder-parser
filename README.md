# Reminder Parser
Parses a sentence into a title and a date in order to pass along to an AppleScript to create a reminder.

## How to use
The console takes input, and you type in a sentence like:

`remind me to do laundry tomorrow at 5pm`

Then the program returns two lines as output:

    do laundry
    6/22/2016 5:00:00 PM

### Other types of input

- `remind me about stuff in 30 minutes`
- `remind me to return my books on july 3 at 8:30AM`
- `remind me to get ready for bed at 10pm`

## Notes
- The time component must not have a space between the time and the am/pm.
