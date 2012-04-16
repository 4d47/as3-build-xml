
as3-build-xml
=============

Generic Flex Ant build script for our AS3 friends over here.

It builds the `src/*.{as,mxml}`, using the SWC in your `libs/` and put the
generated SWF files in your `bin/` folder. The ASDoc is generated in `doc/`.
The FlexUnit classes are in `test/` and Mockolate is available, results
including code audit (by FlexPMD, FlexCPD and FlexMetrics) is written
in `test-reports/`.

It is convention based but you can be configured with a `build.properties`
and `build-config.xml` in your project root directory.

*Install in a subfolder*, eg:

    git submodule add https://github.com/4d47/as3-build-xml.git build


todo
----

- make use of html-wrapper ?
- can we have a portable (windows) deploy task ?

