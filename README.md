#### Event Calendar module

---
This repository contains a Drupal 7 module that pulls events information from a calendar. It will then be posted as an internal comment for team members to see.  This module is part of the swarm initiative.

As a new user, these are the recommended step to follow for getting started with this module:

1. Add a new Drupal 7 application to Acquia Cloud
  a. Go to https://insight.acquia.com/subscriptions/add.
  b. Recommended naming `calendarevents{your name}`.
  c. Use the standard Drupal installation.
2. Download and install DevDesktop
3. Add the application to DevDesktop
4. Navigate to the `sites/all/modules` folder.
5. Create and navigate into a new `custom` folder (e.g. `mkdir custom`.)
6. Run `git clone https://github.com/bjkropff/calendar_events.git`.
7. Run `drush cc` from DevDesktop.
8. Install the "Calendar Events" module.

Note: After making any changes be sure to run `drush cc`.