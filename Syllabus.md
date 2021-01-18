## Introduction to Coding Spring 2021 weeks 1-5
### Vic Kelson, _vkelson@indiana.edu_ (office hours by appointment)

### Prerequisites

A desire to enhance your use of computing systems, making you a more productive professional.

### Textbook

_"How to Think Like a Computer Scientist"_ (Miller et al.). The book is available for free as an interactive text with live example code, at this web site (Links to an external site.). A hardcopy or Kindle edition may also be purchased from Amazon at this link (Links to an external site.). I intend to work from the interactive book in class.

### Software

We will be utilizing Python version 3.8, facilitated with an Integrated Development Environment (IDE) called PyCharm Professional. PyCharm provides us with lots of powerful, advanced tools for coding, documenting, and .
For installation on your own laptop, I recommend the use of the Anaconda Python Distribution (Links to an external site.). For the course, we will utilize Jupyter notebooks. I also recommend the use of the Visual Studio Code (Links to an external site.) text editor for more sophisticated code editing.

### Learning Outcomes

The student will understand the essential concepts of computer programming, including computer architecture, data storage and networking
Proficiency in basic Python language scripting for data processing and Jupyter Notebook as a tool for data analysis and inquiry
Basic Python programming practice, including debugging and testing

* Basic data types
* Looping structures
* Functions and modules
* Text processing
* Numerical calculations
* Using external Python libraries
* Accessing external data sets

### Course Assignments

#### Exercises (0%):
Each Tuesday, you will be given an exercise to solve on your own time. I will discuss my solution on the Thursday following. The purpose of the exercises is to give you chances to be coding without grade pressure. I'll try to make the exercises fun!
#### Homework assignments (80%):
Since the goal of the course is to encourage students to include programming and scripting in their daily work, a Homework Assignment will be given every Thursday during the first 4 weeks. 
Each assignment will be in the form of a Jupyter workbook, and the workbooks will be submitted via Canvas. Each assignment will be worth 20 points, and will be due on the Tuesday following the assignment. We will discuss my solution to the problem in class on Tuesday.
#### Making programming part of your personal work flow (20%)
One of the highlights at Pycon, the international Python community conference, are sessions of “lightning talks”. Lightning talks are three-minute presentations, many spontaneously developed during the conference.
Since Each student is expected to seek opportunities to use programming in their personal work or research, our last class session will be a Lightning Talk session devoted to student presentations of a way they’ve used programming during the semester that was unrelated to the programming course. This can be a topic related to other coursework, research, or just a fun outside activity, and can be a Python application or other programming activity. Your lightning talk will be worth 20 points.

### Schedule 
As I write this, I have noticed that the published and amended schedule has 11 days scheduled for this five-week course, and it is usually 10 days. As a result, I'm writing this in terms of the session-number sequence. I'll update to put the calendar in when I know more.

#### Session 1 - Getting started
 * Course introduction
 * Components of a computer and terminology
 * Setting up our computers
 * Using Python as a calculator
 * Writing our own functions for reusable code

#### Session 2 - Scalar data types and more about writing functions
 * The basic scalar types, `int`, `float`, `bool`, `str`, `None`
 * Converting between scalar types
 * Python data types can perform specialized duties: some `str` methods
 * A more formal discussion about writing our own functions
 * Conditional processing with the `if` / `elif` / `else` structure

#### Session 3 - Sequence types and `for` loops
 * Indexing and slicing strings
 * Processing a `str` one character at a time with a `for` loop
 * Introducing sequence types (`tuple` and `list`)
 * Sorting a `list`  
 * Processing sequences with the `for` loop
 * The `for` loop as an expression: list comprehensions
 * Controlling our loops: the `break` and `continue` keywords
 
####Session 4 - Sets and dictionaries, _plus_ the `itertools` module 
 * The `set` type and `set` operations
 * Introducing dictionaries
 * Indexing and accessing dictionaries
 * Looping over dictionaries with the `keys`, `values`, and `items` methods

#### Session 5 - Reading and writing external data
 * A short introduction to character encodings
 * Reading a text file one line at a time or as a whole
 * Reading and processing a large text file
 * Writing textual data to a file
 * Using the Python `csv` module to read, process, and write comma-separated tabuilar data
 * Wrapping file input/output inside of a context manager using the `with` keyword

#### Session 6 - Much ado about the "iterator" protocol
 * What is an iterator and how do I create one?
 * Introducing generators and the `yield` keyword
 * Generator expressions 
 * When should I consider using a generator?
 * Using the `itertools` module for more-powerful looping
 * More about sorting and using the `sorted` generator

#### Session 7 - Making our very own data types
 * What is object-oriented programming, and why would I want to utilize it?
 * Encapsulating data in a custom structured data type with the `class` keyword
 * Adding code (or "methods") to a class
 * Special methods (or "under" methods)

Introducing object-oriented programming via data classes / Methods

#### Session 8
More object-oriented programming / Inheritance and Composition as strategies for building data types.

#### Session 9
Number crunching with the standard math module / Introducing graphs and charts in Jupyter notebooks.

#### Session 10 - Lightning talks!
 * Short student presentations about personal Python applications
 
### Course Policies

#### About the instructor

I am a 1998 SPEA Ph.D. graduate, having studied under Dr. Henk Haitjema. I also hold a B.S. in Chemical and Petroleum-Refining Engineering from Colorado School of Mines. Prior to graduate school, I worked as a process and process-control engineer in the chemical and plastics industries. As part of that work, I developed simulation tools as part of process-improvement projects

After graduate school, I worked for two years at the South Florida Water Management District as a Senior Engineer in the Hydrologic Systems Modeling department. I returned to Bloomington as Chief Modeler for WHPA Inc., a water-supply planning consulting company. In 2008 we sold WHPA to Layne Christensen Company, the largest water-well drilling firm in the US. Our Layne Hydro team conducted numerous water-supply studies, and were awarded the 2015 National Groundwater Supply Project Award by the National Groundwater Association. In April 2016, I left Layne to become the City of Bloomington Utilities Director. CBU is responsible for water supply, wastewater treatment and storm water management in the city of Bloomington.

I am the author of several software products, including the U.S. EPA code WhAEM for Windows, GFLOW, and the open-source AEM code ModAEM. Since 1998, I have done quite a lot of computer programming for hydrological analysis in the Python language, and have taught dozens of scientists and engineers to use Python in their daily work.

Official University Policies:

Students with Learning Disabilities:  Students with a learning disability, hearing impairment, speech impairment, or any other disability that may affect their ability to fulfill a requirement of the College should contact the Disability Services for Students in Franklin Hall 096, (812) 855-7578, prior to registering. Requirements will not be waived for students with disabilities; however, some modifications may be made within specific courses.

Source: http://www.indiana.edu/~college/ado/policies.shtml  

Religious Holidays:  To ensure freedom of religious observance throughout our increasingly diverse population, a set of Calendar Principles were approved by the Bloomington Faculty Council, including a Religious Holidays Policy. This policy requires instructors to make reasonable accommodation when a student must miss an exam or other academic exercise because of a required religious observance. Under IU policy, students are required to request accommodation for religious observance before, not after, it occurs. Instructors should include information about accommodation and the deadline for requesting it in their syllabi. Students are not required to supply evidence of their attendance at the religious services or events in order to qualify for any accommodation granted to them. Source: IU Web Site (Links to an external site.)Links to an external site..

Academic Misconduct:  Academic misconduct is defined as any activity that tends to undermine the academic integrity of the institution. Academic misconduct includes, but is not limited to, the

following: cheating, fabrication, plagiarism, interference, violation of course rules, and facilitating academic dishonesty. The faculty member may take into account the seriousness of the violation in assessing a penalty for acts of academic misconduct. The faculty member must report all cases of academic misconduct to the dean of students, or appropriate official. The university may discipline a student for academic misconduct.

Source: Indiana University Code of Student Rights, Responsibilities, and Conduct -

http://www.dsa.indiana.edu/Code/index1.html 

Sexual Misconduct:

As your instructor, one of my responsibilities is to create a positive learning environment for all students. Title IX and IU’s Sexual Misconduct Policy prohibit sexual misconduct in any form, including sexual harassment, sexual assault, stalking, and dating and domestic violence.  If you have experienced sexual misconduct, or know someone who has, the University can help.

If you are seeking help and would like to speak to someone confidentially, you can make an appointment with:

The Sexual Assault Crisis Services (SACS) at (812) 855-8900 (counseling services)

Confidential Victim Advocates (CVA) at (812) 856-2469 (advocacy and advice services)

IU Health Center at (812) 855-4011 (health and medical services)

It is also important that you know that Title IX and University policy require me to share any information brought to my attention about potential sexual misconduct, with the campus Deputy Title IX Coordinator or IU’s Title IX Coordinator.  In that event, those individuals will work to ensure that appropriate measures are taken and resources are made available.   Protecting student privacy is of utmost concern, and information will only be shared with those that need to know to ensure the University can respond and assist. 

I encourage you to visit stopsexualviolence.iu.edu to learn more.
