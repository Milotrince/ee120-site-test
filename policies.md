---
layout: page
title: Policies
nav_order: 2
description: >-
    Course policies and information.
---

{%- if site.under_construction -%}
<p class="warning">
This site is under construction. All dates and policies are tentative until this message goes away.
</p>
{%- endif -%}

# Policies
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.854 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Tue Jan 17 2023 10:48:16 GMT-0800 (PST)
* Source doc: Syllabus
----->



## Communication

All official course communication will be through Ed and bCourses. We will also maintain the course website for your convenience.

For any administrative concerns, please **email** **[ee120-sp23-admin@lists.berkeley.edu](mailto:ee120-sp23-admin@lists.berkeley.edu)** **with [EE 120] in the subject line**. This will reach both Babak and the head TAs, Naomi and Yousef. 

For emergency communication during exams, email **[ee120-sp23@lists.berkeley.edu](mailto:ee120-sp23@lists.berkeley.edu)**. This reaches all staff, including Babak.


## Gradescope

All assignments will be submitted through Gradescope. The code to join can be found on Ed.


## Lecture

**Time**: Mon/Wed 3-5pm

**Location**: Physics Building 4 (directly east of the Campanile; the room should be near the entrance to the building)

**Recordings**: Will be posted to the course website and “Lecture Index” Ed thread.

**Lecture Threads**: There will be an Ed thread for each lecture where you can ask questions about lecture topics.


## Discussion

There are 4 discussion sections, all on Friday. **You can attend any discussion time you would like as long as it is not oversubscribed**.

Discussions will be in-person, but we will post worksheet walkthrough videos after discussion. Walkthrough videos will be available in the Media Gallery on bCourses.

We will post the worksheet to bCourses and Ed on Friday mornings, along with the TAs that will teach discussion that week.

**Times and Locations:**



* Fri 11am-12pm in Cory 540AB
* Fri 12-1pm in Wheeler 30
* Fri 1-2pm in Wheeler 30
* Fri 2-3pm in Wheeler 130

**Note: we will not be offering the Fri 8-9am option**.

**Attendance**: We do _not_ take attendance for lecture or discussion. That being said, we highly recommend that you attend both as frequently as possible to stay caught up with the material.

**The first discussion is Friday, January 20th**.


### COVID Reminder

**If at any time you are feeling ill or need to isolate yourself due to close contact with someone who tests positive for COVID, please do NOT come to live lecture or discussion**. You can watch the lecture recordings and discussion walkthrough videos instead, and let us know promptly if you would like further support.


## Homework

To enhance and gauge your fluency with the course content, we will have two types of homework assignments: problem sets and labs ([Jupyter notebook](https://jupyter.org/)-based coding assignments). You can expect **approximately one problem set per week**, and **5 labs** throughout the semester.


### Drops

**We will automatically drop the two lowest problem scores and one lowest lab score from your final grade**.


### Timeline

As we cannot avoid releasing problem sets and labs in concurrent weeks, we will give you two weeks for each lab: **they will be released on Fridays and due two weeks later on Friday at 11:59pm.**


### Problem Set Logistics

**Release**: Problem sets will typically be released on **Fridays** via bCourses. We will also announce on Ed when problem sets are released.

**Submission**: Problem sets will be due the following **Friday at 11:59pm** (you have **one week** to complete the assignment). 

You will submit your work through **Gradescope**. You have several options for scanning and submitting your work:



1. Print out the homework document and write your solutions on the printout. Then upload a PDF file of the scan.
2. Write your solutions on this PDF file using a tablet device. Then upload a PDF file.
3. Use your own sheets of paper, but demarcate clearly the space for each problem, part, and subpart. You must not exceed the amount of space allotted in this official problem set document. Then upload a PDF file.


### Lab Logistics

Labs are similar to problem sets, except they use Jupyter notebooks, which are a web-based tool for interactively running python code. Labs are an opportunity to see real-world applications of EE 120 material.

**Release**: Labs will be released on **Fridays via Ed**. They will be released on **Datahub**, an online platform for running Jupyter notebooks; we will provide a Datahub link for each lab.

We will also provide .zip files of lab materials via bCourses if you want to work locally. Please note that we will have limited support for technical issues that arise while running labs locally.

**Submission**:



1. Run all cells before the grader.export() cell
2. Save the notebook (ctrl-s or cmd-s should work)
3. Run the grader.export() cell
4. Download the zip file produced by grader.export()
5. Upload the zip file to the Gradescope.

As we cannot avoid releasing problem sets and labs in concurrent weeks, labs will be due **two weeks after they are released, on Friday at 11:59pm**.

**Notes on Autograding**:



* You will be able to see whether you passed the public tests, but not your full score, directly after the autograder finishes running.
* **If tests pass locally but not on Gradescope:**
    * _Double-check that you saved the notebook._
    * _Make sure you did not add any print statements that we did not ask you to add. This interferes with the autograder._
    * Due to a bug, you might see "Failed Tests: Public Tests" in red on the right-hand side of the screen. **Disregard this; you're fine as long as you see "All test cases passed!" for each public test** on the autograder output.
* There may be private tests. You will not see your grade for the private tests until after scores are released. _We will, however, do our best to make public tests comprehensive._
* We'll release full autograder scores during the week after the lab is due.


### Grace Period

Although problem sets and labs are due on Fridays, **you can submit, with no penalty, the assignments until the immediately subsequent Sunday at 11:59pm**; in other words, you have a weekend’s worth of grace period for each assignment. This comes with two important caveats:



1. Staff support will be limited during the grace period.
2. Barring exceptional circumstances and DSP accommodations, we will not be accepting any late assignments (_i.e._, they will automatically earn a 0).


### Collaboration

You may collaborate with up to 5 other students on homework, but each person must submit their own work. For problem sets, please write down the names of your collaborators on the appropriate location on the first page of the assignment. You need not indicate your collaborators for labs.


## Self Grades

Problem sets will be self-graded, and labs will have both autograded and self-graded components. **_Warning: not submitting a self-grade will result in a 0 on the corresponding assignment._**

The purpose of the self-grade assignments strategy is to encourage you to look over the solutions and use it to check your answers.  We hope it offers a chance to self-assess your understanding of the class content to better prepare for exams. We warn students against inflating your self-grade scores, as we will be doing random checks every week to verify.


### Timeline

Self grades will be released, along with assignment solutions, when the grace period for the assignment ends. **Self grades will be due exactly a week after the corresponding assignment: Friday at 11:59pm, with a grace period until Sunday at 11:59pm**.


### Instructions



1. When we release solutions for each assignment, we will post a link to a form in which you can input your self grades. You can find this link on the “Solutions Released” Ed post.
    1. This form produces a JSON file, which you will then upload to gradescope.
    2. For transparency, we will release the number of points associated with each problem. This should not influence your self grades.
2. Using the rubric below, give each problem a score from 0 to 5 and input your scores into the form.
3. Download the file generated by pressing the button at the bottom of the form, and upload that file to the self-grade assignment on Gradescope.
    3. Ensure that the autograder runs properly. Contact course staff through a private post on Ed if you are having issues.
4. In the week after self grades are due, we will checka random sample of self grades.
    4. We’ll check every student’s self grades at least once this semester.
    5. If there is a **large discrepancy** found between your self grade and the course staff-determined score, you run the risk of having that homework scored as a 0, and having your other self grades reviewed as well.


### Rubric

* 5: At least 80% of the problem is correct, with full effort and work shown. Complete work must be shown for full credit!
    * For example:
        * You completed 80+% of the sub-parts (if applicable), and each was fully correct, or had minor arithmetic errors that did not impact the form of the final solution.
        * You attempted all of the sub-parts, and your work was almost fully correct with minor errors.

* 4: At least 60% … 
    * Your work was in the right direction, but missing one or a few critical steps.

* 3: At least 40% … 
    * You made about half (or a little less) of the progress required for a correct solution.

* 2: At least 20% … 
    * You made initial progress but proceeded in the wrong direction.

* 1: At least 5% …
    * Minimal progress; almost fully incorrect.

* 0: Blank or did not attempt.


## Exam

We will have 2 quizzes and 2 midterms this semester. **There is no final exam**. 

**Each exam will be online and take place during lecture time.** For midterms, the question document will be released at **3:10pm** **on bCourses**, and the exam will be due **5:00pm on Gradescope**. For quizzes, the exam will take place during the last half of lecture: the question document will be released at **4:10pm on bCourses**, and the exam will be due **5:00pm on Gradescope**.

Exams are open-book, and we allow collaboration, l**imited to designated threads on Ed**. All external collaboration, including being in the same room as other EE 120 students while taking the exam, is prohibited.

Because all quizzes and exams take place during class, **we will not be accommodating exam time conflicts**. Email [ee120-sp23-admin@lists.berkeley.edu](mailto:ee120-sp23-admin@lists.berkeley.edu) if you have any concerns.

**Quiz Dates:** Monday, February 6th and Wednesday, March 22nd

**Midterm Dates:** Wednesday, March 1st and Wednesday, April 26th

We will release more exam logistics in Ed posts before each exam.


### Clobber

Your Quiz 2 z-score will automatically clobber your Quiz 1 z-score if it improves your overall grade. Your Midterm 2 z-score will also automatically clobber your Midterm 1 z-score if it improves your overall grade.


## Grading



* **Quizzes**: 15% each (30% total)
* **Midterms**: 25% each (50% total)
* **Labs**: 10% (We drop the lowest lab score)
* **Problem Sets**: 10% (We drop the lowest 2 scores)


## Optional Course Materials

There is no official textbook or set of course notes for EE120. However, if you would like additional information beyond what is covered in lectures, homeworks, and labs, you can look at these two textbooks:



* [Signals and Systems by Hwei P Hsu](https://electronicsbookcafe.files.wordpress.com/2015/08/signals-and-systems-2nd-edition-schaums-outline-series-hwei-hsu.pdf)
* [Signals and Systems by Oppenheim and Willsky](https://eee.guc.edu.eg/Courses/Communications/COMM401%20Signal%20&%20System%20Theory/Alan%20V.%20Oppenheim,%20Alan%20S.%20Willsky,%20with%20S.%20Hamid-Signals%20and%20Systems-Prentice%20Hall%20(1996).pdf)

As a disclaimer, EE 120 does not directly follow these textbooks, so they will differ from the course material in terms of content emphasis and scope.
