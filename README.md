# OpenCSV

**[Update]**: After trying to work with the OpenCSV CSVParser code base and fix some of its pernicious bugs, I gave up and rewrote the whole parser with an eye towards simplifying it.  The result is the [simplecsv](https://github.com/quux00/simplecsv) project.  Please take a look at that project and see if it meets your needs.

This OpenCSV fork is now kaputt.

The open issue filed against the ResultSetHelperService here was fixed in the simplecsv project, but not here.


### Original documentation

This is my fork of the Java OpenCSV project: http://opencsv.sourceforge.net

That project has some traction in the Java community but does not seem to be actively maintained any longer, as there has been a pending 2.4 release that has not be published to maven central and numerous patches, bug fixes and feature requests have been posted over the past 1+ year(s) and not responded to.

I myself added a patch to allow the parser to retain the quote characters.

## Provenance and Status

This is a fork from the OpenCSV SVN repo latest 2.4-SNAPSHOT in August 2013.

I have added:

1. Feature to allow the quote chars to be retained in the output (see below).
2. Added tests to ensure that issue xxx has been fixed (it has): URL
3. Fixed the bug 93 reported here: https://sourceforge.net/p/opencsv/bugs/93/
  1. Note I have not (yet?) applied the patch and feature request made in this bug report


If there is active interest in using this fork, please send pull requests (or patches based on this repo) and file issues here.  I may also go and pull some additional patches and bug reports at the SF site and apply/fix them here.  You are welcome to join me.

I have retained the package names of the opencsv project.



## TODO

1. Test and fix defects listed on sf site: https://sourceforge.net/projects/opencsv/
2. Add documentation on usage


## Copyright notice

Most of the codebase is Copyright 2005 Bytecode Pty Ltd.


## LICENSE

The OpenCSV project on Sourceforge was released under the Apache 2.0 license and this fork is also issued under the same license.  See the LICENSE file for details.
