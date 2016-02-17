# Manual configuration

Most of these steps defy automation, though there's probably still some room
for additional plist munging.

## Preflight

- Install Xcode from App Store
- Open and close System Preferences

## Postflight

- Install iWork from App Store
- Manually adjust System Preferences
  - Setup accounts
    - iCloud: disable Calendar, Reminders, and Back to My Mac
    - Google: enable only Calendar
    - Social: disable Share Menu
  - Choose screensaver
  - Turn on FileVault and Firewall
  - Setup notifications
    - Do Not Disturb only when mirroring
    - Disable everything for all but the following
      - Calendar
      - FaceTime
      - Messages
      - Skype
      - Slack
      - TickTick
      - Twitter
  - Arrange external display
  - Set keyboard shortcuts
    - Disable all Launchpad & Dock
    - Enable CTRL-prefixed Mission Control
    - Disable all but next-window focus
    - Disable clipboard Screen Shots
    - Disable all Services
    - Enable all Spotlight
    - Disable all Accessibility
    - Enable all App Shortcuts
  - Setup printers
  - Set computer name and turn off sharing
  - Set network interface service order
  - Turn off most extensions
  - Turn off password hints and parental controls
  - Enable automatic update installation
- Setup Notification Center
  - Today
  - Calendar
  - World Clock
  - Weather
- Adjust Finder sidebar
- Set time zones in Calendar
- Configure installed casks (and record change to defaults)
