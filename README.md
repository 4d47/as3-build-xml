
as3-build-xml
=============

Generic Flex Ant build script for our AS3 friends over here.

It compiles `src/*.{as,mxml}` using the SWCs in `libs/` and put the
generated SWF files in the `bin/` folder. If no src files are found
at the top-level, it assumes it is an archive and compiles a SWC.

The ASDoc is generated in `doc/`. The FlexUnit classes are in `test/` and
Mockolate is available, results including code audit (with FlexPMD, FlexCPD
and FlexMetrics) are written to `test-reports/`. You can use the deploy task,
but make sure ant-jsch.jar and jsch.jar (available in `lib`) are in your
Ant library path.

It is convention based but you can be configured with a `build.properties`
and `build-config.xml` in your project root directory.

*Install in a subfolder*, eg:

    git submodule add https://github.com/4d47/as3-build-xml.git build


