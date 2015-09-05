
# HelloQt

This example demonstrates how QtCore4 and QtGui4 can be build from pure source files within your Visual Studio solution file without requiring an installation of Qt or Qt's build system.

## Dependencies

* *mare* - A Visual Studio solution file generator.
* *qt* - The Qt sources.
* *libcppqt* - The header files for the Qt libraries, which are normally composed by one of Qt's build scripts.

## Usage

* Create a working copy of the HelloQt repository.
* Initialize submodules.
* Call `generate.bat`. This will compile *mare* and generate solutions files for Visual Studio 2013. You can use `generate.bat --vcxproj=20XX` to generate solution files for another version.
* Open the solution file and compile and work with HelloQt within Visual Studio.

-- Donald Pillou
