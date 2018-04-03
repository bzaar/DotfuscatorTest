# DotfuscatorTest

To reproduce the problem:

Install Visual Studio 2015 Community Edition (includes Dotfuscator 5.0)
Install Visual Studio 2017 Community Edition
Build this project with Visual Studio 2017 CE. It should build fine.
Register in AppVeyor.
Create an AppVeyor project to build this repo.
Build in AppVeyor. The build fails: 

https://ci.appveyor.com/project/morpher/dotfuscatortest/build/1.0.3

The goal is to run Dotfuscator as part of the build.

A ticket has been created [here](https://help.appveyor.com/discussions/problems/13462-you-must-first-accept-the-end-user-license-agreement-before-using-dotfuscator).

