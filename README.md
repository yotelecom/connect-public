# Yo Telecom Connect

### Macro functions

````runOnCallRinging()````

This tells the app to run the macro when call rings instead of default, run when call established.

````confirm()```` or ````confirm("Are you sure?")````

Shows a confirmation dialog, with optional custom dialog. Default dialog is ````Search for +44111222333?````

````openApp(YourApp)````

Opens given application

````mouseButton(Left | Right | Middle)````

Simulate mouse button click

````moveMouse(X, Y)````

Move mouse pointer to given screen coordinates X, Y

````keyPress(Key)````

Simulate keyboard press

````writeCaller()````

Simulate keyboard press of incoming callers phone number

````#```` comment

Line that start with # are considered comments and ignored

### Notes

MacOS requires the following permissions:

* Accessibility
* Files & Folders
* Automation

if you change the permissions, restart the application.
