Google Static Maps Generator
============================

Documentation
-------------

First see [Google official documentation](https://developers.google.com/maps/documentation/staticmaps/)
to build your informations.

Usage
-----

You have to built your own `$parameters` array in the script.
To get your final URL, you then only have to run the following script in your
shell:
    
    ./generate

On Mac OS X, you can also copy the output in your clipboard using `pbcopy`:

    ./generate | pbcopy 

To-do
-----

* Put the `$parameters` array in a dedicated config file.
* Better manage the multi-marker situation.