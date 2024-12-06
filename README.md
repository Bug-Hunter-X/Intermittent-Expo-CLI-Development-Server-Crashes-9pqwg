# Expo CLI Development Server Crash Bug

This repository demonstrates a bug where the Expo CLI development server crashes intermittently without providing clear error messages in the console. The application itself builds and functions correctly; the issue is solely confined to the development server.

## Bug Reproduction

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run `expo start`.
4. Observe that after some time (it's unpredictable) the development server will unexpectedly crash without any discernible error message.

## Potential Solutions (Under Investigation)

The root cause of this crash is currently unknown.  Solutions attempted (and unsuccessful) include:

* Reinstalling Expo CLI
* Clearing Expo cache
* Checking for conflicting packages

Any insights or solutions to this issue would be greatly appreciated.  Please feel free to contribute! 
