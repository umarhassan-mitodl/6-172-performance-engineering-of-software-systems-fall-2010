---
content_type: page
course_id: 6-172-performance-engineering-of-software-systems-fall-2010
layout: course_section
menu:
  6-172-performance-engineering-of-software-systems-fall-2010:
    identifier: 9d7797c17761332e81c92ef25cd5b330
    name: Project Descriptions
    parent: 594533c8245719bac07003c4a6cf05e8
    weight: 50
title: Project Descriptions
uid: 9d7797c1-7761-332e-81c9-2ef25cd5b330
---

The bulk of your out-of-class time will be spent completing six projects of increasing scope and complexity. The general structure of each assignment is described below.

**Project 0** will be completed individually. It will give you an opportunity to familiarize yourself with the development environment, which will save you time on future projects. You will not turn in this assignment, but it's strongly recommended that you do it.

**Project 1** will be completed in pairs. It will allow you to explore how "bit hacks" can improve performance. You will modify two small programs with the goal of increasing their performance. You will investigate data representations and efficient bitwise operations on data words.

**Project 2** will be completed individually. You will learn how to profile an application to determine where it is spending most of its time and why. You will take advantage of hardware performance counters and several tools including VTune (a powerful profiler) and Pin (a dynamic instrumentation tool) to collect and analyze performance data.

**Project 3** will be completed in pairs. This project will require you to examine the complex real-world problem of high-performance memory management. You will implement a library which provides the malloc, free, and realloc functions (that is, the C memory-management API) as efficiently as possible for a number of different plausible workloads.

**Project 4** will be completed in pairs. You will begin by analyzing optimizing a single-threaded physical simulation. Then, you will be introduced to Cilk++, a language, compiler, library, and tool chain for developing multithreaded applications, and will parallelize your project. This project will expose you to many of the issues associated with correctness and performance in a multithreaded application.

**Project 5** will be completed individually. This project will be a take-home written assignment that will evaluate your knowledge of the theoretical material that the course will have covered. You will have a chance to demonstrate your knowledge of some of the analytical techniques and fundamental material that you will have learned.

**Project 6** will be completed in small groups of two or three students. You will work to optimize a ray-tracer, which renders scenes that include reflection, refraction, and interaction with solid objects and with water, as well as three distinct types of illumination (direct, caustic, and global). Unlike in previous projects, we will provide relatively little direction; you will have to use everything you have learned during the course to identify performance issues and eliminate them. The fastest submission will win!