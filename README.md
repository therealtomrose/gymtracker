gymtracker
==========

An app to track my workouts at the gym.


requirements
============

# node.js (google for the binary)
# git (google for the binary)
# cordova: (sudo npm install -g cordova)
# ios-sim: (npm install -g ios-sim)


cloning the repo
================

From the directory above where you want the repo to live:
$ git clone https://github.com/therealtomrose/gymtracker.git gymtracker


initialize repo for phonegap platforms
======================================

$ cordova platform add ios

Verify platforms exist:
-----------------------

$ cordova platforms ls


Building and Simulating the app:
================================

$ cordova emulate ios
