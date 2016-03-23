ios-simctl-helpers
==================

Easy to use iOS Simulator scripts. Works with Xcode 7.1 and above.

This repository and its contents are **public domain**. Enjoy!

Included commands:

	sim booted

Prints currently booted iOS simulator.

	sim openurl <URL>

Opens specified URL in currently booted iOS simulator.

	sim getenv <variable name>

Prints out value of specified environment variable in currently booted iOS simulator.

	sim open_app_container <bundle identifier>

Opens in Finder the app container of specified app, which is installed in currently booted iOS simulator.

	sim delete_all_devices

Deletes all iOS simulator devices. Helpful if Xcode automatically creates a bunch of new devices you don't want.
