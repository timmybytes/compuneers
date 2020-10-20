---
layout: post
title: "Margaret Hamilton (1936 - )"
author: "Timothy Merritt"
categories: figures
tags: [figures]
image: /HAM001/896px-Margaret_Hamilton.jpg
figure-id: HAM001
---


## Work

*Content from [Wikipedia](https://en.wikipedia.org/wiki/Margaret_Hamilton_(software_engineer))*

From 1961 to 1963, Hamilton worked on the Semi-Automatic Ground Environment (SAGE) Project at the MIT Lincoln Lab, where she was one of the programmers who wrote software for the prototype AN/FSQ-7 computer (the XD-1), used by the U.S. Air Force to search for possibly unfriendly aircraft. She also wrote software for a satellite tracking project at the Air Force Cambridge Research Laboratories. The SAGE Project was an extension of Project Whirlwind, started by MIT to create a computer system that could predict weather systems and track their movements using simulators. SAGE was soon developed for military use in anti-aircraft air defense from potential Soviet attacks during the Cold War.

It was her efforts on this project that made her a candidate for the position at NASA as the lead developer for Apollo flight software.

### Draper Laboratory

Hamilton then joined the Charles Stark Draper Laboratory at MIT, which worked on the Apollo space mission. Hamilton was initially hired as a programmer for this process but moved on into system designs. Eventually, she was in charge of all Command Module software, which was all the software for navigation and lunar landing guidance. She eventually led a team credited with developing the software for Apollo and Skylab. Hamilton's team was responsible for developing in-flight software, which included algorithms designed by various senior scientists for the Apollo command module, lunar lander and the subsequent Skylab. Another part of her team designed and developed the systems software. This included error detection and recovery software such as restarts and the Display Interface Routines (also known as the Priority Displays), which Hamilton designed and developed. She worked to gain hands-on experience during a time when computer science courses were uncommon and software engineering courses did not exist. Hamilton also served as Director of the Software Engineering Division.

Her areas of expertise include: systems design and software development, enterprise and process modeling, development paradigm, formal systems modeling languages, system-oriented objects for systems modeling and development, automated life-cycle environments, methods for maximizing software reliability and reuse, domain analysis, correctness by built-in language properties, open-architecture techniques for robust systems, full life-cycle automation, quality assurance, seamless integration, error detection and recovery techniques, man-machine interface systems, operating systems, end-to-end testing techniques, and life-cycle management techniques. These made her code incredibly reliable because they helped programmers identify and fix anomalies before they became major problems.

### Apollo program

In one of the critical moments of the Apollo 11 mission, the Apollo Guidance Computer together with the on-board flight software averted an abort of the landing on the Moon. Three minutes before the lunar lander reached the Moon's surface, several computer alarms were triggered. The on-board flight software captured these alarms with the "never supposed to happen displays" interrupting the astronauts with priority alarm displays. Hamilton had prepared for just this situation years before:

> There was one other failsafe that Hamilton likes to remember. Her "priority display" innovation had created a knock-on risk that astronaut and computer would slip out of synch just when it mattered most. As the alarms went off and priority displays replaced normal ones, the actual switchover to new programmes behind the screens was happening "a step slower" than it would today.
> Hamilton had thought long and hard about this. It meant that if Aldrin, say, hit a button on the priority display too quickly, he might still get a "normal" response. Her solution: when you see a priority display, first count to five.
>
> [source](https://members.tortoisemedia.com/2019/07/13/nasa-margaret/content.html)

The astronauts had inadvertently left the rendezvous radar switch on, causing these alarms to be triggered. The computer was overloaded with interrupts caused by incorrectly phased power supplied to the lander's rendezvous radar. The program alarms indicated "executive overflows", meaning the guidance computer could not complete all of its tasks in real time and had to postpone some of them. The asynchronous executive designed by J. Halcombe Laning was used by Hamilton's team to develop asynchronous flight software:

> Because of the flight software's system-software's error detection and recovery techniques that included its system-wide "kill and recompute" from a "safe place" restart approach to its snapshot and rollback techniques, the Display Interface Routines (AKA the priority displays) together with its man-in-the-loop capabilities were able to be created in order to have the capability to interrupt the astronauts' normal mission displays with priority displays of critical alarms in case of an emergency. This depended on our assigning a unique priority to every process in the software in order to ensure that all of its events would take place in the correct order and at the right time relative to everything else that was going on.
>
> [source](https://en.wikipedia.org/wiki/Margaret_Hamilton_(software_engineer)#cite_note-auto-41)

Hamilton's priority alarm displays interrupted the astronauts' normal displays to warn them that there was an emergency "giving the astronauts a go/no go decision (to land or not to land)". Jack Garman, a NASA computer engineer in mission control, recognized the meaning of the errors that were presented to the astronauts by the priority displays and shouted, "Go, go!" and they continued. Paul Curto, senior technologist who nominated Hamilton for a NASA Space Act Award, called Hamilton's work "the foundation for ultra-reliable software design".

![Margaret Hamilton](/assets/img/HAM001/578px-Margaret_Hamilton.jpg)
<figcaption>Hamilton with the Apollo guidance software she and her team developed at MIT.  |  <strong><a href="https://news.mit.edu/2016/scene-at-mit-margaret-hamilton-apollo-code-0817">MIT Museum</a></strong></figcaption>

Hamilton later wrote of the incident:

> The computer (or rather the software in it) was smart enough to recognize that it was being asked to perform more tasks than it should be performing. It then sent out an alarm, which meant to the astronaut, 'I'm overloaded with more tasks than I should be doing at this time and I'm going to keep only the more important tasks'; i.e., the ones needed for landing ... Actually, the computer was programmed to do more than recognize error conditions. A complete set of recovery programs was incorporated into the software. The software's action, in this case, was to eliminate lower priority tasks and re-establish the more important ones ... If the computer hadn't recognized this problem and taken recovery action, I doubt if Apollo 11 would have been the successful moon landing it was.
>
> — Letter from Margaret H. Hamilton, Director of Apollo Flight Computer Programming MIT Draper Laboratory, Cambridge, Massachusetts, titled "Computer Got Loaded", published in Datamation, March 1, 1971
>
> [source](https://en.wikipedia.org/wiki/Margaret_Hamilton_(software_engineer)#cite_note-auto-44)

### Businesses

In 1976, Hamilton co-founded with Saydean Zeldin a company called Higher Order Software [HOS] to further develop ideas about error prevention and fault tolerance emerging from their experience at MIT working on the Apollo program. They created a product called USE.IT, based on the HOS methodology they developed at MIT. It was successfully used in numerous government programs including a project to formalize and implement C-IDEF, an automated version of IDEF, a modeling language developed by the U.S. Air Force in the Integrated Computer-Aided Manufacturing (ICAM) project. In 1980, British-Israeli computer scientist David Harel published a proposal for a structured programming language derived from HOS from the viewpoint of and/or subgoals. Others have used HOS to formalize the semantics of linguistic quantifiers, and to formalize the design of reliable real-time embedded systems.

Hamilton was the CEO of HOS through 1984 and left the company in 1985. In March 1986, she founded Hamilton Technologies, Inc. in Cambridge, Massachusetts. The company was developed around the Universal Systems Language (USL) and its associated automated environment, the 001 Tool Suite, based on her paradigm of Development Before The Fact for systems design and software development.

## Biography

Margaret Elaine Heafield was born August 17, 1936, in Paoli, Indiana, to Kenneth Heafield and Ruth Esther Heafield (née Partington); she has two younger siblings: David and Kathryn. The family later moved to Michigan, where Margaret graduated from Hancock High School in 1954. She studied mathematics at the University of Michigan in 1955 before transferring to Earlham College where her mother was a student; she earned a BA in mathematics with a minor in philosophy in 1958. She cites Florence Long, the head of the math department at Earlham, as helping with her desire to pursue abstract mathematics and become a mathematics professor. She had other inspirations including her father (a philosopher and poet), and her grandfather (a school headmaster and Quaker minister). She says these men inspired her to include a minor in philosophy in her studies.

While at Earlham, Hamilton met her first husband, James Cox Hamilton, a senior majoring in chemistry. They were married on June 15, 1958, the summer after she graduated from Earlham. She briefly taught high school mathematics and French at a public school in Boston, Indiana, while her husband completed his undergraduate degree at Earlham. The couple then moved to Boston, Massachusetts, where James would later earn his master's degree in chemistry from Brandeis University; they had a daughter, Lauren, born on November 10, 1959. James later graduated from Harvard Law School in 1963; he founded a law firm in Boston and also later served on the board of the American Civil Liberties Union. The couple divorced in 1967 and Margaret married Dan Lickly two years later.

## Awards

* In 1986, Hamilton received the Augusta Ada Lovelace Award by the Association for Women in Computing.
* In 2003, she was given the NASA Exceptional Space Act Award for scientific and technical contributions. The award included $37,200, the largest amount awarded to any individual in NASA's history.
* In 2009, she received the Outstanding Alumni Award by Earlham College.
* In 2016, she received the Presidential Medal of Freedom from Barack Obama, the highest civilian honor in the United States.
* On April 28, 2017, she received the Computer History Museum Fellow Award, which honors exceptional men and women whose computing ideas have changed the world.
* In 2017, a "Women of NASA" LEGO set went on sale featuring minifigures of Hamilton, Mae Jemison, Sally Ride, and Nancy Grace Roman.
* In 2018, she was awarded an honorary doctorate degree by the Polytechnic University of Catalonia.
* In 2019, she was awarded The Washington Award.
* In 2019, she was awarded an honorary doctorate degree by Bard College.
* In 2019, she was awarded the Intrepid Lifetime Achievement Award.

## Trivia

Anthony Oettinger, Barry Boehm, and Margaret Hamilton have been credited with naming the discipline of "software engineering". Hamilton details how she came to make up the term:

> When I first came up with the term, no one had heard of it before, at least in our world. It was an ongoing joke for a long time. They liked to kid me about my radical ideas. It was a memorable day when one of the most respected hardware gurus explained to everyone in a meeting that he agreed with me that the process of building software should also be considered an engineering discipline, just like with hardware. Not because of his acceptance of the new 'term' per se, but because we had earned his and the acceptance of the others in the room as being in an engineering field in its own right.
>
> [source](https://en.wikipedia.org/wiki/Margaret_Hamilton_(software_engineer)#Legacy)
