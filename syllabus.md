---
layout: page
title: Syllabus
catalog:  BPHS 3352 / PGEL 4001
credits: 3
semester: Fall 2018
professor: Dr. Jeramia Ory
office: Jones 1544
email: jeramia.ory@stlcop.edu
phone: 314-446-8169
schedule: ['Monday & Wednesday 8:30 - 9:50']
appointment_url: http://drlabratory.com/calendar/schedule-appointment/
office_hours: By appointment
---

## {{ site.title }}

{{ page.catalog }}, {{ page.credits }} Credits, {{ page.semester }}

### Professor

{{ page.professor }}

Office: {{ page.office }}

Email (best way to contact me):
[{{ page.email }}](mailto:{{ page.email }})

Phone: {{ page.phone }}


### Times & Location

{% for class in page.schedule %}
  {{ class }}
{% endfor %}


### Office Hours

Times: {{ page.office_hours }}

Location: {{ page.office_hours_location }}

Appointments: [Click here to schedule an appointment]({{page.appointment_url}})

*Note: my schedule gets busy during the semester, and I've had bad luck setting
office hours that students show up to. I have an open door policy, so please
feel free to stop by at any time. However, if you want to make sure I'll be in
my office, I've cleared 12 hours during the week that are available to make
appointments.  Please try to schedule appointments as far in advance as
possible. In general it will be very difficult to set up appointments less than
24 hours in advance.*

### Website

The syllabus and other relevant class information and resources will be posted
at [{{ site.url}}]({{ site.baseurl }}/).
Changes to the schedule will be posted to this site so please try to check it
periodically for updates.


### Course Communications

Email: [{{ page.email }}](mailto:{{ page.email }})


### Required Texts

There is no required text book for this class.


### Course Description

Computers are increasingly essential to the study of all aspects of
biology. Data management skills are needed for entering data without errors,
storing it in a usable way, and extracting key aspects of the data for
analysis. Basic programming is required for everything from accessing and
managing data, to statistical analysis, to modeling. This course will provide an
introduction to data management, manipulation, and analysis, with an emphasis on
biological problems. Class will typically consist of short introductions or
question & answer sessions, followed by hands on computing exercises. The course
will be taught using R and SQLite, but the concepts learned will easily apply to
all programming languages and database management systems. *No background in
programming of databases is required.*


### Prerequisite Knowledge and Skills

Knowledge of basic biology and chemistry.

### Purpose of Course

In this course you will learn all of the fundamental aspects of computer
programming that are necessary for conducting biological research. By the end of
the course you will be able to use these tools to import data into R, perform
analysis on that data, and export the results to graphs, text files, and
databases. By learning how to get the computer to do your work for you, you will
be able to do more science faster.


### Course Goals and Objectives

Students completing this course will be able to:

* Create well structured databases
* Extract information from databases
* Write simple computer programs in R
* Automate data analysis
* Apply these tools to address biological or pharmaceutical questions
* Apply general data management and analysis concepts to other programming
  languages and database management systems

### Course Project

Projects offer an opportunity to work with bigger data-related computing tasks
and learn specific computing tools you need for your research. Projects can
involve programming, databases, or both. They should be on
something you are excited about.

As a rough guideline projects should represent ~30-40 hours of work. Some class
time will be provided for working on projects.

Get more details about the project from the [Projects Introduction]({{ site.baseurl}}/materials/projects).

### Teaching Philosophy

This class will be taught using a mix of short, introductory lectures and a more
flipped, learner-centered approach. Learning to program and work with data
requires actively working on computers. Flipped classes work well for all kinds
of content, but I think they work particularly well for computer oriented
classes. If you're interested in knowing more take a look at this great
[info-graphic](http://www.knewton.com/flipped-classroom-2/).


### Instructional Methods

Students will be provided with either reading or video
material that they are expected to view/read prior to class. Classes will
involve brief refreshers on new concepts followed by working on exercises in
class that cover that concept. While students are working on exercises the
instructor will actively engage with students to help them understand material
they find confusing, explain misunderstandings and help identify mistakes that
are preventing students from completing the exercises, and discuss novel
applications and alternative approaches to the data analysis challenges students
are attempting to solve. For more challenging topics class may start with 20-30
minute demonstrations on the concepts followed by time to work on exercises.


## Course Policies



### Quiz/Exam Policy

There are no quizzes or exams in this course.

### Attendance
Attendance in highly suggested, the material covered builds on previously discussed information. Please do not expect to be able to put off your reading for three weeks and magically understand everything in one crash study session. I will not provide handouts for a missed class without a formal excuse. There are always legitimate excuses for missing class, however, the definition of “legitimate” is at the discretion of the Dean. As per STLCOP policy:

>“The School of Pharmacy expects student pharmacists to be present for course activities at which attendance is required as noted on a course schedule or syllabus, and to be present for all course-related assessments (e.g., exams, quizzes, case presentations, practicums, etc.).  This is necessary to allow efficient and effective teaching of course material and active learning during class sessions, to show respect for instructors, and to ensure the security of examinations, quizzes, and other types of student assessments. However, the School of Pharmacy also recognizes that there are occasions when student pharmacist attendance at these activities is not possible or prudent. The attached policy is intended to inform P1-P3 student pharmacists of how absence requests and approvals will be processed.  Starting today, all P1-P3 student pharmacists are expected to follow this policy when submitting requests for excused absences from class sessions.  Please note that as stated in the policy, for expeditious processing, requests for excused absences should be directed via email to the Dean’s Office mailbox – not to the Dean of Pharmacy. Emails directed to Dean Canaday, Dean of Pharmacy, may take up to an additional 3 – 5 days for processing.”

### Make-up policy

Late assignments will be docked 20% and will not be accepted more than 48 hours
late except in cases of genuine emergencies that can be documented by the
student or in cases where this has been discussed and approved in advance. This
policy is based on the idea that in order to learn how to use computers well,
students should be working with them at multiple times each week. Time has been
allotted in class for working on assignments and students are expected to work
on them outside of class. It is intended that you should have finished as much
of the assignment as you can based on what we have covered in class by the
following class period. Therefore, even if something unexpected happens at the
last minute you should already be close to done with the assignment. This policy
also allows rapid feedback to be provided to students by returning assignments
quickly.

### Assignment policy

Assignments are generally due by the start of the next class, and will be
specified on the Github Classrooms assignment.

### Course Technology

Students are required to provide their own laptops and to install free and open
source software on those laptops (see [Setup]({{ site.baseurl }}/computer-setup)
for installation instructions). Support will be provided by the instructor in
the installation of required software.

## Academic and General Conduct, Academic Dishonesty
Acts of academic dishonesty are outlined within the Academic Honor Code and Integrity Policy, which will be upheld to the highest standards in this course. For questions related to the Academic Honor Code and Integrity Policy, please contact the Academic Honor Code Committee co-chairs or the Dean of Arts and Sciences.

## Special Accommodations:
If any student has a need for special testing arrangements, note-taking assistance, or other accommodations because of a documented disability, please feel free to discuss this with me privately. Rebecca Jones from the Student Affairs staff will need to evaluate and approve your accommodation needs.

## Correspondance & Social Media
* My typical turnaround for e-mail is 24 hours. If you don’t get an answer after 24 hours please email me again, it may have disappeared from my focus.
* I’m fairly active on twitter, my handle is DrLabRatOry. Feel free to follow (or not), but I don’t follow students back until after graduation. If you want to get to know me and my (dry, horrible, influenced by countless bad 80’s movies) sense of humor, this is probably the best way.
* If you can ask me a question in 140 characters or less, use twitter and tag it #CHEM3320 so others in the class can find it. I’ll probably get back sooner than 24 hours. If people want to live tweet lectures, that’s fine as long as you tag it #CHEM3320.
* I am on facebook, but I do not friend students until they have graduated from the college.


## Grading Policies

Grading for this course will revolve around a combination of assignments (75%)
and an independent project (25%).

All assignments will be equally weighted. One problem from each assignment
(selected at the instructors discretion after the assignments have been
submitted) will receive a thorough code review and a detailed grade. Other
problems will be graded as follows:

* Produces the correct answer using the requested approach: 100%
* Generally uses the right approach, but a minor mistake results in an incorrect
    answer: 90%
* Attempts to solve the problem and makes some progress using the core concept:
    50%
* Answer demonstrates a lack of understanding of the core concept: 0%

Independent projects may focus on databases, programming, or a combination or
the two.

### Grading scale

- **A 93-100**
- **A- 90-92**
- **B+ 87-89**
- **B 83-86**
- **B- 80-82**
- **C+ 77-79**
- **C 73-76**
- **C- 70-72**
- **D+ 67-69**
- **D 60-66**
- **E <60**


## Course Schedule

The details course schedule is available on the course website at:
[{{ site.url }}/schedule]({{ site.baseurl }}/schedule).

**Disclaimer:** This syllabus represents my current plans and objectives. As we
go through the semester, those plans may need to change to enhance the class
learning opportunity. Such changes, communicated clearly, are not unusual and
should be expected.
