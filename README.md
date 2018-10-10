# B2X300-resources

Resources for your B2X300 3D printer.
Here you'll find extra parts you can add to your printer, printing profiles and others.

## Repository Usage
The `master` branch on this repository is automatically mirrored from BEEVERYCREATIVE's internal git server to GitHub. This means that the `master` branch acts as a *public*.

To develop experimental and instable features you should do so on a *feature*  branch. Feature branches should always be named according to the following convention: `feature/ft-yourfeaturename`.

To merge a *feature* into the `master` branch you should open a merge-request that should be approved by at least peer and must neccessarily go through a Quality Assessment procedure.

To add content to the project, make sure you are in the correct branch and then add or modify the contents of the project according to the following rules:
1. Related files should be grouped under the same folder. 
2. The folder should be archived under the correct category (according to the current file structure). 
3. The name of the folder should be written in english with the first letter of each word capitalized. 
4. The name of the folder should state clearly its contents.
5. Don't save several versions of the same contents. That's what git history is for.
6. In each folder there should always be an instructions file in Markdown ou PDF format on how to use the files.
7. Everytime you include an STL file, please include a render of such file (`fan_support.stl` should have a render called `fan_support.png`) 
