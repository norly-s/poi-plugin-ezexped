# EZ Exped: Expedition Made Easy

EZ Exped is a [poi](https://github.com/poooi/poi) plugin that helps you
check expedition requirements and estimate expedition income accurately.

## Changelog

[![npm version](https://badge.fury.io/js/poi-plugin-ezexped.svg)](https://badge.fury.io/js/poi-plugin-ezexped)

### 0.3.1

- Adding "All ships need to be sparkled" requirement for great success expeditions

    Exceptions are Expedition 21 / 24 / 37 / 38 / 40 (usually referred to as "overdrum expeditions"),
    For non-overdrum expeditions, it's a requirement that all ships in fleet need to be sparkled.
    However, you can have less than 5 ships in a fleet and still get great success
    given that all regular expedition requirements are met.

- Allow customizing "number of sparkled ships" to `3`.

### 0.3.0

- Allow customizing the number of sparkled ships for great success on non-overdruming expeditions
- Now user can opt-in plugin auto-switch feature.

    This feature is turned off by default. When enabled, poi switches to this plugin automatically
    when user goes to the in-game expedition screen.

### 0.2.3

- Fix errors when not all fleets are unlocked in game

### 0.2.2

- Fix errors caused by missing translations

## Features

### Expedition Requirement Checker

Check your fleet against expedition requirements. Now all you have to do
is to take a look at unmet requirements and adjust your fleet & equipments accordingly.

![](docs/checker1.jpg)

### Accurate Resource Income Estimation

Great Success, all kinds of Daihatsu Landing Craft, their improvement levels
and resupply cost, all taken into account.

![](docs/income1.jpg)

### Auto Switch

Always show you the most related fleet depending on your in-game action:

- Automatically switch to the fleet you are working on (changing fleet composition or ship equipments)
- Automatically switch to the fleet you are about to send out for expedition, allows a last minute confirmation.

### Colorful Fleet Indicator

The Fleet Indicator allows you to tell whether a fleet is ready for the expedition you have specfied
without even taking a close look at it.

![](docs/indicator1.jpg)

- Green: This fleet is ready for the expedition or you cannot send this fleet out for expedition.
- Blue: This fleet is not available, perhaps due to an on-going expedition.
- Orange: This fleet is almost ready for the expedition, all you have to do is to resupply this fleet and send them out again.
- Red: This fleet has some unmet requirements more than just resupply issue.

Note that these colors may vary depending on your theme.
