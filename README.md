# Test repo to Debug Python / GHA / CMake issues

I am attempting to use GitHub Actions to set up a build with a specific version of Python across
several platforms.  This uses the setup_python action to manage the installation.  That should
set the variable pythonLocation pointing at the result.

Next, CMake should use FindPythonLibsNew.cmake to find the version of Python pointed at by
pythonLocation and set some CMake variables appropriately.

This MWE test is set up to make debugging this quicker and hopefully enable others to see a
complete picture of what is being attempted.
