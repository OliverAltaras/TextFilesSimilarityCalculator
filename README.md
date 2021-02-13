# TextFilesSimilarityCalculator

I File Comparator G00387943

File Comparator G00387943 is an application that allows users to input two text files and check how similar they are.

II Launching

To launch it, you must use a command line. Go to the directory where the cosine.jar file is saved.
Once there, enter "java -cp ./cosine.jar ie.gmit.dip.Runner" and the application should start.

III Options

After launching File Comparator G00387943, you will be presented with a menu containing two options:
1 - Compare two files>
2 - Quit>

If you enter 2, the program will shut down immediately. 
If you enter 1, you will then be asked to enter the path to the query and the subject files.
Afterwards, the program will give you a percentage of how similar the files are.

If you enter an invalid input at any time during the program, do not worry: the program will let you know.

IV Design

The application is designed by storing each file into Maps. The words are converted into hashcodes.
The words are then stored as keys and their frequencies are stored as values.
The Maps are then stored as variables and used by a method that calculates the cosine similarity between them. 
The method returns a double between 0.0% and 100.0%. The returned result is displayed on the command line.

The .zip file also contains a directory with the Java docs generated for the program, as well as a .png UML file.
The source code is saved inside the "src" directory.

V About

File Comparator G00387943 was developed by Oliver Kovacevich Altaras in 2020-2021.
It is the final project for the Advanced-Object Oriented Software Development module at GMIT.
The whole source code is commented, and references are noted in the relevant classes.
