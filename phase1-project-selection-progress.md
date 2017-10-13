Subject: Phase 1 - Cheah: An implementation and evaluation of Loopix, an anonymity system

Phase 1 Project Selection Status Report

Name: Jun Siang Cheah

College: Christ's

User Identifier: jsc81

Director of Studies: Richard Mortier

1. Please write 100 words on your current project ideas.

Loopix is a new anonymity system, which solves some of the issues that affect
existing onion routing/mix networks such as Tor. A useful feature of Loopix for
mobile P2P applications is storage of messages for offline clients, where mobile
clients can find it hard to stay online for P2P communication to take place.
However, the reference implementation of Loopix is written in Python, which
isn't easy to run on iOS or Android. I propose to create a Java library
implementation of Loopix for use with desktop/Android applications, and evaluate
the performance and privacy metrics of my implementation.

2. Please list names of potential project supervisors.

Alastair Beresford

3. Is there any chance that your project will involve any
computing resources other than the Computing Service's MCS and
software that is already installed there, for example: your own
machine, machines in College, special peripherals, imported
software packages, special hardware, network access, substantial
extra disc space on the MCS.

If so indicate below what, and what it is needed for.

* Possible need for a cluster of machines to test system at scale. (Original
  paper used about 500 VMs)
  - Fallback: Use a small number of machines and extrapolate results.