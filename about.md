---
layout: page
title: Syllabus
description: Course policies and information.
---

# Course Syllabus
{:.no_toc}

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Logistics
This is for CS 450, Fall 2022. Lecture is MW 1:50PM-3:05PM in SB104. 

## Course Overview
Operating systems run the world. Without an OS, you couldn't have hundreds of
programs running at once, you'd have to have deep understanding of hardware,
and you'd have to rewrite your code for each new machine on the market. You
wouldn't have web servers, desktop machines, laptops, phones, or smart watches;
no Siri, no Alexa, no TensorFlow or CUDA programs.

In this course, you will dive straight into the deepest and often most
confounding component of a computer system's software stack. You will become
familiar with both the high-level concepts underpinning modern operating
systems and with low-level mechanisms, in addition to new and emerging
techniques and programming models for computer systems. I am a strong believer
in learning by doing, so the majority of your time for this course will be
spent working on programming projects, both very low-level work and high-level
(user-space) work. **This course will be challenging!** It will bring together
a lot of concepts you've learned in your previous courses, from data structures
and algorithms to assembly language, computer architecture, virtual memory, and
advanced C programming.

## Course Goals
My goal with this course is for you to be exposed to and become familiar with the following:
    - Operating system architectures and design trade-offs
    - Programming patterns and sound programming principles for large software systems
    - Virtual memory and resource virtualization
    - Principles underlying the distinction between policy vs. mechanism
    - Principles of End-to-end systems design
    - Concurrency and Safety
    - Concurrency vs. Parallelism
    - Practical debugging
    - I/O Devices
    - File Systems
    - Persistence
    - Non-volatile memories and emerging technologies
    - Future OS directions and trends


## Topics
1. Computer architecture review (3 hours)
2. Virtualization Foundations and Theory (3 hours)
3. Full System Emulation (6 hours)
4. Process Virtual Machines (4 hours)
5. High-level Language Virtual Machines (9 hours)
6. System Virtualization (9 hours)
7. Virtual Machine Management (3 hours)
8. Network Virtualization (3 hours)
9. Lightweight Virtualization and Containers (3 hours)
10. Virtualization Performance and Optimizations (1.5 hours)
11. Current and Future directions (1.5 hours)

## Course Outcomes
- Define the functionality that modern operating systems must provide.
- Articulate design trade-offs inherent in operating system design. 
- Understand the benefits of software modularity and how it applies to OS design.
- Understand the importance of concurrency and how to implement concurrent abstractions correctly in an OS.
- Understand OS scheduling policies and mechanisms (for execution contexts, I/O).
- Understand the benefits and applications of resource virtualization, and how it is achieved by the OS.
- Understand how operating systems implement protection, isolation, and access control.
- Understand the fundamentals of data storage, including file abstractions, file systems, object storage, etc. 
- Understand how OSes employ caching in various ways to improve performance, and how this impacts system complexity.
- Understand and apply programming patterns for efficient systems implementation.

## Prerequisites
You must have taken CS 350 and CS 351. I will only waive this requirement in
truly exceptional cases—this will be a challenging course, and you will need to
already be quite familiar with the fundamentals of computer systems. You should
be comfortable (ideally proficient) with programming in C. I won't take much time to
cover basic C programming.

## Lectures
It is critical you attend class sessions. 

## Textbooks
We will be referring to two textbooks for this course. Both are **freely available online**. We will be using Remzi and Andrea Arpaci-Dusseau's [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) (OSTEP) and the [RISC-V xv6 book](https://pdos.csail.mit.edu/6.828/2021/xv6/book-riscv-rev2.pdf). 

## Readings
For every lecture, I will be posting required readings on the course webpage,
mostly from the OSTEP and xv6 books, but also from other sources. Be sure to read them!
If a reading is marked as required, **the reading content is fair game for
exams**. Any readings I post that are required will be freely available
either from the web or from me. I may post optional/extra reading as well.
These may play into any extra credit I choose to include on exmas.


## Projects
By far the most important part of this course is the projects. You will learn
by doing. Thus, they will comprise the lion's share of your grade. Unless
otherwise noted you will be working individually on projects. Projects will
be generally due at 11:59PM CST on the due date. You can submit as many times
as you like (`make handin`) until then. Your project grades will be calculated
based on the output of `make grade`, and all labs will be weighted equally. 

## Collaboration

See the section on [academic integrity](#academic-integrity). 

**DO NOT** publish your solutions to publicly accessible websites like Github, 
Gitlab or publicly visible file servers. 

## Bad Submissions
If you submit the wrong file or a program that doesn't compile or doesn't run
at all, or one which does not pass any tests, **you will earn a zero for that
project**. It is **your responsibility** to make sure that you submit what you
intend to submit and that you submit a well-formed, compiles-without-errors
codebase. In some cases we will include a suite of tests for you to verify your
work.

## Grading
The grade break-down for the semester is as follows:

- 70% Projects
- 10% Midterm Exam
- 15% Final Exam
- 5% In-Class Participation

## Letter Grade Cut-offs
- A: 90-100
- B: 80-89
- C: 70-79
- D: 60-69
- E: 0-59

## Grading Policies

### Borderline Grades
Roughly nine times out of ten, there's no ambiguity as to what your Final Grade
is; the only judgement comes in at the borders. I will look for every reason I
can find to push you up to the next higher grade, such as: Your Final Exam
score is much higher than the average, or your Final Exam score is higher than
your earlier test scores. In addition, if you're two points short on the Final
Exam, I'll give you the benefit of the doubt. On the other hand, if you're five
points short, you get the lower grade.

## Grading Principles
The Final Grade describes the overall quality of your semester's work:
It all gets piled onto a big scale and my job is to tell you what the Quality
meter says.

For figuring out Final Grades, there are two
ethical/professional principles I must follow. Violating these principles would
be unethical and unprofessional of me and it would cheat the other
students.

**First principle**: Grades can be based only on the quality of
your work. So unfortunately, you can work hard for the course but still earn a
low grade. I'm sorry if a low grade makes your life harder, but that's
absolutely not a reason to raise your grade. 

**The second principle**:
Grading has to be done on a level playing field: I can't give one person
an opportunity that I don't offer to everyone unless it's to re-level the
playing field.  This is why questions like "Can I retake the test or can you
give me some extra work to raise my grade?" have the answer "No."


### Late work policy
Each of you will have a total allocation of 96 late hours for the entire
course. These only apply to the projects (not the exams). You can use these
hours however you want, but be aware of your current quota. For example, if you
submit a project 2 hours late, you will have 94 late hours remaining. If
you submit 4 days late for one project, that will use up all of your late hours.
After you've exhausted your late hours, your grade will be penalized. Beyond
that point, one hour late is the same as one day late.

After you've run out of free late hours, for all projects, you can submit up to three days late with penalties. Each day you will
be docked 10%. So if I have a perfect project, submitting three days late will give me 70%.
**After three days, submissions will no longer be accepted, and you will receive a zero for that project**.

If you have an emergency or are ill, it may be possible to excuse you from a
project or to get you an extension, but you must contact me (or have a
friend or family member contact me) as soon as you can. Please
don't wait until you get well / get back into town / start worrying about your
Final Grade. Overly delayed requests may be denied. Requests made after classes
end will be denied.

## Exams
There will be two exams, a midterm and a final exam. 

## Makeup Exams
If you can't make it to an exam because you're sick or have an emergency, it may be
possible to get you a makeup exam, but contact me (or have a friend
or family member contact me) as soon as you can. Overly delayed
requests may be denied, so don't wait until you get well / get back into town /
start worrying about your Final Grade.  Requests made after classes end will be
denied.

Make-up exams are not a guaranteed right, especially if you ask after
the exam. Barring some urgent reason, you must take tests at the scheduled
time (Getting a cheaper airline ticket is not considered to be an urgent
reason).

If during the test, you feel too ill to finish it, stop and come up and talk to
me so we can work on rescheduling it; don't turn in the test and then
come to me later. Similarly, don't turn in the Final if you want a grade of
Incomplete.

## Regrades

If you think a test or project has been misgraded, then if a TA
graded it, discuss it with that TA first. If you still think it's been
misgraded, discuss it with me. Regrade requests must be 
specific: Don't just ask us to regrade an entire problem or assignment. Also,
you must include your justification for a higher grade: Don't just say you
think you deserve more points. Regrade requests should be timely, else they may
be denied. In particular, regrade requests made after classes end will be
denied.

## Disability Accommodations
Reasonable accommodations will be made for students with documented
disabilities. In order to receive accommodations, students must obtain a letter
of accommodation from the Center for Disability Resources. The Center for
Disability Resources (CDR) is located in Life Sciences Room 218, telephone (312) 567-5744 or disabilities@iit.edu.

## Sexual Harassment and Discrimination Information
Illinois Tech prohibits all sexual harassment, sexual misconduct, and gender
discrimination by any member of our community. This includes harassment among
students, staff, or faculty. Sexual harassment of a student by a faculty member
or sexual harassment of an employee by a supervisor is particularly serious.
Such conduct may easily create an intimidating, hostile, or offensive
environment.

Illinois Tech encourages anyone experiencing sexual harassment or sexual
misconduct to speak with the Office of Title IX Compliance for information on
support options and the resolution process.

You can report sexual harassment electronically
[here](https://iit.edu/incidentreport), which may be completed anonymously. You
may additionally report by contacting the Title IX Coordinator, Virginia Foster
at foster@iit.edu or the Deputy Title IX Coordinator at eespeland@iit.edu.

For confidential support, you may reach Illinois Tech’s Confidential Advisor at
(773) 907-1062. You can also contact a licensed practitioner in Illinois Tech’s
Student Health and Wellness Center at student.health@iit.edu or (312)567-7550

For a comprehensive list of resources regarding counseling services, medical
assistance, legal assistance and visa and immigration services, you can visit
the Office of Title IX Compliance [website](https://www.iit.edu/title-ix/resources).

## Academic Integrity

In short: DO NOT CHEAT! Why would you do that? You're paying for this, so you might as well get 
something out of it. All students are responsible for maintaining the highest level of academic
integrity, as discussed in the [IIT Code of Academic Honesty](http://web.iit.edu/student-affairs/handbook/fine-print/code-academic-honesty)
**The normal penalty for violations of this policy,
especially copying or other cheating during tests, is an E for the course, plus
notification of the student's advisor and/or department and any appropriate
administrators**.

You are allowed to discuss your work with others in the class (we especially
encourage you to do this on Diderot), but ultimately
what you submit must be solely yours. Cheating, plagiarism, copying from other
students, or any other sort of academic dishonesty may result in you getting
a zero on the assignment, may impact your grade negatively, and may result in
referral to the Dean. 

## Disability Accommodations
Reasonable accommodations will be made for students with documented
disabilities. In order to receive accommodations, students must obtain a letter
of accommodation from the Center for Disability Resources. The Center for
Disability Resources (CDR) is located in Life Sciences Room 218, telephone (312) 567-5744 or disabilities@iit.edu.

## Sexual Harassment and Discrimination Information
Illinois Tech prohibits all sexual harassment, sexual misconduct, and gender
discrimination by any member of our community. This includes harassment among
students, staff, or faculty. Sexual harassment of a student by a faculty member
or sexual harassment of an employee by a supervisor is particularly serious.
Such conduct may easily create an intimidating, hostile, or offensive
environment.

Illinois Tech encourages anyone experiencing sexual harassment or sexual
misconduct to speak with the Office of Title IX Compliance for information on
support options and the resolution process.

You can report sexual harassment electronically
[here](https://iit.edu/incidentreport), which may be completed anonymously. You
may additionally report by contacting the Title IX Coordinator, Virginia Foster
at foster@iit.edu or the Deputy Title IX Coordinator at eespeland@iit.edu.

For confidential support, you may reach Illinois Tech’s Confidential Advisor at
(773) 907-1062. You can also contact a licensed practitioner in Illinois Tech’s
Student Health and Wellness Center at student.health@iit.edu or (312)567-7550

For a comprehensive list of resources regarding counseling services, medical
assistance, legal assistance and visa and immigration services, you can visit
the Office of Title IX Compliance [website](https://www.iit.edu/title-ix/resources).
