---
layout: single
title:  "Interning at Vision Cortex and SeaQL"
date:   2023-01-21 20:54:33 +0000
categories: internship
---
Before graduating and moving on to a full-time software engineer role, I spent several semesters working on a number of open-source projects with the talented minds behind [Vision Cortex](https://www.visioncortex.org/) and [SeaQL](https://www.sea-ql.org/) - and I highly recommend any students to take part in their industrial internship programs.

## Getting my hands dirty

The most impactful benefit of interning in the team has to be the exposure to up-to-date real-world toolings that are overlooked in university curriculums. University education, for the most part, puts the focus on learning principles and is not flexible enough to cover the **most modern solutions that modern developers actually adopt**.

A good industrial internship **fills the gap between the knowledge and the "actual" problems**. After taking a course or two in databases, a student may be able to write clever SQL statements or explain what `CREATE INDEX` does, but they might still have no clue how to set up and connect to a database because those have been configured by TA's before the coursework. The latter is an example of what you can expect to experience hands-on during internships.

![Mascot of Rust programming language, Ferris the crab.](/assets/images/2023-01-21/ferris.png){: .align-center .width-half}

As the team fully embraces Rust, I was granted the chance to learn and practice the rather new yet wonderful programming language. Listing the benefits of Rust would take a whole another post, but I'd stress that **just understanding Rust's design decisions enables an engineer to formulate more robust solutions in any languages** - by considering what Rust considers.

## Getting into Open Source

Another perk of working with the team was the experience of contributing (and using) open source code. **The community of open source development has always been one of the nicest forms of communities** I've ever seen anywhere: developers around the world working on the same product in their free time; there's (*usually*) no monetary compensation, only passion and satisfaction.

![Programmers working together.](/assets/images/2023-01-21/programmers-collaborate.jpg){: .align-center .width-half}
*Photo by Annie Spratt on Unsplash.*

Having worked on various open source graphics/vision projects in Vision Cortex and some data engineering ones in SeaQL, I'd gladly say that it even feels like a privilege to get paid for working on open source projects. **It was indeed quite satisfying to know that your code contributed (in)directly to someone else's research, and/or when more and more developers are seeing the vision you saw**.

## Recounting the Journey

![Vision Cortex Logo](/assets/images/2023-01-21/visioncortex-logo.svg){: .align-center .width-half}

### Vision Cortex

In 2020, I joined the team working on [VTracer](https://github.com/visioncortex/vtracer), and it was the very first experience I had with Rust. Having worked only with "mainstream" languages like Python and C++ at that time, I was quickly overwhelmed by the complex and strict requirements imposed by the language - for the better of course. **Fortunately the Rust compiler suite is very well equipped and provided me with 100% support and 0% judgement - and that's why I would recommend anyone interested in Rust to just try it out!**

Later on, I worked on several other graphics/vision projects such as [SymCode](https://github.com/visioncortex/SymCode). Through them, **I developed the ability to built solid software with numerous components interacting with each other**. It's a challenging task particularly in Rust, due to how the language always enforces certain rules to keep your program safe.

For example, a common pattern we see in system design is a data structure in which different entities reference each other, like in a doubly linked list. However, the implementation of such a pattern always requires special attention because of the issue of ambiguous ownerships (and hence lifetimes), and anyone who tried would know that Rust gives its absolute best to give you a hard time (*as it should!*) when you try to do this without "specialized" knowledge (f.i. [`std::rc::Rc`](https://doc.rust-lang.org/std/rc/struct.Rc.html)). One (*ahem, past me, ahem*) might argue that it would be trivial to implement in other languages, but no, it's probably just that the implementation is vulnerable and the programmer never even considered those points of vulnerability in the first place. **All Rust does is force you to rethink vulnerable designs or explicitly use specialized infrastructure after some research**.

![SeaQL Logo](/assets/images/2023-01-21/seaql-logo.png){: .align-center .width-half}

### SeaQL

Towards the end of my university career, I decided to explore and switched to the data engineering field. [StarfishQL](https://github.com/SeaQL/starfish-ql) was an experimental engine to query and visualize dependency-based data as graphs. It was really an opportunity for me to put all my skills to the test. In the later half of my final year as an undergrad, I chose to contribute to reworking the tutorials of [SeaORM](https://github.com/SeaQL/sea-orm), one of the main products of the SeaQL. It allowed me to take my time and familiarize with the usage of ORM's, and the transparent nature of open source projects gave me the freedom to explore the implementation of any parts I was interested in.

## Self-Discovery

![A hand doing planning work](/assets/images/2023-01-21/planning-work.jpg){: .align-center .width-half}
*Photo by Alvaro Reyes on Unsplash*

These experiences were great opportunities for me to explore what I truly enjoy in software development. In general, I've discovered that I find the process of sophisticated system design really fascinating - the way we have to **carefully take all relevant factors into acount and correctly model how different components in the system would interact with each other**. More specifically, it's always been nothing but rewarding to see **how my imaginations are realized through implementations**; sometimes it could be the abstract system design, or in graphics, how I imagine the pixels would look like. Before I knew it, I'd already fallen in love with software engineering, and programming in general!

## All in all

Huge shoutout to [Chris](https://github.com/tyt2y3) and [Billy](https://github.com/billy1624), who have been providing the best mentoring and company along the journey. I can confidently claim that interning at the team was a career-changing experience that has given me a huge boost towards where I want to be. **Prospective software engineers must never underestimate the value of setting foot in the field through industrial internships, and it always does more good than harm to submerge yourself in the ocean of open source**. Even if you lack the time/effort to invest into a full/part-time commitment, definitely try contributing to open source anyway!
