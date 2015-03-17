Description:

VRPSolver is a wizard-like application which solves a basic Vehicle Routing Problem (VRP as it is known in the world of Operations Research) using the Savings Heuristic Method invented by Clarke and Wright in 1964.
A basic VRP consists of one warehouse and several nodes each of which has a demand to be fulfilled by delivery trucks based in the warehouse. These trucks will have a maximum capacity. The objective of solving this problem is to find the minimum number of routes which will add up to having the minimum total distance which will also maximize the utilization of truck capacity. This in turn would ensure the least distribution cost for the company.
Solving this problem requires a lot of effort if done manually because the complexity of this problem increases exponentially with each additional node. Another difficulty faced by users is that the solution needs to be recalculated each time a node is added or removed, location's demand changes, etc.

Objective:

The objective of this project is to develop a software application which would automate this calculation process and make it flexible and practically usable by any BUSINESS which have such delivery processes. This application would also be useful to STUDENTS in the field of OPERATIONS RESEARCH.

Prerequisits:

Microsoft .NET Framework ver2.0. You may download it from the following link:
http://www.microsoft.com/downloads/details.aspx?FamilyID=0856eacb-4362-4b0d-8edd-aab15c5e04f5&displaylang=en
Or just google for it :-)

Technicalities:

This project is written in C#(.NET Framework 2.0) in order for it to be able to be ported to Linux using mono. So the windows version will need the Microsoft .NET Framework installed in the computer. It is currently targeted for 32 bit Windows 2k and above but further development could easily enable it to be ported to Linux.
The C# solution has five sub projects, Which are as follows,

1. libConfigFile
> This provides a library of functions which enable anyone to read and manipulate data stored inside configuration files which hold saved data of the application. This library is also useful for anyone interested in MANIPULATING XML files for their own purposes.

2. libVRPSolver
> This is the main library of the application. Anyone could develop THEIR OWN vrp application using this library by using its functions which HIDE the complexity of the calculation process.

3. libWizard
> This library provides two base classes for DESIGNING WIZARDS easily.

4. libPrint
> This provides a set of classes and functions which aim to facilitate all printing tasks in the solution.

3. VRPSolver
> This project provides a flexible and easy wizard based UI to the user to enter data and view, export, print, etc. the solution. It also provides the facility for the user to save his/her work at any given step. This project also DEMONSTRATES the use of the libraries mentioned above.

4. VRPSolverSetup
> The windows setup project for VRPSolver application based on the Windows installer.

License:

The application is to be used under the GNU GPL.