# MIDS Computing Basics Bridge Class

In the MIDS program we teach concepts and tools around data science and machine learning. While we offer our students introductory classes for Python and Statistics, we cannot deliver basic computation skills that are usually taught in a full Bachelor program CS. To cover this gap this bridge course gives resources to learn the most important concepts and tools required to successfully complete the MIDS program.

## Goals and Objectives
This course has the objective to give resources for self learning and test the students’ skill level in the end. Students who already know the content can skip ahead to the tests. 
Objectives of this course:
* Acquire basic knowledge/terminology about:
* Operating systems
* Computer Networks
* LINUX
* Learn basics of important tools:
  * Linux command line
  * Git and GitHub
  * Shell scripting

## How to use this course:
This course guides you through a series of FREE online classes. For example in EDX you can select the Audit only option, 
the paid certificate is NOT necessary. 
The courses are in a order we think will be most efficient for learners but the are self contained and can be taken in any order.
Each topic ends with a series of multiple choice questions, a short quiz. These quizzes are not graded and the answers directly follow each questions. They 
function as self assessment to give you an idea where you stand in the topic, i.e., if you should definitely take the course or can skip the segment.
At the end you will have to take an exam (find the link at the end of this doc). You will have to solve the given problem and write two reviews for the solution 
others have submitted to show your thorrough understanding of the material.

Alternatively you can prove your knowledge through having finished a CS undergrad or corresponding work experience - please speak to the faculty in that case.

## Courses in this class

The big topics are 
* Operating systems: have an understanding
* Networking: the network stack and an overview on protocols
* LINUX: have a working knowledge of the LINUX operating system
* Shell scripting (optional): this is an extension and a deep dive of topics covered in the LINUX class. You will need HEREDOCS in later classes though.
* Git and GitHub: You need to be able to use git from the web UI and the commandline, know branching, reversing, have good workflow habits.

### Operating systems
Understanding how a computer works and the role of the Operating System is the basis for any work with cloud technology and distributed computing as is the standard for many big data and machine learning approaches.

The following course is offered through EDX and was created by NYU:
https://courses.edx.org/courses/course-v1:NYUx+FCS.OS.1+1T2020/course/

This course is relatively short with 5 lectures rangning from 50 minutes to 1 hour 40 minutes.

<details>
  <summary>Quiz - click to see</summary>

  1. What is an operating system?<br>
    (a) a collection of programs that manages hardware resources<br>
    (b) a system service provider to the application programs<br>
    (c) a link to interface the hardware and application programs<br>
    (d) all of the above

  <details>
    <summary>Answer</summary>
    d - all of the above
  </details>

  2. What is interprocess communication?<br>
    (a) communication within the process<br>
    (b) communication between two processes<br>
    (c) communication between two threads of the same process<br>
    (d) none of the mentioned
  
  <details>
    <summary>Answer</summary>
    b - communication between two processes
  </details>  
</details>  


### Networking 

Understanding how computers communicate with each other is a basic concept necessary to work with cloud tech, multi container setups, 
and more. Networking comes in two parts. The following EDX course, again from NYU, covers an overview of the network stack. 
We will later revisit networking for a special topic, SSH proxies, that is needed to attend W261 Machine Learning at Scale.

https://courses.edx.org/courses/course-v1:NYUx+FCS.NET.1+1T2020/course/

Please make sure to at least audit lectures 1 to 4 (Network Layer)

### LINUX
Most server infrastructure in use today is based in LINUX systems. MacOS too has a LINUX system at its core. Understanding the principles of this specific brand of operating systems and finding your way around in it is fundamental to this program. Many tools today abstract away the complexity of the underlying system but in order to debug a problem or create a new way of using modern tools will bring you back to digging deeper into LINUX.
The following EDX course is made and maintained by the LinuxFoundation.
https://courses.edx.org/courses/course-v1:LinuxFoundationX+LFS101x+1T2020/course/

Please go through at minimum chapters 3, 7 - 16, and 18. In chapter 14 you can skip directly to Networking configuration tools if you have finished the networking class before. You may also skip 9 if you are familar with ps and top and have finished the OS lecture above.

To get extra practice the linux survival tutorial allows you to test your skill in an interactive, gamified way. This is optional: https://linuxsurvival.com/linux-tutorial-introduction/

### Shell scripting
Shell scripting is part of each LINUX class and you probably have received your first practice going through the LINUX course. Being able to use Shell scripting in an efficient way has more to it than can be covered in a general LINUX class. A great and interactive way to learn it is 
on https://www.learnshell.org/

A concept usually not covered by basic scripting classes is HEREDOCS, you will need this in the advanced classes in the MIDS program: https://linuxhint.com/bash-heredoc-tutorial/

### Git and GitHub
"Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows." - Wikipedia
Git is an essential tool used across most modern tech companies. In the MIDS program you will need to be able to use git together with GitHub (a platform hosting Git repositories). You will be required to work with git from the commandline, local and remote locations such as VMs in the cloud. 

- To get started on basic git: https://www.codecademy.com/learn/learn-git
- Using github: https://guides.github.com/activities/hello-world/
- optional: deeper dive into git and github https://try.github.io/

### Additional Readings:

* Kurose, Ross: Computer Networking - A Top Down Approach:
http://www.bau.edu.jo/UserPortal/UserProfile/PostsAttach/10617_1870_1.pdf
* Linux For Beginners by Jason Cannon
* The Linux Command Line : A Complete Introduction by William Shotts
* Modern Operating Systems by Andrew S. Tanenbaum


