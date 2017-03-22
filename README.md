# GetExperiencedBootcamp
Bootcamp designed to create real world team experience
Homework questions

The theme for these question is definitions.  You have to know what the things are before you can use them.  
1.	What is a software engineer? What do they do?
a.	Software engineering is a field of engineering, for designing and writing programs for computers or other electronic devices. A software engineer, or programmer, writes software (or changes existing software) and compiles software using methods that make it better quality.
2.	How do you become a software engineer?
a.	Get a degree
b.	Learn to program a language
c.	Build software
d.	Find job opportunities
3.	What are the parts of a web application?
a.	Users computer
b.	Internet
c.	Web Server
d.	Database
e.	Http requests
4.	What technologies are used in a web application?
a.	Server-side
1.	Languages/frameworks such as ruby Node.js Python(Django) PHP C# and Java.
2.	database
b.	Client-side
1.	Languages HTML CSS JS
5.	What is HTTP?
a.	Hypertext Transfer Protocol is a application protocol for distributed, collaborative, and hypermedia information systems. Hypertext us structured text that uses logical links (hyperlinks) between nodes containing text
6.	How do you improve at programming?
a.	You improve at programming by practicing building things
7.	What is HTML?
a.	HTML is Hypertext markup language, a standardized system for tagging text files to achieve font, color, graphics, and hyperlink effects on www pages
8.	What is CSS?
a.	A language for describing the presentation of Web pages, including colors, layout, and fonts
9.	What is Javascript?
a.	An object-oriented computer programming language commonly used to create interactive effects within web browsers
10.	What is Linux?
a.	An open source operating system modelled on UNIX
11.	What is CentOS
a.	A Linus distribution that attempts to provide a free, enterprise-class, community-supported computing platform functionally compatible with its upstream source, Red Hat Enterprise Linux
12.	What is SCRUM?
a.	Is a subset of Agile. It is a lightweight process framework for agile development, and the most widely-used one. A “process framework” is a particular set of practices that must be followed in order for a process to be consistent with the framework.
13.	What is Agile?
a.	Agile development is an umbrella term for several iterative and incremental software development methodologies including scrum.
14.	What is QA?
a.	Consistes of a means of monitoring the software engineering processes and methods used to ensure quality.
15.	What is Python?
a.	Is a clear nd powerful object-oriented programming language, comparable to Java
16.	What is Django?
a.	A high-level python web framework that encourages rapid development and clean, pragmatic design
17.	What are web frameworks for?
a.	A software framework that is designed to support the development of dynamic websites the framework aims to alleviate the overhead associated with common activities performed in web development
18.	What is MySQL?
a.	Open source relational database management system
19.	What method was used before agile?  What were the downsides?
a.	The waterfall methodology a sequential(non iterative) design process
b.	You cant add different features mid-way through and it doesn’t account for unseen circumstances that may develop
20.	What is web accessibility?
a.	Is the inclusive practice of removing barriers that prevent interaction with, or access to websites by people with disabilities.
21.	What are design patterns?
a.	Is a general repeatable solution to a commonly occurring problem in software design. A design pattern isn’t a finished design that can be transformed directly into code. It is a description or template for how to solve a problem that can be used in many different situations
22.	What is Git?
a.	A modern version control system
23.	What is Github?
a.	A web-based Git/version control repository and internet hosting service
24.	What is the command line?
a.	A user interface to a computers operatinf system or an application in which the user responds to a visual prompt by typing in a command on a specified line and receives a response back from the system
25.	What is a shell script?
a.	A shell script is a computer program designed to be run by the UNIX shell, a cli the various dialects of shell scripts are considered to be scripting landuages
26.	What is jQuery?
a.	A fast, small, and feature-rich Javascript library
27.	What is Angular?
a.	A structural framework for dynamic web apps. It lets you use HTML as your template language and lets you extend HTML’s syntac to express your application’s components clearly and succinctly


Tasks

Do your best to try and complete these by Thursday.  I will show you how to complete these on Thursday.  There will be no code reviews this week.


1.  Server Administration and Setup

Sign up for AWS account and try to create an EC2 instance running CentOS

2.  Front End Developer 1 (HTML/CSS)

Create a 2 column page with a header, using Bootstrap.  Have links in the left column and a picture with text paragraphs in the right column.  Make the right column 75% width of the page and the left column 25%.  Have a logo in the header the spans the entire page

3.  Front End Developer 2 (Javascript/jQuery/Angular/..)

Create an html page with a button in the middle.  When that button is clicked, alert a message that says "Clicked" and append the word clicked to a div under the button

4.  Backend Developer (Python/Django)

Install Python and Django to your local computer. Have it say hello world on the home page of the django app

5.  Database Administrator

Install Mysql to your local computer.  Create a database with 1 table.  That table should have 3 columns: id, name, created data.  The table should be called names.  Insert 4 names into that table with a sql query and create a query to retrieve just the names from the database

6.  SCRUM Master / System Architect / Project Manager (will touch a little of all the above)


Find out what design pattern Django uses and describe it.  Give and example in pseudo code. 

The design patteren that Django uses is MVC(Model View Controller):

The Model is the representation of the data not the actual data but an interface to the data. It allows you to pull data from the database without know the intricacies of the database. The model also provides the abstraction layer with the database o you can use the same model with multiple databases.

The View is what you actually see. It’s the presentation layer for your model. On the computer the view would be what you see in your browser or for a desktop app its your UI. The view also provides and interface to collect user input.

The Controller is what controls the flow between the model and the view. It uses programmed logic to decide what information is pulled from the database via the model and what information is passed to the view. It also gets information fron the user via the view and implements business logic: either by changing the view, or modifying the data through the model or both.












1	User Input.
2	Invokes model for requested inputs
3	Get response of command from the model
4	Selects a template to display the results to the user requests
5	Response back to the user
