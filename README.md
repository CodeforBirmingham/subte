# Subte

[![Stories in Ready](https://badge.waffle.io/CodeforBirmingham/subte.png?label=ready&title=Ready)](https://waffle.io/CodeforBirmingham/subte)

## Description 

Subte is an application to manage public transit data. It can create stops, build routes and timetables, and export to [General Transit Feed Specification](https://developers.google.com/transit/gtfs/reference) data which can be used by Google Transit, Open Trip Planner, and others.

This software was developed by [Marcus Dillavou](http://line72.net) to aid in building transite data for the [Birmingham-Jefferson County Transit Authority](http://www.bjcta.org) in Birmingham, AL. For more information, please see the project [website](http://line72.net/index.php/software/subte/)

This software is licensed under the [GPLv3](http://www.gnu.org/licenses/agpl-3.0.html) or later.

## Getting Started

### Installation

To install the project on your operating system for development, please take a look at the [installation guide wiki](https://github.com/CodeforBirmingham/subte/wiki/Installation-Guide)

### Waffle.io

For issue management, we are using [waffle.io](https://waffle.io/CodeforBirmingham/subte) which integrates with github very well. Issues can also be submitted directly via github. Please submit bug reports, features requests, documentation requests, etc, as they come up; they will be addressed as they are able.

### Wiki

The [wiki document](https://github.com/CodeforBirmingham/subte/wiki) is a collection of useful information about the project. It is recommended for users and developers to take a look at the wiki to familiarize with the project usage, plans, and general information. It is still a work in progress, so some information is not yet placed there properly.

### Dependencies

The following are the dependencies used in the project:

* python2.7
* gobject-introspection
* glib (with gobject introspection)
* gtk3 (with gobject introspection)
* clutter (with gobject introspection)
* clutter-gtk (with gobject introspection)
* libchamplain (with gobject introspection)
* libchamplain-gtk (with gobject introspection)
* python-exif
* PIL or python-pillow
* python-lxml
* python-dateutil

## Notes

This project was started as a personal linux desktop client. Since being adopted by [Code for Birmingham](http://www.codeforbirmingham.org/), we have decided to port the program to windows. This is the top priority at the moment and we are hoping to make this program available as soon as practicable.
