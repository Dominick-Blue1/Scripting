#! /usr/bin/env python3
# mapIt.py

# Author: Dominick Blue
# Description: A small command line based script to take in a user address from the clipboard
# and search it on Google Maps.

import webbrowser, sys, pyperclip

if len(sys.argv) > 1:

    address = ' '.join(sys.argv[1:])

else: 

    address = pyperclip.paste()

webbrowser.open('https://www.google.com/maps/place/' + address)



