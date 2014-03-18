Sphere Studio Plugin Repository
===============================

This is where you'll find all unofficial contributions to
the Sphere Studio. Anyone can ask to have their plugin featured
here via pull request.

How to Use
==========

Create a clone of this repository. Then create a new .Net project targeting
.Net 4.0 or higher. Link up the two dependencies found in the /Core folder.
These provide the backbone for interacting with the host and Sphere-related files.
Make sure to include any third-party libraries via NuGet in your solution, if not
include them somewhere inside it. See the FastScriptPlugin as an example.

Then you can follow the plugin tutorial here:
https://github.com/Radnen/spherestudio/wiki/How-to:-Plugins

Tip: Copy the Base Plugin and use it as your base for a plugin. That's why it's there!

Plugins
=======

- Base Plugin: Radnen
- Fast Script Plugin: Radnen