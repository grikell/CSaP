# **Computer Systems and Programming (2024 - 2025)**

#### **Teacher: Giorgio Richelli - [giorgio.richelli@uniroma1.it**](mailto:giorgio.richelli@uniroma1.it)

## **NEWS**

Class Timetable

- Monday h.08:00/10:00- Aula Magna (V.le Regina Elena)

- Tuesday h.13:00/16:00 - Aula Alfa (Via Salaria)

Lectures will be delivered in presence (no streaming).

### **Office Hours**

**By previous appointment, before or after the lessons.**

**Students can always use email and/or schedule a webmeeting**

**CSAP Google Group**

A group has been created in order to allow communication, sharing of information, etc.

Interested students are invited to join it, in order to to get access to the folder where code, slides and recordings will be available.

### Objectives

The course is mainly focused on system programming for Unix/Linux systems.

The objective is to make students able to understand, write and modify, programs interfacing with the Linux operating system and its kernel source code. More precisely, we expect the students to acquire knowledge of:

1. the C language and the tools normally used in the development environment (compiler, preprocessor, debugger, make, shell, etc.)

2. the fundamental functions of the operating system and its main modules (Scheduler, Virtual Memory Manager, Filesystem..).

3. the main system primitives for the creation and synchronization of processes, exchange of messages and information (this is the core of the course)

4. primitives for network programming (sockets)

and be able to:

1. use the primitives provided by the operating system and integrate them correctly into the code.

2. choose the most suitable OS component and functions, based on the needs of the applications and their execution mode.

3. determine the complexity and how to implement a system application.

4. describe the interaction of an application with the operating system and explain the reasons behind the choices.

5. continue learning by examining, in detail, the architecture and programming interface of the operating system.

### Prerequisites

Formal pre-requisites for the course are the same as the prerequisites for enrollment to the Master in Cybersecurity (see https://cybersecurity.uniroma1.it/admission\#requirements):

Our MSc takes for granted the subjects and contents covered in the Italian Bachelor's Degree in Computer Science or Computer Engineering. Our MSc offers an in-depth technical study aimed at training experts in Cybersecurity. Therefore, an high technological core is essential, regardless of the orientation chosen within your Study Plan.

In practice, you will need (at least):

- mastery of one (preferably more) programming language(s)

- understanding of computer architecture and operating system principles

- understanding of computer network protocols (preferably TCP/IP).

Each student should have access to a Linux system (a VM is ok), including the compiler, development tools (make, debugger, etc) and man pages. Ubuntu 26.04 is the recommended platform.

Working natively on other devices, such as Mac or Windows laptop, while possible, is not recommended due to suble differences in the compiler suite and OS interface.

## **Exam**

**The exam consists in an oral discussion of a set of C sources, makefiles & documentation, a.k.a “*the project*”.**

The project consists of a C language program that satisfies a set of specified requirements, **using only the library calls that are part of the course program**. The use of other calls is generally not accepted. If in doubt, ask the teacher.

The project code must correctly compile and execute in the required software environment (compiler version, kernel version, clib version).

Each exam session may have a different project. All detailed specifications will be posted on the Google Group.

The project can be done in a team of max. two persons and it must constitute an original creation. Therefore it is not possible to share parts of the code, or copy contents from other sources. 

However, discussions between students, exchanges of ideas, use of mailing lists, chats, and in general everything that helps the student to learn are legitimate and appreciated (in case of doubts regarding which forms of collaboration are considered legitimate or not, it is better to explicitly ask for clarification).

**The code and the docs for the project must be sent by email a week before the session where it will be reviewed/discussed**.

The evaluation criteria of the project are:

- Prerequisite: the code must correcly compile, link and start on Ubuntu 26.04.

- Correctness of the code: main evaluation element that determines (alone!) the passing of the exam.

- Error handling: it is an integral part of the correctness of the code!

- Modularity and readability of the code: division into functions, comments, function and variable names (!), etc...

- Quality of documentation: user manual, software architecture, README file, project report.

However, the oral discussion is the mail component of the final evaluation.

### **Program**

**These are the topics that are planned to be covered during the course. Of course mileage may vary, depending on time available, etc.**

- **Recap of the C programming language: variables, costants, operators, expressions, control instructions, functions, pointers, arrays, structures & unions, preprocessor directives**

- **Programming environment: compiler, make & makefiles, gdb debugger**

- **Operating system basics (Linux): processes, filesystem, inter-process communication primitives (signals, pipes, semaphores, shared memory)**

- **Network programming: sockets, raw sockets, sniffers**

## **Recommended Readings**

- **Daniel P. Bovet, Marco Cesati: Understanding the Linux Kernel**

- **Brian Kernighan, Dennis Ritchie: The C Programming Language (2nd Ed.)**

- **Richard Stevens: Advanced Programming in the UNIX Environment**

- **BW Kernighan, R. Pike : The Practice of Programming**

- **M. Mitchell, J. Oldham, A. Samuel: Advanced Linux Programming**

