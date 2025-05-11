This repo hosts a KiCAD symbol and footprint for the National Instruments
RoboRIO.

# Adding a RoboRIO To your KiCAD Project

1. Go to the [Releases] page and download the latest RoboRIO.zip file.

[Releases]: https://github.com/ryukoposting/RoboRIO-KiCAD/releases

2. Open your KiCAD project in a file browser. You can do this by right-clicking
   on the project, and choosing "Open Directory in File Explorer."

    ![](/screenshots/01-open-directory.png)

3. Unzip the RoboRIO.zip into the project folder. A new folder named `RoboRIO`
   should appear in your project:

    ![](/screenshots/03-folder-extracted.png)

   Inside that folder, you should see two files `roborio.kicad_sym` and
   `cd_roborio.stp`, and a folder `RoboRIO.pretty`:

    ![](/screenshots/03-folder-contents.png)

    If you don't see the above contents (ex: maybe there's a folder called
    RoboRIO inside another folder called RoboRIO) the rest of this procedure
    won't work.

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

Now, you will be able to use the RoboRIO KiCAD symbol and PCB footprint in your
KiCAD project!
