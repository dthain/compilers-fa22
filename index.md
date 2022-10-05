# CSE 40243 - Compilers and Language Design - Fall 2022

## Instructors

|----|----|
|![](images/dthain-small.jpg)| Prof. Douglas Thain (`dthain@nd.edu`)<br> Office Hours: 1-3PM Tue/Thu <br> Office: 384 Fitpatrick Hall|
|![](images/nziems2-small.jpg)| TA: Noah Ziems (`nziems2@nd.edu`)<br> Office Hours: 3-5PM Mon/Wed <br> Office: 150B Fitpatrick Hall (Student Commons)|

## Online Textbook

|----|----|
|![](images/compilerbook-small.jpg)| Douglas Thain,<br>Introduction to Compilers and Language Design,<br>2nd edition, 2020.<br>[http://compilerbook.org](http://compilerbook.org)

## Important Documents

- [Course Syllabus](syllabus.md)
- [Slack Channel](https://nd-cse.slack.com/channels/compilers-fa22)
- [Online Textbook](http://compilerbook.org)
- [Canvas Course Page](https://canvas.nd.edu/courses/52550)
- [General Assignment Instructions](general.md)
- [Starter Code](https://github.com/dthain/compilerbook-starter-code)
- [Flex Scanner Generator](https://westes.github.io/flex/manual/)
- [Bison Parser Generator](https://www.gnu.org/software/bison/manual/html_node/index.html)
- [B-Minor 2022 Language Guide](bminor.md)

## Course Schedule

(Subject to change as needed.)

|Week | Reading | Monday | Wednesday | Friday | Assignment | Extra Links |
|-----|---------|-------|------------|--------|------------|-------------|
|Aug 22 | Ch 1-2     |                 | Introduction | Overview        | [Syllabus](syllabus.md)  |
|Aug 29 | Ch 3       | Regular Expressions | Finite Automata       | RE->NFA    | [HW1 Due Wed](homework.md) | / [Hand Parser](https://github.com/cooperative-computing-lab/cctools/blob/master/dttools/src/jx_parse.c#L254) / [Regex 101](https://regex101.com/) / [Regex Golf](http://alf.nu/RegexGolf?world=regex&level=r02) / [Unicode](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/) |
|Sep 5  | Ch 3       | NFA->DFA            | Flex | Context Free Grammars | [HW2 Due Wed](homework.md) | [Flex Scanner Generator](https://westes.github.io/flex/manual/)
|Sep 12 | Ch 4.1-4.3 | Context Free Grammars | LL(1) Grammars | LL(1) Parsing   | [Scanner Due](scanner.md) | [CFG Tool](https://web.stanford.edu/class/archive/cs/cs103/cs103.1156/tools/cfg/) / [Joke](https://xkcd.com/1090/)
|Sep 19 | Ch 4.4-4.6 |  Shift-Reduce Parsing  | LR(0) Automaton  | SLR Parsing         | [HW3 Due Wed](homework.md) |
|Sep 26 | Ch 5      | LR(1) and Recap  | Bison           | Bison  | [HW4 Due Wed](homework.md) | [Bison Manual](https://www.gnu.org/software/bison/manual/html_node/index.html) / [Examples](https://github.com/dthain/compilerbook-examples/tree/master/chapter5) |
|Oct 3  | Ch 5       | Parsing B-Minor | Parsing B-Minor     | Abstract Syntax Tree |  | [AST Handout](ast.html) |
|Oct 10 | Ch 6       | Abstract Syntax Tree | Review              | **Midterm Exam** |  [Parser Due Mon](parser.md) |
|Oct 17 |            | *Fall Break*    | *Fall Break*          | *Fall Break*     |                   |
|Oct 24 | Ch 7       | Type Systems    | Name Resolution       | Typechecking     |                   |
|Oct 31 | Ch 9       | Memory Org      | Memory Org            | Guest Lecture    | [Printer Due Mon](printer.md)|
|Nov 7  | Ch 10      | Assembly        | Assembly              | Assembly         |                   |
|Nov 14 | Ch 11      | Codegen         | Codegen               | Codegen          | [Typecheck Due Mon](typecheck.md)|
|Nov 21 | Ch 11      | Codegen         | *Thanksgiving*        | *Thanksgiving*   |                   |
|Nov 28 | Ch 12      | Optimization    | Garbage Coll.         | Garbage Coll.    |
|Dec 5  |            | Catch Up        | Review                |                  |  Code Generator Due Wed|
|Dec 12 |            |                 |                       | **Final Exam** 8-10AM Friday Dec 16  |                   |

