# FileBot

The FileBot source code is available for your convenience:

* You may view the source code and learn from it.
* You may build FileBot for private use on unsupported platforms.
* You may NOT use the source code to publish binary builds without explicit authorization.

Please respect the author that is kindly making the source code available under the [MODIFIED DON'T BE A DICK PUBLIC LICENSE](https://github.com/filebot/filebot/blob/master/LICENSE.md).

## Developing

Building a development environment on Windows:

1. Install Eclipse with OpenJDK11 as the default JDK
1. Install OpenJDK11 Standalone (Optional)
1. Set the JAVA_HOME environment variable and add JAVA_HOME\bin to PATH
1. Download and install Apache Ant
1. Set the ANT_HOME environment variable and add ANT_HOME\bin to PATH
1. Install Git for Windows
1. Download Apache Ivy and add the Ivy jar file to ANT_HOME\lib
1. Run `ant resolve` from the filebot directory to download dependencies