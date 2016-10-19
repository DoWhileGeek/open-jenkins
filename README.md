# open-jenkins
A command line utility for opening a repositories corresponding jenkins build homepage.

## Installation:

`pip install open-jenkins`

## Usage:
open-jenkins initially asks your jenkins server base url, and saves it. Afterwards it will grab your current directory name, builds a url, and opens it in your default browser.

`$ open-jenkins`

I suggest adding an alias to the tune of:

`alias jenkins="open-jenkins"`
