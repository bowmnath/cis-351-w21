## Welcome to CIS 351!

This is the main website for the course.
The slides, schedule, and links to assignments, labs, projects, and videos,
as well as the official course policies,
will be posted here.
The course also uses other websites for specific purposes.
* [Piazza](http://www.piazza.com/gvsu/winter2021/cis351section2/home) is a question-and-answer forum.
*All official announcements will be sent through Piazza*,
and you are responsible for monitoring Piazza to keep up to date with
announcements
(Piazza by default will send an email when an announcement is posted).
    * Signup link:
      [www.piazza.com/gvsu/winter2021/cis351section2](http://www.piazza.com/gvsu/winter2021/cis351section2).
    * You can read the following [Piazza FAQ](misc/piazza-faq.md) if you have
      questions.
* [Zoom](https://zoom.us) will be the video conferencing service for office
  hours and synchronous course meetings.
    * Course meetings and labs:
      [https://gvsu-edu.zoom.us/j/91852767552?pwd=Z0NqMEhzdUxuTkszcTVORmJyTjhlQT09](https://gvsu-edu.zoom.us/j/91852767552?pwd=Z0NqMEhzdUxuTkszcTVORmJyTjhlQT09)
    * Office hours:
      [https://gvsu-edu.zoom.us/j/98637553783?pwd=RzJsazNrcDhFemFRTCtvN2xiblFnUT09](https://gvsu-edu.zoom.us/j/98637553783?pwd=RzJsazNrcDhFemFRTCtvN2xiblFnUT09)
* [Prairielearn](https://www.prairielearn.org/pl/course_instance/128492) is where you will
submit all of your assignments, labs, and projects.
* [ClassTranscribe](https://classtranscribe.illinois.edu/) is where the videos
will be hosted.

That seems like a lot to monitor,
but don't worry -- you really need only actively follow Piazza.
I will release announcements there any time assignments or videos are posted,
and I will post links to them directly on this page.

Be sure to read through the [syllabus](syllabus.md) for course policies,
contact information, and other important info.

## Schedule

** Note: This is an estimated timeline and subject to change. **

| Week | Topics | Readings | Deliverables |
| ---- | ------ | -------- | ------------ |
|  1   | Introduction<br>[intro slides](slides/intro.pdf)<br>Combinational circuits<br>[circuits slides](slides/boolean-circuits.pdf)<br>[circuit representation slides](slides/boolean-representations.pdf)<br>[conversion slides](slides/boolean-conversions.pdf)<br>[SOP & PLA slides](slides/boolean-sop.pdf)<br>[logical completeness slides](slides/boolean-logical-completeness.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=18f7e06a-1a87-430c-ba9e-393c1242f95e) | Chapter 1 | **Friday 1/22** [Syllabus quiz](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309007) |
|  2   | Binary numbers<br>[intro slides](slides/binary-intro.pdf)<br>[usage slides](slides/binary-use.pdf)<br>[tricks/tips slides](slides/binary-hex.pdf)<br>Negative binary numbers<br>[sign-magnitude slides](slides/binary-sign-magnitude.pdf)<br>[two's complement slides](slides/binary-twos-complement.pdf)<br>[overflow slides](slides/binary-overflow.pdf)<br>Boolean algebra<br>[simplification slides](slides/boolean-simplify.pdf)<br>Ripple-carry adder<br>[half adder slides](slides/half-adder.pdf)<br>[ripple-carry adder slides](slides/ripple-carry-adder.pdf)<br>Circuit Timing<br>[circuit timing slides](slides/circuit-timing.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=a4e3f4e5-9f2d-4686-b3b1-4b5e23550955)<br>[Monday activity](activities/week-01-intro.md) | 2.1 - 2.5 | **Monday 1/25** [Lab partner survey](https://forms.gle/WTAUJEqDJLfBxr6AA)<br>**Tuesday 1/26** [DLUnit Lab](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309105) |
|  3   | Ripple-Carry Timing<br>[ripple-carry timing slides](slides/ripple-carry-timing.pdf)<br>Multiplexors<br>[multiplexor slides](slides/muxes.pdf)<br>Carry-select adder<br>[carry-select slides part 1](slides/carry-select-part1.pdf)<br>[carry-select slides part 2](slides/carry-select-part2.pdf)<br>Carry-lookahead adder<br>[carry-lookahead slides part 1](slides/carry-lookahead-part1.pdf)<br>[carry-lookahead slides part 2](slides/carry-lookahead-part2.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=4faf36cd-3b69-4534-9e4a-3dc5fc070e18)<br>[Monday activity](activities/week-02-binary-adder.md) | | **Tuesday 2/2** [Homework 1](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309285)<br>**Tuesday 2/2** [Breadboard Lab 1](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309376) |
|  4   | Karnaugh Maps<br>[k-map slides](slides/karnaugh-maps.pdf)<br>Latches<br>[latches slides](slides/latches.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=b861270f-4cce-4673-bfdc-2315dd0ffdd0)<br>[Monday activity](activities/week-03-faster-adders.md) | | **Tuesday 2/9** [Adder Lab](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309538) |
|  5   | Flip-flops<br>Synchronous sequential circuits<br>[flip-flop slides](slides/flip-flops.pdf)<br>[synchronous sequential slides](slides/synchronous-sequential.pdf)<br>[timing sequential slides](slides/sequential-timing.pdf)<br>Pipelining<br>[pipelining slides](slides/pipelining.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=31ee9429-15c6-4551-8373-42a7b39d0b88)<br>[Monday activity](activities/week-04-kmaps-latches.md)<br><br>[Practice Exam 1](practice-exams/practice-exam-1.pdf) | | **Tuesday 2/16** [HW 2](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309679) |
|  6   | Turning circuits into computers<br>[building computer handout](misc/architecture-intro-handout.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=10533129-10c0-4e3d-86d9-4c137f58be86) | | **Monday 2/22** [Project 1 (standard credit)](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309626)<br>**Tuesday 2/23** [Sequential Circuits Lab](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309769)<br>**Wednesday, February 24** Midterm Exam 1 (during lab) |
|  7   | Computer Architecture<br>[architecture](slides/arch-intro.pdf)<br>[automatic computer](slides/arch-automatic-computer.pdf)<br>[R-type datapath](slides/arch-mips-r-type.pdf)<br><br>I-type instructions<br>[I-type](slides/arch-mips-i-type.pdf)<br>[I-type implementation](slides/arch-impl-i-type.pdf)<br><br>Branches<br>[conditional branching](slides/arch-branches.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=a73ca91a-07b4-42e2-8a70-4d340bdd422d) | | **Monday 3/1** [Project 2 (standard credit)](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309627)|
|  8   | Unconditional branch (jump)<br>[jump](slides/arch-jump.pdf)<br><br>Assembly programming constructs<br>[conditionals (if statements)](slides/assembly-conditionals.pdf)<br>[loops](slides/assembly-loops.pdf)<br><br>Branch microarchitecture<br>[implementing branch](slides/arch-impl-beq.pdf)<br><br>Memory load/store<br>[memory instructions](slides/arch-memory.pdf)<br>[load/store implementation](slides/arch-lw-full-impl.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=7f103015-13e6-4450-9e1d-52c0439e8d6a)<br>[Monday activity](activities/week-07-architecture.md) | | **Tuesday 3/9** [Homework 3](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309945)<br>**Tuesday 3/9** [Assembly Intro Lab](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309989) |
|  9   | Control logic<br>[control logic](slides/arch-control-logic.pdf)<br><br>Arrays<br>[arrays](slides/assembly-arrays-intro.pdf)<br>[arrays and loops](slides/assembly-arrays-loops.pdf)<br><br>Functions<br>[functions](slides/assembly-functions.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=cbcf360d-a5bd-4cee-a2c9-c15fd9b1b36e)<br>[Monday activity](activities/week-08-load-store.md)<br><br>[Practice Exam 2](practice-exams/practice-exam-2.pdf) | | **Monday 3/15** [Project 3 (standard credit)](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309971) |
|  10  | Stack<br>[stack](slides/assembly-stack.pdf)<br>[recursion](slides/assembly-recursion.pdf)<br><br>Memory<br>[memory map](slides/arch-map-memory.pdf)<br>[loading and executing](slides/arch-loading.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=1829be2d-eb09-4d96-8dda-3af8a615ce42) | | **Monday 3/22** [Homework 4a](https://www.prairielearn.org/pl/course_instance/128492/assessment/2310163)<br>**Monday 3/22** [Homework 4b](https://www.prairielearn.org/pl/course_instance/128492/assessment/2310164)<br>**Tuesday 3/23** [Branches lab](https://www.prairielearn.org/pl/course_instance/128492/assessment/2310270)<br>**Wednesday 3/24** Midterm Exam 2 (during lab) |
|  11  | Memory<br>[data segment code](code-examples/data-segment-final.asm)<br>[heap code](code-examples/malloc.asm)<br>[generic debugging code](code-examples/generic-debug.asm)<br>[stack vs heap vs global (optional -- no video)](code-examples/stack-heap-global.asm)<br><br>Cache motivation<br>[cache motivation](slides/cache-motivation.pdf)<br><br>Direct-mapped cache<br>[direct-mapped cache](slides/cache-direct-map.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=b451fca2-50fc-4b53-8605-e8a25ca4488e)<br>[Monday activity](activities/week-10-programming.md) | | **Tuesday 3/30** [Loops lab](https://www.prairielearn.org/pl/course_instance/128492/assessment/2310271) |
|  12  | Cache conflicts<br>[cache conflicts](slides/cache-direct-conflict.pdf)<br><br>Associative cache<br>[associative cache mapping](slides/cache-associative-map.pdf)<br>[associative cache conflicts (LRU)](slides/cache-associative-conflict.pdf)<br><br>Varying block size in cache<br>[mapping with larger block sizes](slides/cache-block-map.pdf)<br>[blocks of addresses](slides/cache-block-addresses.pdf)<br>[associativity vs block size and address bits](slides/cache-type-comparison.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=4778b0da-5b83-444d-bfeb-3a7f7629c504)<br>[Monday activity](misc/week-11-direct-cache.md) | | **Tuesday 4/6** [Recursion Lab](https://www.prairielearn.org/pl/course_instance/128492/assessment/2310444) |
|  13  | Cache performance<br>Basic pipelining in MIPS | | **Tuesday 4/13** [Stack homework](https://www.prairielearn.org/pl/course_instance/128492/assessment/2310443) |
|  14  | Data and Control Hazards | | |
|  15  | **Final Exam** | | |
