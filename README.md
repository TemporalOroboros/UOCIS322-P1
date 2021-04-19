# UOCIS322 - Project 1 #

## Overview

A small pageserver written in python.
Handles GET requests to supply requested files.
Will reject any request containing the unsafe path elements "..", "//", or "~".
Will reject any request not for a .html or .css file.

## Usage

Run the pageserver.py file using python3 or higher
Send GET requests to the port defined in the credentials.ini or app.ini files.

## Author

Ethan Killen
killen.ethan@gmail.com

### Credits ###

Michal Young, Ram Durairajan, Steven Walton, Joe Istas.
