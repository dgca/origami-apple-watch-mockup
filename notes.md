# Notes

For the initial notification, the app icon and the app name both fade in and translate up a bit.

For the transition from the notification to the long notification, the app name fades out and translates up, and the app icon resizes and repositions itself to the top of the notification bar of the long notification.

The time of day fades into the long notification in place, and the long notification slides up into place.

When you tap a button on the long notification, it dims, goes back to normal, and then the whole notification goes away.

--- First Animation ---

App Icon
  Start
    Y Position -310
  End
    Y Position 57

App Name:
  Start
    Y Position -270
  End
    Y Position -106

--- Second Animation ---

Long Notification
  Start
    Y Position -475
  End
    Y Position -105

App Icon (before shrinking and translating)
  X Position 0
  Y Position 57
  Width 204
  Height 203

App Icon (after shrinking and translating)
  X Position -94
  Y Position 148
  Width 94
  Height 94