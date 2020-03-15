** Forked from https://github.com/drewandersen/nemoprofile

NemoProfile
===========
This repository includes sample programs designed to run with the `nemolib` (https://github.com/Kimw6/NemoLib-Java) 
library, specifically to execute the NemoProfile algorithm both sequentially 
and in parallel.

Testing in Linux
-------------
* Install the `nemolib` library, located at: 
https://github.com/Kimw6/NemoLib-Java
* Compile this testing files with the following commands
1) git clone https://github.com/Kimw6/nemoprofile.git
2) Install
   cd sequentialApp
3) Edit compile.sh for the path for nemolib-0.1-SNAPSHOT.jar
4) Edit run.sh for the correct path for nemolib-0.1-SNAPSHOT.jar
5) Compile and run
   ./compile.sh
   ./run.sh ../data/test01 3 100
   
* Each program may have additional requirements found in its README file.

Testing in Windows
-------------
* Install of the `nemolib` library, located at: 
https://github.com/Kimw6/NemoLib-Java
* download the testing files as zip from https://github.com/Kimw6/nemoprofile
* In Netbeans, creat new project as java with existing code. Main folder is sequentialApp
* Add library jar (nemolib-0.1-SNAPSHOT.jar)
* Compile nauty program (the instruction follows) to obtain "labelg.exe"
* Put the "labelg.exe" by following the link that is defined in the "Labeler.jar" from NemoLib
* Right Click the project. Choose "property". Add argument "../data/test01 3 100"
* Then run the project

Compile Nauty
-------------
* NemoLib java is dependent on nauty program for graph label. Therefore, you should have a working "labelg.exe" program in your computer. 
* From http://pallini.di.uniroma1.it/ Download nauty26r10.tar.gz
* If you are using cygwin 
    - Open cygwin-terminal
    - Go to the downloaded folder (for example cd /cygdrive/c/users/Name/programs)
    -Then use as if it is a linux-shell
 * Or if you are using netbeans IDE (using cygwin), just create a project with existing source, will build automatically
 * Locate "labelg.exe" program


Contact
-------
If you have any questions, contact Drew Andersen at drewda81@gmail.com.
