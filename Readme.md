Gister
======

Installation
------------
chmod +x and symlink to your classpath.

### Example
ln -s ~/projects/ruby/gister/gister ~/bin/gister

Usage
-----

gister -h for help

gister -d "Description here" -v -p file1.rb file2.erl file3.cpp .....

Options
-------
* -v Will output the entire response, aswell as debug output
* -d Add a description.
* -p Make the Gist private.
* -h Display help text.
* -a Make an anonymous gist
* -n No-op, makes no actual calls.
