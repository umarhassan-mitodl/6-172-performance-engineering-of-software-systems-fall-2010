---
content_type: page
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
hide_download: true
hide_download_original: null
layout: course_section
menu:
  6-172-performance-engineering-of-software-systems-fall-2010:
    identifier: fb179760b9fbb65851c339cc6bce439e
    name: Syllabus
    weight: 10
title: Syllabus
uid: fb179760-b9fb-b658-51c3-39cc6bce439e
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

Course Information
------------------

### Lectures

All material covered in the lectures will be fair game for projects and quizzes. We will post lecture slides on the course website, but they often will not contain all of the information presented in a particular lecture, and should not be considered a substitute for attendance.

### Recitations

We will not have regularly scheduled recitations. The teaching assistants will periodically hold primers—sometimes during regularly scheduled lecture hours, and sometimes at other times—to cover practical material that can help you complete the projects.

### Projects

The bulk of your out-of-class time will be spent completing six projects of increasing scope and complexity. Please see the [Projects]({{% getpage "courses/6-172-performance-engineering-of-software-systems-fall-2010/sections/projects/_index.md" %}}) section.

### Exams

There will be two one-and-a-half hour quizzes, which are not available on MIT OpenCourseWare. The quizzes will be closed-book and closed-notes, but you will be permitted crib sheets. Roughly speaking, they will cover the first and second halves of the course material. All material covered by the lectures, projects, or prerequisite courses, as well as any other material indicated by course staff, is fair game for the quizzes.

There will be no final exam.

Late and Missing Work
---------------------

Since this is a fast-moving class, you will most likely find it difficult to play "catch-up" if you should fall behind. For this reason, among others, we will generally not accept late projects. You should submit whatever you have by the deadline, and we will award partial credit as appropriate.

Grading
-------

Each assignment will describe how the materials you submit will be evaluated. The scores you receive on each assignment will be combined to produce your final grade after being weighted approximately as follows:

| ASSIGNMENTS | PERCENTAGES |
| --- | --- |
| Project 1 | 4% |
| Project 2 | 10% |
| Project 3 | 10% |
| Project 4 | 12% |
| Project 5 | 4% |
| Project 6 | 25% |
| Quiz 1 | 15% |
| Quiz 2 | 15% |
| Participation | 5% 

In addition, if you receive no substantial credit for the final project or for any two other assignments, you will receive a failing grade.

Software Engineering
--------------------

Research on programmer productivity has demonstrated that pair programming, where two programmers sit together during coding, produces better quality code faster than two programmers coding on their own. For group projects, we encourage you to do pair programming.

Likewise, regression testing demonstrably promotes fast code development. Studies have shown that over 90% of bugs are repeat occurrences of previous bugs. The idea of regression testing is to build a battery of tests that include test cases for every bug that has ever been found in the software. Whenever you find a bug in your code, before fixing the bug, you write a test that detects the presence of the bug and add it to the regression suite. Then, you fix the bug. Finally, you run the regression tests to ensure that the new code passes the test. With a good regression suite, it's easy to make changes to software, because if you mess something up, you don't go far down the road before discovering the fact.

It can also be helpful to write unit tests, which test a particular function, method, or class. That way, instead of trying to find a bug in a large codebase when it's all harnessed together, you can divide-and-conquer to do your detective work in smaller components, which is much faster and easier.

You should also make liberal use of the assert package to check assumptions, including loop and recursion invariants. Liberal use of printf can help you see the internal state of your computation. If you use #ifdef's to conditionally execute printf's based on a debug flag, you will not adversely impact production running time when the debug flag is set to FALSE. Some programmers also find it productive to use debugging tools, such as gdb, which allows setting of breakpoints, inspection and modification of internal state, and single stepping.

MITPOSSE
--------

The course staff has recruited senior software engineers in the region to share with you their invaluable experience and give you concrete advice on your design and code. These Masters in the Practice of Software Systems Engineering (MITPOSSE) will review your designs and code. Although they will not provide any input into your grade, their expertise can help you produce projects with a higher grade.

Your assigned Master has agreed to volunteer a significant time to help you learn. We've hand-picked these volunteers from among the very best software engineers in the region. They know what they are talking about. All have extensive experience with real-world, on-the-job design reviews.

Please accord these Masters your greatest respect, since they are volunteering their time. Be punctual. Be prepared. Be gracious. You can learn a lot from them.