# Microwave_Qickcheck_PBT
In this assignment, you'll get some practice at writing property-based tests using junit-quickcheck on the Microwave controller Java program. The goal is to create formal properties for the user requirements that are described as comments in the MicrowaveProperties.java file that is included with the initial project described below.

An initial project is available in the .zip / .tar.gz files below. This project contains a build.gradle file with all of the dependencies necessary to use junit-quickcheck, along with a slightly buggy Microwave model.

Interaction should occur through the InputRecords and OutputRecords as shown in the "Explanation of Test Harnesses" video lecture.

Download and expand the .zip / .tar.gz file (depending on whether you are using Windows or Linux/Mac OS) into a directory of your choice, then to import the project into Eclipse, follow the directions to import gradle projects into Eclipse:

If you want to do things from the command line or from another IDE, you can use gradle directly starting from the build.gradle and settings.gradle file. To install gradle, follow the download and install directions from https://gradle.org/ that are appropriate for your platform. However, in this case you are on your own.

Deliverable

Your task is to complete the MicrowaveProperties.java file to test the Microwave application to ensure it is working properly. There is one bug in the original model. Inside the project, you will find the functional code and a couple of sample properties to get you started. To submit for grading, submit this file.

How will this be graded?

In order to measure the adequacy of your tests, we will run your tests against the bugs in the original model, and a fixed version of the program. The tests should pass on the fixed version and detect the bugs in the buggy version, as well as three additional seeded bugs.

You will get half credit for submitting tests which accurately report a working correct implementation. Then, you get incremental credit for each buggy version your tests successfully identify as not correct. There are 10 buggy mutant programs in total; to receive full credit your program should discover 8 of the bugs.  If you correctly code the properties, your tests should find all the bugs.
