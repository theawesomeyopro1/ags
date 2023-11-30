# Unreleased

## Features
- feat: support print from client with --run-js
- feat: support shebang with --run-file


# 1.5.4

## Features

- add: notificationForceTimeout option
- add: bluetooth device-added, device-removed signal
- add: cursor property
- feat: window popup close on click away
- add: config.onWindowToggled & config.onConfigParsed
- add: marks property setter to slider #186
- feat: --run-js async support
- add: --run-file

## Breaking Changes

- feat: Window.exclusivity
- deprecate: --run-promise cli flag

## Fixes

- overlay pass-through #168