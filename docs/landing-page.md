---
id: landing-page
title: Welcome to RHT524
sidebar_position: 1
slug: /
description: Landing Page for RHT524
---

# Welcome to RHT524

## Open Source Certification I

## Quick Links

| [Weekly Schedule](./weekly-schedule.md) | [Course Outline](https://apps.senecacollege.ca/ssos/print/cpo500/20221/) | [Assignment 1](/B-Assignments/assignment1.md) | [Assignment 2](/B-Assignments/assignment2.md) |
| --- | --- | --- | --- |

## What This Course is About

Students will learn the core utilities to work productively in a Linux environment. Students will do this work using the shell, at the same time learn to configure their login accounts, manipulate data stored in files, effectively use Linux commands and utilities to configure, adjust, maintain, and troubleshoot the operation of computer systems. This is a lot of responsibility, and with that responsibility comes power. You will be able to change anything on the system, and you will also have the ability to damage or destroy the system.

This course is the first of two courses intended to prepare the student to write the EX200 certification.

In this course you will be given remote access to a virtual machine hosting Redhat Enterprise Linux

## Learning by Doing

Most of the learning in this course occurs through the hands-on problem solving that takes place in doing labs and two assignments. Therefore, it's very important to stay up-to-date with the coursework, and to practice until you have confidently mastered each task.

## Weekly Schedule

Weekly topic, lab, and assignment information is available on the [RHT524 Weekly Schedule](./weekly-schedule.md) page.

## Supplies Checklist

Needed by the second class:

1. You will need a RedHat account. Note that this must be created using your Seneca email or you will not be able to access the course material. Instructions can be found on blackboard.
2. Once you have created the account and provided it to your professor you will receive an invitation email to gain access to the material hosted on the RedHat Academy platform.

## Faculty

During the Winter 2023 semester, RHT524 is taught by:

- [Peter Callaghan](https://ict.senecacollege.ca/~peter.callaghan)

## Course Information

### Important Websites

- [School of Information and Communications Technology](https://ict.senecacollege.ca/students/home) (includes class cancellation information and general bulletins)

### Evaluation:

| Evaluation | Marks|
| --- | --- |
| Labs (Minimum 5) | 5% |
| Quizzes (Minimum 5) | 10% |
| Tests (Minimum 1) | 20% |
| Assignments (Minimum 2) | 40% |
| Final Assessment | 25% |

## Tips and Suggestions

- Always shut down your system under software control, rather than using the reset or power buttons. You can shutdown using the GUI or with the `poweroff`, `reboot`, `init`, or `shutdown` commands.

**Always shut down your virtual machines before shutting down your main system.** If you do not shut down the virtual machines first, they may become unstable or unusable.

- If you get a message about the gnome-power-manager configuration at the login screen, you may have run out of disk space. Switch to a character-mode virtual terminal (for example, switch to VT2 by pressing Ctrl-Alt-F2). Login and take a look at the available space (with the command: `df -h`). If the `/` filesystem is full, delete some files (such as unused VM images in `/var/lib/libvirt/images`) and then reboot the system.
