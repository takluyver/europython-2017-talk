## Use of notebooks

- William: Maths - lectures and assignments.
  - Students work in NB in last 20 mins of lecture
- Kyle: Maths - lecture notes, assignments, exams
  - https://github.com/mandli/intro-numerical-methods
  - https://github.com/mandli/numerical-methods-pdes
  - Has done surveys about notebook effectiveness
  - Mini-problems for students to solve in the lecture
- Robert: Computer science, learning material & assignments
  - Flipped classroom
  - Electronic submission of notebook assignments
- Grant: Lectures, tutorials, homework, projects
- Andrew: Quantum mechanics, materials complementing textbook, in class & homework
  - https://github.com/amcdawes/QMlabs
  - Aiming to be enough for self-guided learning, but some programming knowledge needed
- Harald: Intro to programming, handbook, teaching & assignments
  - Course where lectures were cut, leaving only exercise classes
- Kiran: Maths [like William Stein], course materials & homework
- Ian: Various, inc teaching & exercises
  - Preparing material that is mostly consumed in PDF
- Alisdair: Programming for philosophy, psych & linguistics students
- Brian: Data science, assignments & lectures
  - Flipped class
- Michael: Tech meetup groups, conference tutorials
  - Using bash_kernel & metakernel_bash
  - Several links in email
- Matt: Data science as part of library science, lectures w/ embedded exercises
  - Distributes notebooks by email, would like a better way
- Steve: Chemistry, flipped class exercises, homework
  - Students will have the choice to submit lab reports as notebook or PDF
- Ariel: Workshops for neuroscientists about software tools
  - http://grinberglab.ucsf.edu/python
  - Paper about it: https://arxiv.org/abs/1703.04900
- Nicolas: maths, lectures & computer labs, + Sage tutorials
  - Links to course materials in email
  - Planning to use for teaching C++ as well
- Lex: Comp modelling for biologists, flipped class
  - https://flxlexblog.wordpress.com/2017/03/08/a-new-1st-semester-bachelor-course-introduction-to-computational-modelling-for-the-biosciences-%e2%80%8b/
- SWC: Learning programming, ~1/2 day intro to Python in 2-day workshop
- UCB Data 8: Data science - lectures, textbook examples and assigments
  - http://data8.org/
- Hans: Intro to computing for engineers
  - *Without* notebooks for first part of course

* Popular in maths: familiar with notebook interfaces in other software?
* Data science is becoming a thing

## Extra software

- CoCalc (William): formerly SMC
  - Includes collecting & distributing work, peer grading
  - + Kiran, Steve
  - As a backup solution: Robert, Nicolas
- JupyterHub: Kyle, Alisdair, Brian, Matt, Lex, Data8
- Nbgrader: Kyle, Brian
- Assembly of notebooks into a large latex doc: Harald
- Programmatically generated notebook exercises: Harald
  - inc. detection of similarity between students -> large cluster sharing may
    need attention
- Nbconvert: Ian
- Nbsphinx: Ian
- RISE: Michael
- rst2ipynb https://github.com/nthiery/rst-to-ipynb : Nicolas
- OK autograder (https://okpy.org/): Data8

- None: Robert, Andrew

* JupyterHub is well used
* CoCalc (SMC) also quite popular

## Alternatives

- Blackboard: William, Kyle
- Slides: William, Kyle
- Text files (Python, latex, etc): Robert, Ian, Matt
- IDE: Ian
- Pen & paper?: Andrew
- http://playwithdocker.com/ : Michael
- Maple: Steve
- Mathematica: Steve

## Advantages

- Students engage with material
- Avoids installation problems (hosted env)
- Code for figures available
- Students can provide corrections on Github
- Combines computation, writing, maths
- Students can follow lectures interactively
- Students can tackle harder problems than using pen & paper
  - e.g. problems without neat analytical solutions
- NB exercises can capture more of what the student was doing & thinking than raw code
- Live coding example in lectures
- Run before teaching to check that it still works
- Open source
- Intro to technical computing (Py, Latex) for students who might not get that otherwise

## Disadvantages

- Difficult on a projector with limited resolution
  - Kyle partly switching back to a board
- Installation issues
  - inc setting up git?
- Incompatible changes to the ipynb format
- Problems with notebooks in VCS
- Backup/undo issues
- Problems with large output

- Students delete things they shouldn't
- Not clear if another cell is still running
- Error messages can be confusing
- Variables invisible (no variable explorer)
- Namespace shared by separate examples in one NB
- Output is a 'snapshot' - can be confusing
- Out of order execution
- Cognitive load if students are learning programming alongside a primary subject
  - Also markdown
- Teaching test practices is easier with standard source code
- Don't learn how to run a Python program outside the notebook

- Can be easy to run through a notebook quickly without learning much

## Hosted vs local

### For hosted

- Are people really less likely to keep using a hosted notebook
  - Hosted service *for the course* vs general hosted service (like CoCalc)
  - Limits of free hosted service & willingness to pay for more
- Local installs can give slightly different results, problem for auto-grading
- Students may struggle to set up & maintain a local install
  - Depends on experience level - may be easier for some courses than others
  - Equity: privileges people with prior computational knowledge
- Hosted servers can be used on a tablet or Chromebook
  - Equity: Courses requiring a powerful computer disadvantage some students
- Servers can be provisioned with lots of computational resources
- Can make large datasets available on hosted server
- Nbgrader currently requires hosted system, WIP for working with local installs
- Many people downloading Anaconda at an event can saturate network
- Assignment features integrated in CoCalc

### Neutral

- Self-hosted server: high load during class, v. low at other times
- Local installs when class designed for hosted server can hit problems w
  platform dependent code

### For local

- Wifi issues with large class accessing hosted service
- Local network failures interrupting access to hosted
- Regions where internet access is less available
- Cultural issues around ownership?
- Anaconda made local install much easier than before
- Keeping data after course finishes
- Hosting costs money!
- Highly contested wifi at events such as conferences
- Integrating with lab hardware requires local install

### Specific cases

- Kyle: most students have local install as well
- Robert: students must have local install (1') and CoCalc account (2')
- Andrew: mostly local install; point students to hosted services (SMC/Azure),
  but they mostly prefer local.
- Ian: Local install, would consider university hosted for larger number of students
- Alisdair: Tried local, switched to self-hosted server with JHub
- Michael: lets participants choose where possible
- Matt: Self-hosted JHub, but some students also have local install
  - Plans to show about local installation & use at the end of the course
- Steve: Most students use CoCalc, help available for local Anaconda installs
  - Research students more likely to use local install
- Nicolas: Mostly local, CoCalc as Backup
  - Local JupyterHub planned
- Hans: Anaconda on Uni computers, + students advised to install it
  - Works with a cohort of ~500 students
  
## Misc

- Andrew
  - Best practices docs? Notebook ambassadors?
  - Study how effectiveness of different teaching practices
