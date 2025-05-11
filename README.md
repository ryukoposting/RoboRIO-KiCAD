This repo hosts a KiCAD symbol and footprint for the National Instruments
RoboRIO.

# Adding a RoboRIO To your KiCAD Project

1. Open your KiCAD project in a file browser. You can do this by right-clicking
   on the project, and choosing "Open Directory in File Explorer."

![](/screenshots/01-open-directory.png)

2. Create a folder named "RoboRIO" inside your KiCAD project.
3. Copy the `RoboRIO.pretty` directory, as well as `roborio.kicad_sym` and
   `cd_roborio.stp` into the RoboRIO folder you just created.

![](/screenshots/03-folder-contents.png)

4. Go back to KiCAD, and go to Preferences → Manage Symbol Libraries, then
   choose the "Project Specific Libraries" tab.

![](/screenshots/04-manage-symbols.png)
![](/screenshots/04-project-specific-libraries.png)

5. Use the "+" button to add a new library.
6. Name the Library "RoboRIO," and choose the `roborio.kicad_sym` file for
   "Library Path." The new library should look like this when you're done:

![](/screenshots/05-new-symbol-library.png)

7. Click OK to close the Symbol Libraries window.
8. Go to Preferences → Manage Footprint Libraries. Then, choose the "Project
   Specific Libraries" tab.

![](/screenshots/08-manage-footprints.png)
![](/screenshots/08-project-specific-libraries.png)

9. Use the "+" button to add a new library.
10. Name the library "RoboRIO." and choose the `RoboRIO.pretty` folder for
    "Library Path." The new library should look like this when you're done:

![](/screenshots/09-new-footprint-library.png)

11. You're done!
