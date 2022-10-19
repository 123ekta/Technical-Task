# Technical-Task
Project
Project Report
On
RESTAURANT MANAGEMENT SYSTEM 



ABSTRACT
	The businesses in restaurants are now growing constantly. At the same time, the need for managing its operations and tasks arises. The best way to optimize these activities is growing the business online as well. Today’s generation encourages high-tech services especially over the Internet.
The project “Restaurant Management System” is implemented to reduce the manual work and enhances the accuracy of work in a restaurant.
RESTAURANT MANAGEMENT SYSTEM is Desktop Application to restaurant management. Hence the project is developed proficiently to help restaurant. This system wake to provide service facility to restaurant and owners automate their BILLING OPERATIONS.
This system entirely reduces the unnecessary time waste inside the hotel as well as it reduces unnecessary calculation.
As per the new rule Goods and Service Tax (GST) levy on both AC and non-AC restaurants to 5%. Every restaurant charges 5% GST breakup as 2.5% State GST (SGST) and 2.5 % Central GST (CGST) without any other service tax and any other VAT charges.. We have developed a RESTAURANT MANAGEMENT SYSTEM with inbuilt GST calculation in the bill, as well as it shows the amount in rupees how much GST is applied.
RESTAURANT MANAGEMENT SYSTEM project fully developed in python language which is currently demanded in market using python GUI Tkinter. Python is a programming language that lets you work quickly and integrate systems more efficiently.


 
INDEX

Sr.No.	TITLE	PAGE NO
1	CHAPTER 1-INTRODUCTION
PYTHON
Python Language Introduction
History of Python
Python Features
Python graphical user interfaces (GUIs)
PYTHON TKINTER GUI 
Tkinter Widgets
Geometry Management
	4 - 10
2	CHAPTER-2 IMPLEMENTATION
Technologies used    
Language used    
CODE OF PROJECT
	11 - 22
3	CHAPTER-3 SCREENSHOTS
	23 - 25
4	CHAPTER-4 CONCLUSION
	26
 
CHAPTER 1-INTRODUCTION
PYTHON 
Python Language Introduction
Python is a widely used general-purpose, high level programming language. It was initially designed by Guido van Rossum in 1991 and developed by Python Software Foundation. It was mainly developed for emphasis on code readability, and its syntax allows programmers to express concepts in fewer lines of code.
Python is a programming language that lets you work quickly and integrate systems more efficiently.
Python is a high-level, interpreted, interactive and object-oriented scripting language. Python is designed to be highly readable. It uses English keywords frequently where as other languages use punctuation, and it has fewer syntactical constructions than other languages.
•	Python is Interpreted − Python is processed at runtime by the interpreter. You do not need to compile your program before executing it. This is similar to PERL and PHP.
•	Python is Interactive − You can actually sit at a Python prompt and interact with the interpreter directly to write your programs.
•	Python is Object-Oriented − Python supports Object-Oriented style or technique of programming that encapsulates code within objects.
•	Python is a Beginner's Language − Python is a great language for the beginner-level programmers and supports the development of a wide range of applications from simple text processing to WWW browsers to games.

History of Python
Python was developed by Guido van Rossum in the late eighties and early nineties at the National Research Institute for Mathematics and Computer Science in the Netherlands.
Python is derived from many other languages, including ABC, Modula-3, C, C++, Algol-68, SmallTalk, and Unix shell and other scripting languages.
Python is copyrighted. Like Perl, Python source code is now available under the GNU General Public License (GPL).
Python is now maintained by a core development team at the institute, although Guido van Rossum still holds a vital role in directing its progress.

Python Features
Python's features include −
•	Easy-to-learn − Python has few keywords, simple structure, and a clearly defined syntax. This allows the student to pick up the language quickly.
•	Easy-to-read − Python code is more clearly defined and visible to the eyes.
•	Easy-to-maintain − Python's source code is fairly easy-to-maintain.
•	A broad standard library − Python's bulk of the library is very portable and cross-platform compatible on UNIX, Windows, and Macintosh.
•	Interactive Mode − Python has support for an interactive mode which allows interactive testing and debugging of snippets of code.
•	Portable − Python can run on a wide variety of hardware platforms and has the same interface on all platforms.
•	Extendable − You can add low-level modules to the Python interpreter. These modules enable programmers to add to or customize their tools to be more efficient.
•	Databases − Python provides interfaces to all major commercial databases.
•	GUI Programming − Python supports GUI applications that can be created and ported to many system calls, libraries and windows systems, such as Windows MFC, Macintosh, and the X Window system of Unix.
•	Scalable − Python provides a better structure and support for large programs than shell scripting.
Apart from the above-mentioned features, Python has a big list of good features, few are listed below −
•	It supports functional and structured programming methods as well as OOP.
•	It can be used as a scripting language or can be compiled to byte-code for building large applications.
•	It provides very high-level dynamic data types and supports dynamic type checking.
•	IT supports automatic garbage collection.
•	It can be easily integrated with C, C++, COM, ActiveX, CORBA, and Java.

Python graphical user interfaces (GUIs)
•	Tkinter − Tkinter is the Python interface to the Tk GUI toolkit shipped with Python. We would look this option in this chapter.
•	wxPython − This is an open-source Python interface for wxWindows http://wxpython.org.
•	JPython − JPython is a Python port for Java which gives Python scripts seamless access to Java class libraries on the local machine http://www.jython.org.
There are many other interfaces available, which you can find them on the net.

PYTHON TKINTER GUI 
Tkinter Programming
 
Tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit.

Creating a GUI application using Tkinter is an easy task. All you need to do is perform the following steps −
•	Import the Tkinter module.
•	Create the GUI application main window.
•	Add one or more of the above-mentioned widgets to the GUI application.
•	Enter the main event loop to take action against each event triggered by the user.

Example
#!/usr/bin/python

import tkinter
top = tkinter.Tk()
# Code to add widgets will go here...
top.mainloop()
This would create a following window −
 

Tkinter Widgets
Tkinter provides various controls, such as buttons, labels and text boxes used in a GUI application. These controls are commonly called widgets.
There are currently 15 types of widgets in Tkinter. We present these widgets as well as a brief description in the following table −
Sr.No.	Operator & Description
1	Button
The Button widget is used to display buttons in your application.
2	Canvas
The Canvas widget is used to draw shapes, such as lines, ovals, polygons and rectangles, in your application.
3	Checkbutton
The Checkbutton widget is used to display a number of options as checkboxes. The user can select multiple options at a time.
4	Entry
The Entry widget is used to display a single-line text field for accepting values from a user.
5	Frame
The Frame widget is used as a container widget to organize other widgets.
6	Label
The Label widget is used to provide a single-line caption for other widgets. It can also contain images.
7	Listbox
The Listbox widget is used to provide a list of options to a user.
8	Menubutton
The Menubutton widget is used to display menus in your application.
9	Menu
The Menu widget is used to provide various commands to a user. These commands are contained inside Menubutton.
10	Message
The Message widget is used to display multiline text fields for accepting values from a user.
11	Radiobutton
The Radiobutton widget is used to display a number of options as radio buttons. The user can select only one option at a time.
12	Scale
The Scale widget is used to provide a slider widget.
13	Scrollbar
The Scrollbar widget is used to add scrolling capability to various widgets, such as list boxes.
14	Text
The Text widget is used to display text in multiple lines.
15	Toplevel
The Toplevel widget is used to provide a separate window container.
16	Spinbox
The Spinbox widget is a variant of the standard Tkinter Entry widget, which can be used to select from a fixed number of values.
17	PanedWindow
A PanedWindow is a container widget that may contain any number of panes, arranged horizontally or vertically.
18	LabelFrame
A labelframe is a simple container widget. Its primary purpose is to act as a spacer or container for complex window layouts.
19	tkMessageBox
This module is used to display message boxes in your applications.

Geometry Management
All Tkinter widgets have access to specific geometry management methods, which have the purpose of organizing widgets throughout the parent widget area. Tkinter exposes the following geometry manager classes: pack, grid, and place.
•	The pack() Method − This geometry manager organizes widgets in blocks before placing them in the parent widget.
•	The grid() Method − This geometry manager organizes widgets in a table-like structure in the parent widget.
•	The place() Method − This geometry manager organizes widgets by placing them in a specific position in the parent widget.

 
CHAPTER-2 IMPLEMENTATION

Technologies used    - Python 3.6.
Python Tkinter GUI 
Language used         - Python

