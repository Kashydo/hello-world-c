# hello-world-c

Making friends in a new neighborhood is tough. First, learning all those names, then saying hello to all of them!

´Hello Janice!´ ...doesn't it sound better than 'Hello World!'?

What are you going to learn?
Set up your IDE of choice.
Creating a new class.
Instantiate and use object.
build and run.
Run your script from command line with arguments.
Tasks
0%
SHOW ALL CRITERIA
Class creation
Create your own class in the project folder with name App, using the chosen IDE. Make sure that you create the class in the proper folder.

There is a new App class in the src/HelloWorld folder

The namespace is Codecool.HelloWorld

CRITERIA
Use another class
Create a main method (entry point) in the App class (move it from Helloworld.cs), initialize your own instance of HelloWorld in the method, then call the welcome method of the instance. The app must pass its first command line argument to this method.

In class App there is a Main method as the entry point of the program.

There is a HelloWorld instance created in the Main method.

The Welcome method in the HelloWorld instance is called with the first command line argument.

CRITERIA
Compile and run
Compile your source files and run App with a command line argument using the terminal.

The .exe file is generated from source files.

Running the App from the terminal with a command line argument displays Hello <argument>! (for example, the argument "Andrew" prints Hello Andrew! to the output).

CRITERIA
Shell script
Write the commands used for compiling and running your program into the make.sh / make.ps1 file. You can do both actions with one command. Make sure that you can run this file with a command line argument as well.

Previously used commands are saved in script file in separate lines.

Executing make.ps1 with an argument compiles the source code and calls App with the given argument, to perform the Compile and run task in one step.

CRITERIA
Compile and run with IDE
Compile your source files and run App with a command line argument using your chosen IDE.

The .exe file is generated from source files.

Running the App from the IDE with a command line argument displays Hello <argument>! (for example, the argument "Andrew" prints Hello Andrew! to the output).

CRITERIA


Hints
Set command line arguments (parameters) in your IDE. These settings are usually found in the project settings/configuration dialogs.

Find out why running your App class without command line arguments results in an exception.

Browse the connected pages on the left navigation of the articles linked in the Background materials section to read more sub-articles.

Check out the C# code samples on docs.microsoft.com.

Background materials
Introducing docs.microsoft.com
Open project in Visual Studio
.NET Core
How to build your project using .NET Core CLI
How to run your project using .NET Core CLI
Passing parameters to PowerShell script
Introduction to PowerShell

