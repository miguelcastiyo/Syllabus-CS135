# Syllabus - CS 135 (Computer Science I)

```
Revision History:
01/12/2024: Original
```

|          |          |
| :-------- | -------- |
| Section(s)    | **4201** (Hybrid) <br> **4202** (Hybrid)    |
| Semester    | Spring 2024    |
| Duration    | 16 Weeks <br> *(16 Jan 2024 — 12 May 2024)*    |
| Weekly Contact Hours <br> <br> | Mondays: 6:00pm-9:50pm (Section 4202) <br> 4 Total <br>  Thursdays: 6:00pm-9:50pm (Section 4201) <br> 4 Total <br>

<br>

# Instructor Information

|          |          |
| :-------- | -------- |
| Instructor    | Miguel Castillo  |
| Office Hours  | Available in-person or virtually on Discord <br> via Appointment   |
| CSN Email    | miguel dot castillo-leyva at csn dot edu   |

I will reply to emails sent to my CSN email address, above, within 48 hours as best I can.
> You must use your CSN email address for official correspondence.

<br>

# Course Description
This course is intended for students in computer science or engineering majors. It covers: <br>
a) Program development in a complex operating environment; <br>
b) Problem-solving methods and algorithm development in a high-level programming language; <br>
c) Program design, coding, debugging, and documentation using techniques of a good programming style.

**Prerequisite(s)**: A grade of C or better in either MATH 127 or MATH 128; or MATH 181 or SAT score of 630 or higher or ACT Math score of 28 or higher.

<br>

# Learning Outcomes
1. Develop algorithmic solutions to problems and translate their algorithms into C++ programs that meet a set of specifications.
2. Compile and execute their programs in the Linux operating environment and use appropriate testing and debugging strategies.
3. Use appropriate control structures (sequence, selection, and iteration) in their programs.
4. Develop modularized programs using functions and passing parameters.
5. Use strings and file streams.
6. Use one-dimensional arrays and records.
7. Use good programming style and adequately document programs.

<br>

# Meeting Times
We will meet in-person on Mondays (Section 4202) or Thursdays (Section 4201) from 6:00pm to 9:50pm. This session is approximately 3 hours lecture and 1 hour lab combined. <br>

We will make use of CSN's Learning Management System, Canvas, for assessments, announcements, discussion forums, and viewing your grades. You can log into the course by going to [https://csn.instructure.com/](https://csn.instructure.com/).

<br>

# Discord Server
Discord is an online application for messaging and audio/video communication. We will make extensive use of Discord this semester. The invitation link to join our server is [https://discord.com/invite/Pn2nhdTf8K](https://discord.com/invite/Pn2nhdTf8K)

<br>

# Late Instructor Policy
When meeting, students must wait for 15 minutes if the instructor is late. The class is excused if the instructor is delayed beyond 15 minutes. Check Canvas for updates.

<br>

# Required Text
- > Malik, D.S. C++ Programming: From Problem Analysis to Program Design, 8th Edition. Cengage, 2017. ISBN-13: 978-1-33710-208-7. Purchase new or used, physical or electronic. We do not use the publisher's online resources (if any). For possible savings, check out [https://www.cengage.com/unlimited](https://www.cengage.com/unlimited). (Note: this same textbook used in CS 202.)
- Shotts, William E. Jr. The Linux Command Line: A Complete Introduction. No Starch Press. 2012. ISBN-13: 978-1-59327-389-7. Download the current edition (free): [http://linuxcommand.org/](http://linuxcommand.org/).

<br>

# Hardware Requirements
You must have access to a Windows, macOS, or Linux computer. <br>
 **Sorry - Chromebooks won't work.**

<br>

# Software Requirements

<p>You will receive login credentials to access the CIT Department's Linux server that has all the tools needed for this course. You will submit assignments through this server. Look for an email at your CSN email address with login information. The server will use your CSN email address for system messages pertinent to your account.</p>

> You must maintain and regularly check your CSN email account for this course! If you do not yet have a CSN email account, go to [https://www.csn.edu/email](https://www.csn.edu/email) to set up your account.

> We will use X2Go Client to access our remote server. This program is free to download and use. Configuration instructions are available at [https://bellagio.csn.edu/~kmess/#!x2goclient.md](https://bellagio.csn.edu/~kmess/#!x2goclient.md) (Note: you must have an established account on the server before you can log in.)

| **Host Operating System**  | **Required Software** |
| ------------------------- | --------------------- |
| Windows    | [http://code.x2go.org/releases/X2GoClient_latest_mswin32-setup.exe](http://code.x2go.org/releases/X2GoClient_latest_mswin32-setup.exe)   |
| macOS    | [http://code.x2go.org/releases/X2GoClient_latest_macosx_10_11.dmg](http://code.x2go.org/releases/X2GoClient_latest_macosx_10_11.dmg)   |
| Linux    | Available from your package manager.  |


The latest edition of the CIT Linux Server Lab Manual is available online at [https://bellagio.csn.edu/doc/labmanual.pdf](https://bellagio.csn.edu/doc/labmanual.pdf) 

<p>CSN provides computer labs for you to complete your work. You may also access the department's Linux server from remotely, e.g., from your home.</p>

> ### The reliability and speed of your Internet connection is solely your responsibility when off-campus.

<br> 

<p>The CSN computer labs each have specific pods of computers that have the X2Go Client software installed. Ask a lab monitor to direct you to the correct pod. You may also use any of the Apple iMac computers.</p>

While you may use any operating system, compiler, or integrated development environment of your choosing, *your programs must compile, build, and execute correctly on the department's Linux server*. Unless specified otherwise, I will compile all programs using the following command:

```
$ g++ $CXXFLAGS source.cpp
```

This class makes use of Canvas, CSN's Learning Management System. You can access Canvas using most modern Web browsers by going to [https://csn.instructure.com/](https://csn.instructure.com/). Some Canvas assessments may require the Respondus Lockdown Browser. This browser is unique to each institution. The link to download Respondus for CSN is [https://download.respondus.com/lockdown/download.php?ID=367436054](https://download.respondus.com/lockdown/download.php?ID=367436054).

> NOTE: The midterm and final exams are proctored. You must take the exams:

- in person in a CSN classroom, one fixed day/time, *or*
- in person at a CSN Testing Center, with an appointment, *or*
- online using Respondus Monitor (requires webcam) at your convenience, *or*
- coordinate with me for alternatives at least three weeks in advance of the scheduled exam.

<br>

# Agenda - Subject to Change

| **Week Number** | **Week Beginning** | **Planned Activity** |
|:--------------|:--------------|:--------------|
| 0x00    | Jan 15, 22<br> <br>    | Martin Luther King Holiday <br> Introduction, Syllabus, Discord, Linux    |
| 0x01    | Jan 22    | Linux, Malik Ch 1 - Overview    |
| 0x02    | Jan 29    | Malik Ch 2 - Basic Elements of C++   |
| 0x03    | Feb 05    | Malik Ch 2 (cont)   |
| 0x04    | Feb 12    | Malik Ch 3 - Input/Output    |
| 0x05    | Feb 19    | President's Day Holiday <br> Malik Ch 4 - Selection    |
| 0x06    | Feb 26    | Malik Ch 5 - Repetition  |
| 0x07    | Mar 04    | Midterm Exam, Chapters 1-5, Linux   |
| 0x08    | Mar 11    | Spring Break   |
| 0x09    | Mar 18    | Malik Ch 6 - User-defined Functions  |
| 0x0a    | Mar 25    | Malik Ch 6 (cont) |
| 0x0b    | Apr 01    | Malik Ch 7 - `std::string` data type    |
| 0x0c    | Apr 08    | Malik Ch 8 - Arrays and Strings    |
| 0x0d    | Apr 15    | Malik Ch 8 (cont)     |
| 0x0e    | Apr 22    | Malik Ch 9 - Structures    |
| 0x0f    | Apr 29    | Malik Ch 9 (cont)    |
| 0x10    | May 06    | Final Exam, Chapters 6-9   |

<br>

## Notes

- Source: [https://www.csn.edu/calendar-catalog-schedule](https://www.csn.edu/calendar-catalog-schedule)
- You may want to subscribe to this class's calendar electronically. While logged into Canvas, open your Calendar and click on the Calendar Feed link.

<br>
<br>

# Policies on late assignments / makeup work

I do not accept late assignments, nor do I provide makeup assignments. You are responsible for your own Internet connection when working remotely. Work ahead if you know you are going to have conflicts or time constraints. Please schedule yourself accordingly.

<br>

# Evaluation methods

I calculate an overall score based on your performance on homework assignments, labs, and assessments. Assessments are scheduled with specific due dates/times. The following weights are applied to determine your course grade:

| **Metric** | **Weight** |
|:-------------------|:-------------------|
|    Programming assignments	  |    20% |
|    Labs  |    10% |
|    Quizzes  |    10%  |
|    Midterm Exam  |    30%  |
|    Final Exam  |    30%  |

Additionally, to pass the course with a grade of C or better, you must (1) **maintain a lab score of 70% or better** and (2) **sit for all exams.**

## How grades are determined

I use the following grading scale applied to your overall score.

| **Letter Grade** | **Overall Score** |
|:-------------------|:-------------------|
|    A	  |    100 to 94% |
|    A-  |    < 94 to 90% |
|    B+  |    < 90 to 87%  |
|    B   |    < 87 to 84%  |
|    B-  |    < 84 to 80%  |
|    C+  |    < 80 to 77%  |
|    C  |    < 77 to 70%  |
|    D+  |    < 70 to 67%  |
|    D  |    < 67 to 64%  |
|    D-  |    < 64 to 61%  |
|    F  |    < 61 to 0%  |

> ### Letter grades shown in Canvas are approximations. I reserve the right to adjust your final grade up/down based on your attendance, participation, and effort.

<p>You may withdraw from the course without academic penalty if you do so by the date published in the academic calendar. Enrollment in the course will appear on your college record, and you will receive a "W" for the class. You should not stop attending the class without officially withdrawing in person or online. Failure to properly withdraw from the class may result in the assignment of an "F" grade to your permanent record.</p>

<br>

# Attendance Policy

Attendance and participation are mandatory.
- Synchronous meetings (classroom): I expect you to be ready at the beginning of the meeting time, heretofore referred to as class time. I do not record attendance at the beginning of each class but our scheduled quiz keeps track of that. Please notify me in advance if you will be late or absent (*things happen, I just want to make sure you don't fall behind as we only meet once per week*).

While not a specific component of your overall score, I use attendance and participation statistics when computing final letter grades. You are responsible for all topics presented in class or posted/discussed in Canvas and our Discord server.

## Additional information unique to the class or instructor
1. We are all adults. You can expect me to treat you with courtesy and respect, and I expect the same from you when interacting with your classmates or me.
2. I like to encourage a casual and friendly atmosphere. In that spirit, please call me Miguel (Mr. Castillo is my dad).

# CSN Standard Syllabus Statement
## Important Note
<p> If you have any concerns about this course and/or me, please contact me first. If I cannot resolve your issue, please contact CIT Department Office at 702-651-5976. You will be directed to the appropriate Program Director or the Department Chair. You will remain anonymous, if possible, and all communications will be strictly confidential. Please DO NOT wait until the last minute to make your concerns known to me and/or to the CIT Department. </p>

## CIT Software Lab
The software lab will be virtual and will be available on August 29, 2022. For location/date/time information, please visit [https://at.csn.edu/cit-information](https://at.csn.edu/cit-information). Click on Networking and Software Lab Hours.

## Counseling and Retention Services
Counselors assist students who are on: academic warning/probation/suspension and financial aid warning/suspension. Counselors prepare academic suspension and financial aid appeals. Counselors help students who are having academic challenges and also those who have been referred by their instructors through the MyCoyotePLAN Early Alert program. Counselors connect students to college and community resources and help them evaluate their options to make informed decisions. For more information about Counseling & Retention Services, please visit: [https://www.csn.edu/counselingdepartment](https://www.csn.edu/counselingdepartment)

## References
Safari Tech Books Online, available through the library, offers an excellent source of supplemental resources that you may use for this course.

To find Safari Tech Books Online, go to the library's Web site at: [https://library.csn.edu](https://library.csn.edu). Click the Databases button. In the A-Z Databases page that appears, click S to filter. The link to Safari Tech Books Online should be at or near the top of the list.

Initially, you will have to enter your CSN student email address, then create an account with Safari Tech Books Online. Subsequently, you will use your email address and your Safari password to access the Safari resources.

## Required extra- or co-curricular activities
All activities are based on projects and exams assigned throughout the course. Any required extra activities will be clearly explained in class.

## Safety
This class does not have an experiment lab and therefore we will not be concerned about following specific safety strategies.

<br>

## Additional fees
There are no additional fees for this course.

## Objectionable materials
<p> Instructors have the responsibility to set and maintain standards of classroom behavior appropriate to the discipline and method of instruction. No objectionable materials or language will be used during this class. This includes all possible modes of the class: online and in person. The instructor will make the final determination regarding any objectionable materials or language. Students may not engage in activity the instructor deems disruptive or counterproductive to the goals of the class. Instructors have the right to remove offending students from class. </p>

# Academic integrity

You are expected to complete your own work in this class. Cheating on exams or lab exercises is not fair to students who are studying honestly. Cheating is also subject to penalties, which can include getting a zero for the assignment or failing the course. The full list of possible penalties is listed in the CSN Student Academic Integrity Policy. Please make yourself familiar with this policy ([https://at.csn.edu/documents/student-academic-integrity-policy](https://at.csn.edu/documents/student-academic-integrity-policy)).

## Stay out of trouble by following these rules:
### **Rule 1: You must not look at solutions or program codes that are not your own.**
<p> It is an act of plagiarism to submit work that is copied or derived from the work of others and submitted as your own. For example, using a solution from the Internet or a solution from another student (past or present) or some other source, in part or in whole, that is not your own work is a violation of the Academic Integrity Policy. Many infractions I see make use of solution code found online. The best way to steer clear of this possibility is not to search for online solutions to the programming assignments. Moreover, looking at someone else's solution code in order to determine how to solve the problem yourself is also an infraction of the Academic Integrity Policy. In essence, you should not be looking at someone else's code in order to solve the problems in this class. This is not an appropriate way to "check your work," "get a hint," or "see alternative approaches." </p>

### **Rule 2: You must not share your solution code with other students.**
<p> In particular, you should not ask anyone to give you a copy of their code or, conversely, give your code to another student who asks you for it. Similarly, you should not discuss your algorithmic strategies to such an extent that you and your collaborators end up turning in the same code. Moreover, you are expected to take reasonable measures to maintain the privacy of your solutions. For example, you should not leave copies of your work on public computers nor post your solution code on websites. </p>

### **Rule 3: You must indicate on your submission any assistance you received.**
If you received aid while producing your solution, you should indicate from whom you got help and what help you received. A proper citation should specifically identify the source (e.g., person's name, book title, website URL, etc.) and a clear indication of how this assistance influenced your work (be as specific as possible). For example, you might write "I discussed the approach used for sorting numbers in the ``sort\_numbers`` function with TA Mary Smith." If you make use of such assistance without giving proper credit, you may be guilty of plagiarism.

It is also important to make sure that the assistance you receive consists of general advice that does not cross the boundary into having someone else write the actual code or show you their code. It is fine to discuss ideas and strategies, but you should be careful to write your programs on your own, as indicated in Rules 1 and 2.

I have no desire to create a climate in which students feel as if they are under suspicion. The entire point of the Academic Integrity Policy is that we all benefit from working in an atmosphere of mutual trust. Students who deliberately take advantage of that trust, however, poison that atmosphere for everyone. I only ask that you be up front and transparent. If you use a Web resource**, just cite the exact source(s). This becomes part of the formal documentation for your program and a ready reference for yourself in the future:

```c++
/// The mathematical constant PI with 15 digits.
/// @see https://en.wikipedia.org/wiki/Pi
const double PI = 3.14159265358979;
```

### **Rule 4: Beware of using Artificial Intelligence Resources**
I am aware of A.I tools such as, but not limited to, ChatGPT. Please refrain from using A.I. tools to complete assignments and to assist on quizzes or exams. My main objective is to prepare students for fruitful careers within the field of computer science. Althouhg A.I. has a place and use, while in the process of learning you should only use it as a reference, not as a leader to write code for you. 

Just be transparent, please. Sneaky behavior destroys trust really quickly.

## Penalties

| **Offense** | **Penalty**|
|:------------|:------------------------------------------------|
| **First**  | You will receive a zero on the assignment, and I will reduce your final course grade by one full letter grade (e.g., if you would have otherwise earned a B+, I will assign a C+ instead). <br> |
| **Second**    | You will receive a failing grade for the course. The class cannot be dropped to avoid the failing grade. |

<br>

# Disability Resource Center (DRC)
<p> The College of Southern Nevada is committed to making physical facilities and instructional programs accessible to students with disabilities. If you have a disability that may have some impact on your work in this class and for which you may require accommodations, please visit the Disability Resource Center (DRC) so that such accommodations can be considered. All discussions will remain confidential. The Disability Resource Center (DRC) has offices at all three campus locations as the focal point for coordination of services for students with disabilities. If you have a physical, emotional, or mental disability that “substantially limits one or more major life activities (including walking, seeing, hearing, speaking, breathing, learning and working),” and will require accommodation in this class, please contact the DRC at WC (702) 651-5644, or email at WCDRCStaff@csn.edu at NLV (702) 651-4045, or email at CYDRCStaff@csn.edu and at HNC (702) 651-3795, or email at HCDRCStaff@csn.edu. For Deaf and Hard of Hearing Services contact (702) 651- 4448, or email at Deaf.HH.Services@csn.edu. Students that receive accommodation letters, please meet with me to discuss the provisions of those accommodations as soon as possible. </p>

# Counseling and Psychological Services (CAPS)
<p> The Counseling and Psychological Services (CAPS offers short-term, problem-focused counseling to CSN students who may feel overwhelmed by the responsibilities of college, work, family, and relationships. Clinicians are available to help students cope with stresses and personal issues that may interfere with their ability to perform in school. The service is provided confidentially and free to currently enrolled students. To schedule an appointment, please call CAPS at WC (702) 651-5518, at NLV (702) 651-4099, and at HN (702) 651-3099. </p>

# Food and Housing Insecurity Support
<p> Any student who has difficulty affording groceries or accessing sufficient food to eat every day, or who lacks a safe and stable place to live, and believes this may affect their performance in the course, is urged to contact Counseling & Psychological Services (CAPS), for a list of resources and support.</p>

# Student rights & responsibilities
When you choose to become a student at CSN, you accept the rights and responsibilities of membership in CSN’s academic and social community. You can find policies covering students such as the Student Conduct, Students’ Right to Know, Students’ Academic Integrity, and Disruptive and Abusive Student in the following locations:
- Catalog and Student Handbook: [https://www.csn.edu/catalog](https://www.csn.edu/catalog) in the Policies and Procedures section.
- CSN Website: [https://www.csn.edu/policies-procedures](https://www.csn.edu/policies-procedures) under the heading “Student Policies.”

# CSN Libraries
CSN Libraries provides support for students completing assignments that require research and the use of information. Librarians are available to students for one-on-one assistance locating and citing quality information either online ([https://library.csn.edu/ask/](https://library.csn.edu/ask/)) or at one of our campus libraries. Find more information on our website ([https://library.csn.edu/](https://library.csn.edu/)).

# Public health directives (COVID-19)
Students must follow all active CSN public health directives while enrolled in this class. CSN public health directives are found at [https://at.csn.edu/covid-19](https://at.csn.edu/covid-19). Students who do not comply with these directives will be asked to leave the classroom. Refusal to follow the guidelines may result in further disciplinary action according to the CSN Student Conduct Code [https://www.csn.edu/sites/default/files/documents/student_conduct_code_policy_1.pdf](https://www.csn.edu/sites/default/files/documents/student_conduct_code_policy_1.pdf),
including being dropped from the course.

<br>

# Recording class 
There are no recordings of the class allowed without the explicit permission of the instructor.
> ### I hereby grant permission.

<br>


# Centers for Academic Success (CAS)
Centers for Academic Success (CAS) provides quality DROP-IN academic assistance to all students enrolled in for-credit courses at CSN. CSN CAS Tutors are available online through Smarthinking, which is accessed in the Canvas online learning management system. View a tutorial video on how to access CSN Tutors/Learning Assistants online at How to Access CSN Tutors in Smarthinking. You may choose “Submit a Question” if you don’t have time for a live session. A Tutor responds to offline questions within 24 hours. Contact us at one of campus phone numbers, and we will assist you with accessing all learning support. Academic learning support includes assistance with placement test preparation, learning strategies, Canvas, Smarthinking online tutoring, Microsoft Office, reading, writing, oral presentations, math, and science. CAS Tutors also provide support in facilitating study groups. You may experience embedded learning assistance in one of your first-year courses. Professors and CAS Staff will make you aware of how to access services as part of your course curriculum. CAS is open Monday through Sunday to be more accessible to all students – Monday – Thursday 9:00 a.m. to 6:00 p.m. and Friday – Sunday 11:00 a.m. to 4:00 p.m. Smarthinking tutors are available 24/7. You may visit [www.csn.edu/centers-academic-success](www.csn.edu/centers-academic-success) for more details or contact us at one of our offices during our regular operational hours: Charleston Centers (702-651-5732), North Las Vegas Learning Commons (702-651-4232), Henderson Learning Commons (702-651-3125).
- Students will receive notification as on-ground tutoring services resume.

<br>

# Early Alert Referral Program
A referral program to connect students with college resources when assistance is needed to achieve success. Referrals may be initiated by faculty and staff as well by students through MyCoyotePLAN. After a referral is submitted, students will receive an email notification and will be contacted by the department to which they were referred to offer assistance.


<br>

# Disclaimer
Information contained in this syllabus is subject to change with notice. I will make an announcement of any change in class and in the college's learning management system for this course. *Please* be sure to read class announcements in the learning management system every time you log in. It is your responsibility to stay informed!

<br>

# Grading Standards
Included as *part of this syllabus* are the following external documents:
- [General Programming Assignment Requirements](https://bellagio.csn.edu/~kmess/#!guidelines.md)
- [Programming Grading Rubric](https://bellagio.csn.edu/~kmess/#!rubric.md)

<br>

/ *EOF* /
