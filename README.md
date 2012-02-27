
as3-build-xml
=============

Generic Flex Ant build script for our AS3 friends over here.

It builds the as|mxml at the top level of your `src/` folder, using the swc in
your `libs/` and put the generated swf files in your `bin/` folder. The ASDoc is
generated in the `doc/` folder. The Unit Tests classes in `test/` end with Test
and the results, including code quality analysis (by FlexPMD, FlexCPD and
FlexMetrics) is put in `test-reports/` folder.

It is convention based but you can be configured with a `build.properties`
and `build-config.xml` in your project root directory.

*Install in a subfolder*, eg:

    git submodule add https://github.com/4d47/as3-build-xml.git build


todo
----

- make use of html-wrapper
- can we have a portable (windows) deploy task ?

