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
|  7   | Computer Architecture<br>[architecture](slides/arch-intro.pdf)<br>[automatic computer](slides/arch-automatic-computer.pdf)<br>[R-type datapath](slides/arch-mips-r-type.pdf)<br><br>I-type instructions<br>[I-type](slides/arch-mips-i-type.pdf)<br>[I-type implementation](slides/arch-impl-i-type.pdf)<br>Branches<br>[conditional branching](slides/arch-branches.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25d3a943-1da6-4e69-b804-6f088a538887#plid=a73ca91a-07b4-42e2-8a70-4d340bdd422d) | | **Monday 3/1** [Project 2 (standard credit)](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309627)|
|  8   | Control logic<br>Memory load/store<br>Assembly programming constructs | | **Tuesday 3/9** [Homework 3](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309945) |
|  9   | Arrays<br>Stack | | **Monday 3/15** [Project 3 (standard credit)](https://www.prairielearn.org/pl/course_instance/128492/assessment/2309971) |
|  10  | Memory | | |
|  11  | Cache motivation<br>Direct-mapped cache | | |
|  12  | Associative cache<br>Varying block size in cache | | |
|  13  | Cache performance<br>Basic pipelining in MIPS | | |
|  14  | Data and Control Hazards | | |
|  15  | **Final Exam** | | |
