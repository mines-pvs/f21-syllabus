CSCI-598 Program Verification & Synthesis, Spring 2020
======================================================

## Course Information

- Lecture Time: Tue Thu 11:00am-12:15am
- In-Person Location: Coolbaugh Hall 131
- Remote Location: [Zoom/YouTube](https://piazza.com/class/kspk2xt3e862wl?cid=7)

## Instructor

[Jedidiah McClurg](https://www.jrmcclurg.com/), Assistant Professor of CS

- Contact: mcclurg (at) mines (dot) edu
- Office Hours: Tue Thu 12:30pm-1:20pm, via [Zoom](https://piazza.com/class/kspk2xt3e862wl?cid=7)

## Teaching Assistant (TA)

(No teaching assistant)

## Course Overview

This course is a hands-on introduction to formal methods. Students will learn how to (1) reason about correctness of programs using first-order logic, temporal logic, and Hoare logic, (2) build tools such as model-checkers to formally verify (exhaustively test) programs written in various languages, and (3) leverage verification functionality to automatically generate (synthesize) correct programs from high-level descriptions of program behavior.

## Prerequisites

There are no official prerequisites, but it is recommended that you
have some familiarity with the material covered in
[CSCI-400 Programming Languages](https://mines-csci400.github.io/f21a-syllabus/).
It is also helpful if you have some basic Linux command-line experience.

## Course Goals

1. Learn several approaches for specifying and reasoning about correctness of programs.
2. Learn how to build *verification tools* to check the correctness of programs.
3. Gain exposure to recent research in the area of *program synthesis*.
4. Apply some verification/synthesis techniques in a domain of interest to you.

## Textbook and Other Reading Materials

NOTE: the following resources are *recommended*, but not required. The
instructor will
assign readings from these sources to supplement our discussions in class,
but our in-class discussions will constitute the "official" version of
the course material.

- [*Logic in Computer Science* by Huth and Ryan](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kspqxc9rxf340d)

The above links will take you to free versions of the materials.


## Schedule

This schedule is tentative, and is subject to change.
Deadlines are at *midnight (Mountain Time)* on the corresponding date.

| week | date   | topic                                                                | lecture notes                                                                            | supplemental reading                                                                                                                                                 | homework                                                                                                                         | project                 |
|------|--------|----------------------------------------------------------------------|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| 1    | Aug 24 | introduction to formal methods                                       | [lecture01](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kspm5khzv5x1fo) |                                                                                                                                                                      | [hw01](https://docs.google.com/forms/d/e/1FAIpQLSfX4-sRtBQEjkOEpRSU-N7SrqGD6rd41exQ8t9dEVPg8N1KNA/viewform?usp=sf_link) assigned |                         |
|      | Aug 26 | natural deduction                                                    | [lecture02](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kszhtcdrkam5ef) | LICS 1.1-1.2                                                                                                                                                         | [hw01](https://docs.google.com/forms/d/e/1FAIpQLSfX4-sRtBQEjkOEpRSU-N7SrqGD6rd41exQ8t9dEVPg8N1KNA/viewform?usp=sf_link) due      |                         |
| 2    | Aug 31 | propositional logic                                                  | [lecture03](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kszhvvj6vpw5oj) | LICS 1.3                                                                                                                                                             |                                                                                                                                  |                         |
|      | Sep 2  | semantics of propositional logic                                     | [lecture04](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kt2bpxbgb484ge) | LICS 1.4                                                                                                                                                             |                                                                                                                                  |                         |
| 3    | Sep 7  | normal forms                                                         | [lecture05](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kt9ikt1k54i6aa) | LICS 1.5                                                                                                                                                             | [hw02](https://github.com/mines-pvs/f21-assignment-hw02) assigned                                                                |                         |
|      | Sep 9  | SAT solving                                                          | [lecture06](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/ktcbe1tkb1u160) | LICS 1.6, [CDCL](http://satassociation.org/articles/FAIA185-0131.pdf)                                                                                                |                                                                                                                                  |                         |
| 4    | Sep 14 | *no class ([career day](https://www.mines.edu/careers/career-day/))* |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
|      | Sep 16 | predicate logic                                                      | [lecture07](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/ktmbs44s1aj28m) | LICS 2.1-2.2                                                                                                                                                         | [hw02](https://github.com/mines-pvs/f21-assignment-hw02) due                                                                     |                         |
| 5    | Sep 21 | proof theory of predicate logic                                      | [lecture08](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/ktt3njvjwud7na) | LICS 2.3                                                                                                                                                             | [hw03](https://github.com/mines-pvs/f21-assignment-hw03) assigned                                                                |                         |
|      | Sep 23 | semantics of predicate logic, SMT solving                            | [lecture09](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kttggwssqnqj0)  | LICS 2.4, [SMT](https://people.eecs.berkeley.edu/~sseshia/pubdir/SMT-BookChapter.pdf)                                                                                |                                                                                                                                  |                         |
| 6    | Sep 28 | linear temporal logic (LTL)                                          | [lecture10](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/ktvnh8del20gr)  | LICS 3.2                                                                                                                                                             |                                                                                                                                  |                         |
|      | Sep 30 | model checking                                                       | [lecture11](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/ktvnhfcvllc15h) | LICS 3.3                                                                                                                                                             | [hw03](https://github.com/mines-pvs/f21-assignment-hw03) due                                                                     |                         |
| 7    | Oct 5  | *no class*                                                           |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
|      | Oct 7  | computation tree logic (CTL)                                         | [lecture12](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kugatbrmfh5566) | LICS 3.4                                                                                                                                                             | [hw04](https://github.com/mines-pvs/f21-assignment-hw04) assigned                                                                |                         |
| 8    | Oct 12 | CTL model checking                                                   | [lecture13](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kunfio57l3t6tj) | LICS 3.6.1                                                                                                                                                           |                                                                                                                                  | project proposal due    |
|      | Oct 14 | LTL model checking                                                   | [lecture14](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kur2mwspk8d77k) | LICS 3.6.3                                                                                                                                                           |                                                                                                                                  |                         |
| 9    | Oct 19 | *no class (holiday)*                                                 |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
|      | Oct 21 | *no class*                                                           |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
| 10   | Oct 26 | program syntax/semantics                                             | [lecture15](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kv7mdqwmzfu68u)                                                                           | LICS 4.1-4.2.1                                                                                                                                                       | [hw04](https://github.com/mines-pvs/f21-assignment-hw04) due                                                                     |                         |
|      | Oct 28 | program verification                                                 | [lecture16](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kvakr5vjzup3ol)                                                                           | LICS 4.2.2-4.2.4                                                                                                                                                     | [hw05](https://github.com/mines-pvs/f21-assignment-hw05) assigned                                                                |                         |
| 11   | Nov 2  | Hoare logic                                                          | [lecture17](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kvalbq1rris4s5)                                                                           | LICS 4.3                                                                                                                                                             |                                                                                                                                  |                         |
|      | Nov 4  | verification conditions                                              | [lecture18](https://piazza.com/class_profile/get_resource/kspk2xt3e862wl/kvg6yed7oyl2d0)                                                                           | [Weakest Preconditions](https://www.lri.fr/~marche/MPRI-2-36-1/2013/poly1.pdf)                                                                                       |                                                                                                                                  |                         |
| 12   | Nov 9  | paper presentation                                                   |                                                                                          | [Combinatorial Sketching for Finite Programs](https://people.csail.mit.edu/asolar/papers/asplos06-final.pdf)                                                         |                                                                                                                                  |                         |
|      | Nov 11 | paper presentation                                                   |                                                                                          | [Sketching Concurrent Data Structures](https://people.csail.mit.edu/asolar/papers/Solar-LezamaJB08.pdf)                                                              |                                                                                                                                  |                         |
| 13   | Nov 16 | paper presentation                                                   |                                                                                          | [Oracle-Guided Component-Based Program Synthesis](http://susmitjha.github.io/papers/icse10.pdf)                                                                      | [hw05](https://github.com/mines-pvs/f21-assignment-hw05) due                                                                     |                         |
|      | Nov 18 | paper presentation                                                   |                                                                                          | [Automating String Processing in Spreadsheets Using Input-Output Examples](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/popl11-synthesis.pdf) |                                                                                                                                  |                         |
| 14   | Nov 23 | *no class*                                                           |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
|      | Nov 25 | *no class (holiday)*                                                 |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
| 15   | Nov 30 | paper presentation                                                   |                                                                                          | [Abstraction-Guided Synthesis of Synchronization](http://www.cs.technion.ac.il/~yahave/papers/popl10.pdf)                                                            |                                                                                                                                  |                         |
|      | Dec 2  | paper presentation                                                   |                                                                                          | [TRANSIT: Specifying Protocols with Concolic Snippets](http://acg.cis.upenn.edu/papers/pldi13_transit.pdf)                                                           |                                                                                                                                  | presentation slides due |
| 16   | Dec 7  | **project presentations**                                            |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
|      | Dec 9  | *no class ("dead day")*                                              |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
| 17   | Dec 14 | *no class (final exam week)*                                         |                                                                                          |                                                                                                                                                                      |                                                                                                                                  |                         |
|      | Dec 16 | *no class (final exam week)*                                         |                                                                                          |                                                                                                                                                                      |                                                                                                                                  | final report due        |

## Homework

There will be approximately 5 homeworks, which will be completed individually.
These are designed to help encourage you to keep up-to-date on the course material.
You will have approximately **2 weeks** to work on each homework.

## Student Paper Presentations

Students will work in groups or individually to thoroughly read one of the program synthesis research papers at the end of the course schedule.
Each group/individual will prepare a detailed (50 min) presentation on the paper, and will lead the class discussion on the corresponding day.
Paper assignments will be finalized shortly after project proposals are due.

## Final Project

Each student will propose a programming project which utilizes a verification/synthesis technique(s) in a domain of interest.
Project proposals are due approximately halfway through the course (week 8).
Each student will give a brief presentation during the last week of class, to describe the project results.
A brief final report will be due at the end of finals week.

## Project Proposal

The purpose of this document is to propose a non-trivial problem related to the topics discussed in the class, and describe the basic steps you will take to develop a software solution. The project proposal should be in PDF format, and should be typeset nicely using LaTeX, Word, LibreOffice, or similar. The report should be 3-4 pages, and should contain *at a minimum* the following sections:
1. *Introduction*: describe the problem you are trying to solve, and discuss the problem's relevance.
2. *Examples*: work through some self-contained examples by hand.
3. *Proposed Approach*: propose a technique/algorithm to solve the problem, and discuss the expected challenges.
4. *Proposed Evaluation*: describe how you will evaluate the correctness/performance of your solution.

Your proposal should provide convincing evidence that (A) the problem is non-trivial, and (B) you have a reasonable plan to tackle the problem. For our purposes, *non-trivial* will mean (roughly) that an *algorithm* needs to be written to solve the problem. For example, implementing a SAT solver by making a single call to Z3 or MiniSAT would be a trivial solution. If any aspect of the proposal is unconvincing, the instructor may require changes that will need to be documented and incorporated into the final project.

## Project Report / Project Code

The purpose of the Project Report is to flesh out the details missing from the Project Proposal -- in particular, you should detail the steps you took to develop your solution, and show how you tested it. The project proposal should be in PDF format, and should be typeset nicely using LaTeX, Word, LibreOffice, or similar. The report should be 6-8 pages, and should contain *at a minimum* the following sections:
1. *Introduction*: describe the problem you solved, and discuss the problem's relevance.
2. *Examples*: work through some self-contained examples, either by hand, or step-by-step using your tool.
3. *Approach*: describe the technique/algorithm you built to solve the problem, and discuss the challenges you encountered.
4. *Evaluation*: describe how you evaluated the correctness/performance of your solution.

The Project Report (an the accompanying Project Code) are due on the last day of the semester (see Schedule). The Code should work on a standard Ubuntu Linux machine. If needed, you can package your code as a VirtualBox VM, so that it can be run on Linux. 

## Project Presentation

We will have short final-project presentations during the final class period. Each presentation time slot will be 10 minutes. Aim for **7-8 minutes** of presentation, and that will leave 2-3 minutes for questions. Please practice your talk to ensure that it falls in the 7-8 minute range, so that we can keep on schedule. Your presentations slides are due the week before the first presentation begins (see Schedule). Please upload your slides in PDF format to your project repository.

In your talk, please be sure to cover each of the 4 elements on the project (Introduction, Examples, Approach, Evaluation). One detailed slide for each of these should be sufficient.

## Online Community and Communication

**In Homework 1, you will be asked to introduce yourself to the instructor. This includes sending
a passport-style photo of yourself to the instructor (or adding one on your Canvas profile).
The photo must be clear, with your face un-obstructed.**
If you are not comfortable providing a photo, then you will need to contact the instructor to set up
a brief in-person meeting to introduce yourself.
Failure to meet this requirement on Homework 1 will result in a 0 (zero) for the Participation component
of the grade.

We will use [Piazza](https://piazza.com/) in the class.
This is a great way to ask questions and communicate with the instructor
and your classmates. Participation on Piazza
will factor into the Participation component of the grade.

The class Piazza link is:
[https://piazza.com/class/kspk2xt3e862wl](https://piazza.com/class/kspk2xt3e862wl)

The instructor will use Piazza to communicate with the class. If you have
questions about the course, you should first do a quick search on the Piazza
page, to make sure your question has not already been answered there. If not,
please go ahead and post your question on Piazza so that the instructor or
another student can answer it publicly. This will help to streamline the
communication.

NOTE: if you have a question you do not wish to publicize (e.g., about
grades, etc.), please create a "private post" on Piazza. **Email should only
be used in rare instances where use of Piazza would not be feasible.**

There is a Github organization for the class:
[https://github.com/mines-pvs](https://github.com/mines-pvs)

All of your individual/team repositories will show up there.

## Class Notes

Class notes will be posted 1-2 days after the lecture.
**Posted notes are not guaranteed to provide all information discussed in lecture**
(class attendance is highly recommended).

## Grading

The following percentages show how final grades will be calculated.
The instructor will *not* perform any rounding on the scores (e.g., a score of
92.999 will not be rounded up to 93).
The instructor may or may not curve the overall
grades, depending on how well the class performs overall, however,
*The instructor expects each student to
work hard, and not rely on the curve!* 

| item             | percentage    |
| -----------------|---------------|
| homeworks        | 45%           |
| presentations    | 20%           |
| final project    | 25%           |
| participation    | 10%           |

Letter grades will be calculated based on the following intervals:

| range    | grade |
|----------|--------------|
| [93,100] | A |
| [90,93)  | A- |
| [87,90)  | B+ |
| [83,87)  | B |
| [80,83)  | B- |
| [77,80)  | C+ |
| [73,77)  | C |
| [70,73)  | C- |
| [67,70)  | D+ |
| [63,67)  | D |
| [60,63)  | D- |
| [0,60)   | F            |

## Late Policy

Late policy: late submissions are accepted up to 5 days after the deadline, with a
penalty of -20% per day applied.

## Attendance

We will not take attendance, but your overall
class attendance will factor into the Participation component of the grade.

## Collaboration

We will use GitHub for collaboration. We will use private individual and team-specific
repositories to submit assignments. Your repositories will show up here:
[https://github.com/mines-pvs](https://github.com/mines-pvs)

## Respectfulness and Academic Honesty

Every student is expected to show respect to the instructors and the rest of the class. This course is preparation
for your future career, so make sure you are behaving with the same level of professionalism that
would be expected at a future full-time position. The general rule of thumb is:
**_informal_ is okay, but _disrespectful_ is not**.

- The instructor prefers to be addressed by "Prof. McClurg" or "Dr. McClurg", but his nickname "Jed" is also fine.
- It is vital that you do your best to be participate in the class, and communicate with the instructor(s) about any course-related difficulties you are facing.

Plagiarism/cheating is NOT acceptable, and will be met with the maximum available penalty.
Sophisticated plagiarism-detection software will be used on every submitted assignment, and
all confirmed instances of cheating will be immediately reported to the Computer Science department.
Please ensure that you do not engage in or facilitate academic dishonesty in this class!

## IMPORTANT CAVEATS

1. **A purely grade-driven approach to taking (graduate) courses is
   at best unnecessary, and at worst highly counterproductive.**
   The volume of grade-related email/questions generated by students
   is typically far too high. As a (graduate) student, your task is
   not to to squeeze every possible point out of the course, your job is to
   learn the material, and be able to use it in the real world (for your
   research, or for your future job, etc.). It's likely that 99% of
   employers are NOT going to care if you have an A versus an A- or B+,
   but they ARE going to care if you can reason about computer science
   concepts, write code, and understand how to build systems.

2. **YOU will determine how much knowledge/experience you gain from this
   course.** The instructor has lots of expertise in the domains covered
   in the course, and will work hard to present you with the resources,
   tools, and techniques to develop a similar skillset. However, education
   is not a pre-packaged box that the instructor can hand out -- YOU
   will need to put in the effort to actively engage with the material,
   participate in class, and work hard on the assignments/projects.

3. **We will take a very formal approach to the topics**, i.e., we will
   carefully develop the mathematical/logical underpinnings of the concepts
   examined throughout the course. Although this may seem dry or boring at
   first, it is very important for you to develop a taste for *being rigorous*
   about computer science. This type of approach will suit you well in your
   future career, regardless of your research area or future career plans.
 
4. **We will learn how to read and absorb highly technical written materials**. 
   Throughout the course, the instructor will work to collect some of the most
   easily-digestible materials for your reference, but a big part of research
   is figuring out things that you don't quite understand at first glance.
   You will need to exercise perseverance in reading research papers, and
   iterate until the pieces start falling into place.

## Course Feedback

Just as you expect the instructor to grade your coursework in a fair and
timely fashion, the instructor expects you to take the Mines course
feedback seriously. Feedback is typically collected during the *two weeks
before finals week*.

As an encouragement to participate in the course feedback, the instructor will
monitor the overall response rate via Canvas -- if the overall response rate
reaches 100%, *all* students in the class will receive bonus points
worth 50% of a homework assignment.

Your feedback is important! The instructor will read all of your comments, and use them to help improve the course/teaching in the future. Rather than simply leaving a numeric rating, please describe your rating in words -- for example, a high score without any indication of what you enjoyed/gained from the class is great but not particularly informative, and a low score without any indication of what went wrong in the class will not help the instructor improve.

Please put yourself in the instructor's shoes, and be **constructive** in
your comments.

## Accommodation

The Colorado School of Mines is committed to ensuring the full participation
of all students in its programs, including students with disabilities. If you
anticipate or experience any barriers to learning in this course, please feel
welcome to discuss your concerns with the instructor. Students with
disabilities may also wish to contact Disability Support Services (DSS) to
discuss options to removing barriers in this course, including how to register
and request official accommodations. Please visit their website at
[https://disabilities.mines.edu](https://disabilities.mines.edu) for contact
and additional information.  If you have already been approved for
accommodations through DSS, please meet with the instructor at your earliest
convenience to discuss your needs in this course.

## Typos and Bug Fixes

Please use the Issues or Pull Request features of GitHub to bring any typos or bugs to the instructor's attention.
