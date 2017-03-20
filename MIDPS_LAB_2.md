# Integrated Development Environments Laboratory Work #2

_Recomended tools are marked with **bold**_

_Use a different IDE for each laboratory work_

## GUI Development
  - **Visual Studio**
  - **Xcode**
  - **QTCreator**
  - Code::Blocks

### Prerequisites:
  - IDEs: Visual Studio, QTCreator, Xcode, Code::Blocks
  - Languages: C/C++, C#, Objective C, Python or others (depends on IDE)
  - Technologies and Frameworks: Forms, wxWidgets, Win32 API, WinRT API, PyQt or others (depends on IDE, chosen language and target GUI)

### Objectives:
  - Make a simple GUI Calculator
  - Default operations are: +,-,*,/,power,sqrt,SignInversion(+/-),operation with decimal floating point.
  - Splitting codebase into two modules: User Interface and Business Logic.

### General Requirements:

  This laboratory work will consist of both mandatory and optional tasks.
  In order to get a passing grade you will have to execute mandatory tasks, present a report, and pass the quiz, given the fact that your work is submitted before deadline.

  _Note:_

  _When writing reports, please do not write it as if I need it, try to write it as if to share your experience with a colleague of yours. I would like to ask you to elaborate on issues you have encountered, logic behind your solutions, and interesting facts that you stumbled upon while executing this work(make sure the facts are relevant to the topic). Moreover, I am asking you to run your reports against a spell checker before submitting it. Please note that a well written report may earn you an extra point._

  _It is only natural for you to find out something new during this laboratory work, therefore do not hesitate to ask questions, however please consider googling first._

  _Gained extra points may be transferred to next laboratory works, given that mandatory tasks were executed._

  _Please use as email subject the following pattern: [TUM][FAF Labs][MIDPS] Name Surname._

### Technical Prerequisites:
  - Modular programming:
    - Business Logic - includes all the functionality that defines the purpose of application
    - GUI module - is a suite of functions that are used for interaction with the user
  - Try to make your application cross platform (Windows,Linux,Mac).

### Laboratory Requirements:

  - Mandatory tasks(mark = 5):
    - Make a simple GUI calculator with basic operations such as +, -, /, *.

  - Optional tasks:
    - Intermediate(each task is worth .5 points):
      - Provide support for the following operations in your application: power, sqrt, SignInversion(+/-).
      - Provide support for operations with decimal floating point numbers.
      - Your program must contain two modules, the GUI module and Business Logic module.
    - Advaned(each task is worth 1.5 point):
      - Work in groups of two(Business Logic & GUI) on a common repo using merge requests.
      - Extract Business Logic module into a library, that can be later used separately, either by another GUI module or from console.
      - Provide a possibility for user to switch between several GUI modules(2+).
      - Plot a graph if user input is a function.

      [Here are some Examples](http://s256376672.websitehome.co.uk/KS_3_Year_8/Y8_KS_3_files/Y8_29_30_Graphs/more_graphs.htm)

      x + y = 4

      and the [Result](http://s256376672.websitehome.co.uk/KS_3_Year_8/Y8_KS_3_files/Y8_29_30_Graphs/2_graph.jpg)

      y = 3x + 1

      and the [Result](http://s256376672.websitehome.co.uk/KS_3_Year_8/Y8_KS_3_files/Y8_29_30_Graphs/1_graph.jpg)
  


### References:
  - [Multitier architecture](http://en.wikipedia.org/wiki/Multitier_architecture)
  - [User Interface Management Systems](https://en.wikipedia.org/wiki/User_interface_management_systems)

### Solved Examples:
Calculator in Visual Studio 2010:

  - [Video - Simple calculator in Visual Studio](http://www.youtube.com/watch?v=DF2fCWLFSG0)
  - [Video - Calculator In Visual Studio 2010](http://www.youtube.com/watch?v=iTVX6O2L3oc)
  - [Basic Calculator In C#](http://www.dreamincode.net/forums/topic/32968-basic-calculator-in-c%23/)

Calculator in Code::Blocks with wxWidgeets:

  - [Layout management in wxWidgets](http://zetcode.com/gui/wxwidgets/layoutmanagement/)
  - [Video - Create a custom dialog with wxWidgets, CodeBlocks](http://www.youtube.com/watch?v=PzbMEe6xCPI)

Calculator in QTCreator:

  - [Video - Simple calculator tutorial on Qt](http://www.youtube.com/watch?v=Gff6_0-tqUM)
  - [Calculator Example](http://doc.qt.io/qt-5/qtwidgets-widgets-calculator-example.html)

Calculator in PyQt:

  - [Layout management in PyQt5](http://zetcode.com/gui/pyqt5/layout/)
