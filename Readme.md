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

Options:
    -v Will output the entire response, omit to just get the URL to the gist.
    -d Add a description.
    -p Make the Gist private.
    -h Display help text.
