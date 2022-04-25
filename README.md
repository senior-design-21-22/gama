# Software Design and Develop I & II
## Team GAMA - Matthew Lang, Alex Heffner, Gavin Dassatti, Aaron Begy
## Roles:
* Team Leader - Matthew Lang
* Release Manager - Gavin Dassatti
* Quality Assurance - Aaron Begy
* Documentation Manager - Alex Heffner

## To Deploy:
Click the link below to launch our project on your web browser! <br />
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/senior-design-21-22/gama/master)

## To Install and Run Locally For Developers: 
  1. Install Pip for installation of jupyter-lab
  2. Install jupyter-lab command
      - Use ```pip install jupyterlab``` on command line to install
      - Link to orignal website: https://jupyter.org/install
  3. Git clone this repository
  4. Run jupyter by typing ```jupyter-lab``` in the terminal while in the directory of the repo
  5. If jupyter notebook doesn't open, you may need to open up a url gave by the terminal in a browser of your choice.

## To Install C++ Kernels Locally for Developers:
Note: At time of making the Xeus-Cling kernel does not support MacOS.

Steps to Install:
  1. Install Miniconda, current version can be found at
    https://docs.conda.io/en/latest/miniconda.html
  2. create enviorment by executing the command ```conda create -n cling```
  3. Activate the enviorment by executing the command ```conda active cling```
  4. Now install Xeus cling by executing the command ```install xeus-cling jupyterlab -c conda-forge```

Xeus-Cling Github: https://github.com/jupyter-xeus/xeus-cling\
Helpful Video: https://www.youtube.com/watch?v=VdkfdBm_6W4

## To Install Rust Kernels Locally for Developers:
  1. Install Rust: https://www.rust-lang.org/tools/install\
    you can do this by executing the command:\
     ```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```
  2. Install EVCXR REPL by executing: ```cargo install evcxr_repl```
  3. Create enviorment by executing: ```conda create --name evcxr```
  4. Activate enviorment by executing: ```conda activate evcxr```
  5. Install conda kernels by executing: ```conda install -y -c conda-forge nb_conda_kernels```
  6. Install evcxr_jupyter by executing: ```cargo install evcxr_jupyter```
  7. Install evcxr_jupyter by executing: ```evcxr_jupyter --install```

Helpful Link: https://depth-first.com/articles/2020/09/21/interactive-rust-in-a-repl-and-jupyter-notebook-with-evcxr/


## To Install Scheme Locally for Developers:
Execute the following commands:
   1. ```pip3 install --upgrade calysto-scheme --user```
   2. ```python3 -m calysto_scheme install --user```
   
   Link to Scheme repo: https://github.com/Calysto/calysto_scheme

## Sci-Java Kernel Notes:
Due to the retirement of the kernel, we were unable to download and test java code locally.

link to Sci-Java Github: https://github.com/scijava/scijava-jupyter-kernel
## Credits
- Credit to Ohio University
- Credit to the Russ College of Engineering
- Credit to the School of Electrical Engineering and Computer Science
- Credit to the faculty and instructors within Ohio University's Computer Science program

## Sprint 1 Code Documentation: 
Configured repository and Jupyter-Lab set up.
Added four main files to the master branch:
  - 1-welcome.ipynb
      - This page is our welcome page for future OU CS students. Purpose - Explain website features and provide code example.
  - cs2400.ipynb
      - This page is our page for CS 2400. Purpose - Provide more information for students about CS 2400 course
  - cs2653.ipynb
      - This page is our page for CS 2653. Purpose - Provide more information for students about CS 2653 course
  - cs3000.ipynb
      - This page is our page for CS 3000. Purpose - Provide more information for students about CS 3000 course

Bug Report: Currently experiencing issues connecting Jupyter Lab to Xeus-Cling C++ Kernel for future use. All code in master branch is bug free.

Code Performance and Testing: Code runs perfectly. Successfully tested on Windows, Linux, and macOS machines.

## Sprint 2 Code Documentation: 
Added four main files to the master branch:
  - cs2401.ipynb
      - This page is our page for CS 2401. Purpose - Provide more information for students about CS 2401 course
  - cs3200.ipynb
      - This page is our page for CS 3200. Purpose - Provide more information for students about CS 3200 course
  - cs3560.ipynb
      - This page is our page for CS 3560. Purpose - Provide more information for students about CS 3560 course
  - cs3610.ipynb
      - This page is our page for CS 3610. Purpose - Provide more information for students about CS 3610 course
      
Also - completed a UI cleanup of all previous files.

Bug Report: Still currently experiencing issues connecting Jupyter Lab to Xeus-Cling C++ Kernel for future use. All code in master branch (and all branches) is bug free.

Code Performance and Testing: Code runs perfectly. Successfully tested on Windows, Linux, and macOS machines.

## Sprint 3 Code Documentation: 
Added six main files to the master branch:
  - cs4000.ipynb
      - This page is our page for CS 4000. Purpose - Provide more information for students about CS 4000 course
  - cs4040.ipynb
      - This page is our page for CS 4040. Purpose - Provide more information for students about CS 4040 course
  - cs4100.ipynb
      - This page is our page for CS 4100. Purpose - Provide more information for students about CS 4100 course
  - cs4420.ipynb
      - This page is our page for CS 4420. Purpose - Provide more information for students about CS 4420 course
  - cs4560and61.ipynb
      - This page is our page for CS 4560 and CS 4561. Purpose - Provide more information for students about CS 4560 and CS 4561 courses
  - ee3713.ipynb
      - This page is our page for EE 3713. Purpose - Provide more information for students about EE 3713 course
      
Also - completed a UI cleanup of all previous files with some suggestions made by our client. Successfully connected xeus cling C++ kernel and Rust kernel to Windows users.

Bug Report: Experiencing issues connecting Jupyter Lab to Xeus-Cling C++ Kernel for MAC USERS ONLY. All code in master branch (and all branches) is bug free.

Code Performance and Testing: All code runs perfectly. Successfully tested on Windows, Linux, and macOS machines.
## Sprint 4 Code Documentation: 
- Now have completed all required CS / EE courses in the CS curriculum.
- Added three main files to the master branch:
  - ee1024.ipynb
        - This page is our page for EE 1024. Purpose - Provide more information for students about EE 1024 course. 
  - ee3613.ipynb
        - This page is our page for EE 3613. Purpose - Provide more information for students about EE 3613 course. This course was not part of this sprint. Extra!!
  - ee3954.ipynb
        - This page is our page for EE 3954. Purpose - Provide more information for students about EE 3954 course. 
- Met with Professor Abukamail. Made changes based off of his suggestions to CS 2400 and CS 4560-61 courses.
- Met with Professor Goble. Incorporated his suggestions in creating EE 1024 and EE 3954 courses. 
- Met with Dr. Ostermann. Made changes based off of his suggestions to CS 4000 and CS 4420 courses.
- Met with Alexander Bagnall. Made changes based off of his suggestions to CS 3200 and CS 4100 courses.
- Researched and prepared for deployment
    - Looked into binder, was unable to deploy due to git repo being private https://mybinder.org
    - Was able to have an instance of deploy using Heroku and viola but had error when trying to reach the site. Unsure of issue at the moment.              
      https://devcenter.heroku.com/articles/getting-started-with-python
    - All 4 of us downloaded and configured Docker to prepare for future deployment
- Also, completed a UI cleanup of all previous files with some suggestions made by our client. Renamed files. 

Bug Report: Experiencing issues connecting Jupyter Lab to Xeus-Cling C++ Kernel for MAC USERS ONLY. All code in master branch (and all branches) is bug free.

Code Performance and Testing: All code runs perfectly. Successfully tested on Windows, Linux, and macOS machines.
## Sprint 5 Code Documentation: 
- Added five main files to the master branch:
  - cs4150.ipynb
        - This page is our page for CS 4150 - Data Science. Purpose - Provide more information for students about CS 4150 course. 
  - cs4250.ipynb
        - This page is our page for CS 4250 - Graphics. Purpose - Provide more information for students about CS 4250 course. 
  - cs4620.ipynb
        - This page is our page for CS 4620 - Databases. Purpose - Provide more information for students about CS 4620 course.
  - cs4800.ipynb
        - This page is our page for CS 4800 - Artificial Intelligence. Purpose - Provide more information for students about CS 4800 course. 
  - ee4683.ipynb
        - This page is our page for EE 4683 - Computer Architecture. Purpose - Provide more information for students about EE 4683 course. 
- Successfully deployed our project with Binder
    - Made GitHub repository public with permission from our client, Dr. Mourning and Professor Abukamail
    - Provided link to Binder deployment at the top of this README file.
    - Automatically opens our JupyterLab project in a new tab on your web browser
    - Thoroughly tested on macOS, Windows, and Linux machines with no bugs
- Completed a UI cleanup of all previous files with some suggestions made by our client.

Bug Report: All code in master branch (and all branches) is bug free.

Code Performance and Testing: All code runs perfectly. Successfully tested on Windows, Linux, and macOS machines.
## Sprint 6 Code Documentation: 
- Added five main files to the master branch:
  - cs1400.ipynb
        - This page is our page for CS 1400 - Fundamentals of Computing. Purpose - Provide more information for students about CS 1400 course. 
  - cs4170.ipynb
        - This page is our page for CS 4170 - Data Mining. Purpose - Provide more information for students about CS 4170 course. 
  - cs4350.ipynb
        - This page is our page for CS 4350 - Game Engine Design. Purpose - Provide more information for students about CS 4350 course.
  - ee4673.ipynb
        - This page is our page for EE 4673 - Embedded Systems. Purpose - Provide more information for students about EE 4673 course. 
  - cs4750.ipynb
        - This page is our page for CS 4750 - Internet Engineering. Purpose - Provide more information for students about CS 4750 course. 
- Converted all CS 2401 examples to C++
- Converted all CS 3610 examples to C++
- Converted all CS 3200 examples to a functional language (Scheme)
- Created documentation for future developers on this project
- Successfully configured the two kernels, Scheme and Java. Both of these kernels also work with Binder.
- Bug Report: All code in master branch (and all branches) is bug free.
- Code Performance and Testing: All code runs perfectly. Successfully tested on Windows, Linux, and macOS machines. Tested on different web browsers.
## Sprint 7 Code Documentation: 
- Added two main files to the master branch:
  - cs2300.ipynb
        - This page is our page for CS 2300 - Computer Programming in Java. Purpose - Provide more information for students about CS 2300 course. 
  - cs4060.ipynb
        - This page is our page for CS 4060 - Computation Theory. Purpose - Provide more information for students about CS 4060 course. 
- Edited CS 4250 - Enabled Graphics functionality displaying various Python graphics to screen.
- Edited CS 4620 - Added a database file with a coding example written in Python
- UI Cleanup - Spelling and grammer changes
- UI Cleanup - Added more visuals to select pages and created headers and footers on each page 
- Security - made text cells uneditable to users
- Bug Report: All code in master branch (and all branches) is bug free.
- Code Performance and Testing: All code runs perfectly. Successfully tested on Windows, Linux, and macOS machines. Also tested on different web browsers.
## Sprint 8 Code Documentation: 
- Added three main files to the master branch:
  - math2301.ipynb
        - This page is our page for MATH 2301 - Calculus I. Purpose - Provide more information for students about MATH 2301 course. 
  - math2302.ipynb
        - This page is our page for MATH 2302 - Calculus II. Purpose - Provide more information for students about MATH 2302 course. 
  - math3200.ipynb
        - This page is our page for MATH 3200 - Linear Algebra. Purpose - Provide more information for students about MATH 3200 course. 
- Edited CS 4170 - Updated data mining examples with new examples relevent to course.
- Edited Welcome Page - Now includes new bubble chart and made other updates.
- Edited CS 2300 - All Java examples are now working with SciJava kernel.
- UI Cleanup - Removed all title (png) pictures and replaced them with HTML text
- UI Cleanup - Fixed grammatical errors and made more cells not editable / not deletable
- Added compatibility of various other kernels
- Various other finishing touches made to project
- Bug Report: All code in master branch (and all branches) is bug free.
- Code Performance and Testing: All code runs perfectly. Successfully tested on Windows, Linux, and macOS machines. Also tested on different web browsers.
