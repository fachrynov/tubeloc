::::::::: TubeLoc :::::::::

TubeLoc is an ActionScript 3 library that serves as an adapter to the 
YouTube ActionScript 2 Player API.

Version 0.5.2
Project Homepage: http://code.google.com/p/tubeloc/


::::::::: Project Introduction :::::::::

The project is made up of two types of ActionScript: ActionScript 2, and ActionScript 3.
The ActionScript 2, or "as2" module produces the SWF application that communicates with
the YouTube player.
The ActionScript 3, or "as3" module is meant to be used as a library integrating YouTube
videos into your ActionScript 3 or Flex projects.

MovieSprite.as is a Sprite based class that can be used in ActionScript 3 only projects.
Movie.as is a Flex based component that can be used in Flex projects.

You may only need to build one or the other.
There is a build file at the top-level of this project to build both.
There is a build file for each one separately as well.

Below are the requirements for building the different parts as they come.


::::::::: General Build Requirements :::::::::

Apache Ant 1.7+
http://opensource.adobe.com/wiki/display/flexsdk/Download+Flex+3


::::::::: ActionScript 3 Demo Build Requirements :::::::::

Open Source Flex SDK 3.2+
http://opensource.adobe.com/wiki/display/flexsdk/Download+Flex+3


::::::::: ActionScript 2 Library Build Requirements ::::::::: 

MTASC 1.12+
http://www.mtasc.org/


::::::::: Build Instructions ::::::::: 

1. Make sure Ant is unpacked and in your PATH
2. Make sure the "mtasc" and/or "FLEX_HOME" properties are correct in build file you're using
3. At the command line, "cd" to the module you would like to build (top-level, or "as2"/"as3")
4. Next on the command line, type "ant".
5. Find the build results in a directory named "dist"


January 28, 2009
Ben Longoria, aka enefekt, enefekt@gmail.com

Big thanks for Jeff F. and Phil H. on the YouTube API team for the code reviews and help!