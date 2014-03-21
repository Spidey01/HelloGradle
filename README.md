This is a simple git repo showing how to use Gradle to build projects in several languages.

	0. java/ 	-> Java example.
	1. c/ 		-> C example (minimalist).
	2. cpp/ 	-> C++ example (advanced).

RESOURCES
---------

	- [Gradle User Guide](http://www.gradle.org/docs/current/userguide/userguide.html)
	
	- [envsetup](https://github.com/Spidey01/envsetup) for shell functions.

UNIX / LINUX / OS X
-------------------

	$ ./gradlew run


WINDOWS
-------
	> .\gradlew.bat run



EXAMPLE OUTPUT
==============

	[ terry@centauri ]$ ./gradlew run
	:c:mainCExtractHeaders UP-TO-DATE
	:c:compileMainExecutableMainC UP-TO-DATE
	:c:linkMainExecutable UP-TO-DATE
	:c:mainExecutable UP-TO-DATE
	:c:installMainExecutable UP-TO-DATE
	:c:run
	Hello, Gradle!
	:cpp:mainCppExtractHeaders UP-TO-DATE
	:cpp:compileX64ReleaseOpensourceMainExecutableMainCpp UP-TO-DATE
	:cpp:linkX64ReleaseOpensourceMainExecutable UP-TO-DATE
	:cpp:x64ReleaseOpensourceMainExecutable UP-TO-DATE
	:cpp:installX64ReleaseOpensourceMainExecutable UP-TO-DATE
	:cpp:run
	Hello, Gradle!
	:java:compileJava UP-TO-DATE
	:java:processResources UP-TO-DATE
	:java:classes UP-TO-DATE
	:java:run
	Hello, Gradle!

	BUILD SUCCESSFUL

	Total time: 4.329 secs
	[ terry@centauri ]$

