# CSE 40243 - Compilers and Language Design - Fall 2022

## Instructors

|----|----|
|![](images/dthain-small.jpg)| Prof. Douglas Thain (`dthain@nd.edu`)<br> Office Hours: 1-3PM Tue/Thu <br> Office: 384 Fitpatrick Hall|
|![](images/nziems2-small.jpg)| TA: Noah Ziems (`nziems2@nd.edu`)<br> Office Hours: 2-4PM Mon/Wed <br> Office: 150B Fitpatrick Hall (Student Commons)|

## Online Textbook

|----|----|
|![](images/compilerbook-small.jpg)| Douglas Thain,<br>Introduction to Compilers and Language Design,<br>2nd edition, 2020.<br>[http://compilerbook.org](http://compilerbook.org)

## Important Documents

- [Course Syllabus](syllabus.md)
- [Slack Channel](https://nd-cse.slack.com/channels/compilers-fa22)
- [Online Textbook](http://compilerbook.org)
- [Canvas Course Page](https://canvas.nd.edu/courses/52550)
- [Starter Code](https://github.com/dthain/compilerbook-starter-code)
- [Flex Scanner Generator](https://westes.github.io/flex/manual/)
- [Bison Parser Generator](https://www.gnu.org/software/bison/manual/html_node/index.html)
- [B-Minor 2022 Language Guide](bminor.md)

## Course Schedule

(Subject to change as needed.)

|Week | Reading | Monday | Wednesday | Friday | Assignment | Extra Links |
|-----|---------|-------|------------|--------|------------|-------------|
|Aug 22 | Ch 1-2     |                 | Introduction | Overview        | [Syllabus](syllabus.md)  |
|Aug 29 | Ch 3       | Regular Expressions | Finite Automata       | RE->NFA->DFA    | [HW1 Due Wed](homework.md) | / [Hand Parser](https://github.com/cooperative-computing-lab/cctools/blob/master/dttools/src/jx_parse.c#L254) / [Regex 101](https://regex101.com/) / [Regex Golf](http://alf.nu/RegexGolf?world=regex&level=r02) / [Unicode](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/) |
|Sep 5  | Ch 4.1-4.3 | Flex            | Context Free Grammars | LL(1) Grammars  | [HW2 Due Wed](homework.md) | 
|Sep 12 | Ch 4.3-4.6 | LL(1) Parsing   | Shift-Reduce Parsing  | LR(0) Automaton | [Scanner Due](scanner.md) |
|Sep 19 | Ch 5       | SLR Parsing     | LR(1) and Recap       | Bison           | [HW3 Due Wed](homework.md) |
|Sep 26 | Ch 6       | Parsing B-Minor | Abstract Syntax Tree  | Catch Up        | [HW4 Due Wed](homework.md) |
|Oct 3  | Ch 7       | Type Systems    | B-Minor Typing        | Name Resolution  | Parser Due Wed |
|Oct 10 |            | Type Checking   | Catch Up              | **Midterm Exam** |                   |
|Oct 17 |            | *Fall Break*    | *Fall Break*          | *Fall Break*     |                   |
|Oct 24 | Ch 8-9     | Intermediate Reps | Memory Org          | Memory Org       | Printer Due Wed   |
|Oct 31 | Ch 10      | Assembly        | Assembly              | Guest Lecture    |                   |
|Nov 7  |            | Assembly        | Assembly              | Codegen          | Typecheck Due Wed |
|Nov 14 | Ch 11      | Codegen         | Codegen               | Codegen          |                   |
|Nov 21 | Ch 12      | Optimization    |                       |                  |                   |
|Nov 28 |            | Optimization    | Garbage Coll.         | Garbage Coll     |
|Dec 5  |            | Catch Up        | Review                |                  |  Code Generator Due Wed|
