## Yo Telecom Connect

### Macro functions

* `runOnCallRinging()`

This tells the app to run the macro when call rings instead of default, run when call established

* `confirm()` or `confirm("Are you sure?")`

Shows a confirmation dialog, with optional custom dialog. 

Default dialog is `"Do you want to search your CRM for +44111222333?"`

For more confirm configuration, pass in the following JSON object:

`confirm({"dialog": "Hello caller, %c", "timer": 30})`

other acceptable configuration: `{"dialog": "Hello caller, %c"}` or `{"timer": 30}`

`%c` will be replaced with the caller phone number

Timer is the countdown timer for when confirmation window is closed in seconds

* `openApp(YourApp)`

Opens given application

* `mouseButton(Left | Right | Middle)`

Simulate mouse button click

* `moveMouse(X, Y)`

Move mouse pointer to given screen coordinates X, Y

* `keyPress(Key)`

Simulate keyboard press

* `writeCaller()`

Simulate keyboard press of incoming callers phone number

* `#` comment

Line that start with # are considered comments and ignored

### [Changelog](Changelog.md)

### Notes

MacOS requires the following permissions:

* Accessibility
* Files & Folders
* Automation

if you get a permissions error on macOS for accessibility, try the following steps:

* Close app if it's open
* Go to System Preferences / Security/Privacy / Accessibility
* Find Yo Telecom Connect.app, select and click the minus to remove app from list
* Manually add app to list. Click plus, select app from Applications folder
* Open app and test.  If there is a permission's error, you should see an error message
