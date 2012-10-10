fruitstrap
==========
Install and debug iPhone apps without using Xcode.

Designed to work on non-jailbroken devices in a continuous integration environment.

## Requirements

* Mac OS X Snow Leopard or newer (Tested on Mountain Lion 10.8.2).
* You need to have a valid iPhone development certificate installed.
* Xcode must be installed (tested with 4.5), along with the SDK for your iOS version.

## Usage

* `usage: ./fruitstrap [-d/--debug] [-i/--id device_id] -b/--bundle bundle.app [-a/--args arguments] [-t/--timeout timeout(seconds)]` 
* Note: On this fork, the `-d` option will automatically run the app and terminate on completion.

## Installing 

* `make all` will place the fruitstrap binary in the project root. 
* Move the binary any where you would like it.
