# Interactive Development Environments Laboratory Work #2

_Recomended tools are marked with **bold**_

_Use a different IDE for each laboratory work_

## GUI Development
  - **Visual Studio**
  - **Xcode**
  - **QTCreator**
  - Code::Blocks

### Prerequisites:
  - IDEs: (one of) Visual Studio, QTCreator, Code::Blocks, Xcode
  - Languages: C/C++, C#, Python or others (depends on IDE)
  - Technologies and Frameworks: Forms, wxWidgets, Win32 API, WinRT API, PyQt or others (depends on IDE, chosen language and target GUI)

> It is 4102. Aliens invaded us. Luckily the world has some great engineers and you are one of them! Your'e working on an unbeatable weapon: Simulatron. Simulatron is an exact copy of alien ship but it has a secret: when the alien gets into ship the alien is traped and brought into human prison. Your task is very simple: you have to clone Simulatron's control panel. World depends on you...

### Mandatory Tasks:
  - Define 3 virtual tasks that you Simulatron is supposed to control
  - Create a GUI application with 5 standard controls (any child window control mentioned in book Windows Programming by Charles Petzold is considered standard)

### Tasks With Points:
  - Add 3 non-standard controls (2pt)
  - Create a custom control (not existent in IDE) (2pt)
  - Make controls to interact. At least 3 interactions (1pt) _ex. on clicking a button a counter should start_
  - Create a _Reset_ button. On clicking this button all controls should go to their default state (1pt)
  - Add a GUI test (1pt)
  - Add a Unit test. For this you'll need to divide your source code in Controller and View (Business and Presentation layer) (2pt)
  - Set a breakpoint in your application and check variables values at that moment of time (1pt)
  - Set debug watches that will not stop your application from running but will allow you to check any application's state (ex. a variable value at some point of time, if a function was called, memory usage) (1pt)
  - Create an installable application (2pt)
  - Create a cross-platform application (1pt) _available only for some IDEs and languages_
  - _Mention your own tasks that you did and claim points for them (max of 5 pt in total)_

### References:
Architecture
  - [Multitier architecture](http://en.wikipedia.org/wiki/Multitier_architecture)
  - [Different User Interfaces - Same Logic](http://qt-project.org/quarterly/view/different_user_interfaces_same_logic)

Custom controls:
  - [Create a custom WPF control](http://msdn.microsoft.com/en-us/library/cc295235.aspx)
  - [Create and Use Custom Control in WPF](http://www.c-sharpcorner.com/UploadFile/sapnabeniwal/create-and-use-custom-control-in-wpf/)

Testing:
  - [Using Testing Tools in VS Professional Edition](http://msdn.microsoft.com/en-us/library/bb385902(v=vs.90).aspx)
  - [Setting up UnitTest++ with Qt Creator in a nice project structure](http://dragly.org/2013/04/19/setting-up-unittest-with-qt-creator/comment-page-1/)
  - [Unit Test Your App](https://developer.apple.com/library/ios/documentation/ToolsLanguages/Conceptual/Xcode_Overview/chapters/UnitTestYourApp.html)
  - [Improving quality with unit tests and fakes](http://s.ch9.ms/Series/Visual-Studio-2012-Premium-and-Ultimate-Overview/Visual-Studio-Ultimate-2012-Improving-quality-with-unit-tests-and-fakes)
  - [Easily testing user interfaces with Coded UI tests](http://s.ch9.ms/Series/Visual-Studio-2012-Premium-and-Ultimate-Overview/Visual-Studio-Ultimate-2012-Easily-testing-user-interfaces-with-Coded-UI-tests)

Creating an installer:
  - [How to create a Setup package by using Visual Studio .NET](http://support.microsoft.com/kb/307353)
  - [Use Advanced Installer for Visual Studio](http://www.advancedinstaller.com/user-guide/tutorial-ai-ext-vs.html)
  - [Qt Installer Framework](http://qt-project.org/doc/qtinstallerframework-1.4/index.html)

### Calculator Examples:
Calculator in Visual Studio 2010:

  - [Video - Simple calculator in Visual Studio](http://www.youtube.com/watch?v=DF2fCWLFSG0)
  - [Video - Calculator In Visual Studio 2010](http://www.youtube.com/watch?v=iTVX6O2L3oc)
  - [Basic Calculator In C#](http://www.dreamincode.net/forums/topic/32968-basic-calculator-in-c%23/)

Calculator in Code::Blocks with wxWidgeets:

  - [Layout management in wxWidgets](http://zetcode.com/tutorials/wxwidgetstutorial/layoutmanagement/)
  - [Video - Create a custom dialog with wxWidgets, CodeBlocks](http://www.youtube.com/watch?v=PzbMEe6xCPI)

Calculator in QTCreator:

  - [Video - Simple calculator tutorial on Qt](http://www.youtube.com/watch?v=Gff6_0-tqUM)
  - [Calculator Example](http://qt-project.org/doc/qt-4.8/widgets-calculator.html)
  
Calculator in PyQt:

  - [Layout management in PyQt4](http://zetcode.com/tutorials/pyqt4/layoutmanagement/)
