---
title: "CS1200 Discrete Mathematics for CS - I"
subtitle: July - Nov 2025
page-layout: full
lightbox: true
format:
  html:
    grid:
      sidebar-width: 400px
listing:
  - id: lectures
    type: table
    contents: lectures.yml
    template: lectures.ejs
    page-size: 100
include-in-header: 
  - text: |
      <style>
      .panel-tabset > .nav-tabs,
      .panel-tabset > .tab-content{
        border:none;
      }

      .nav-pills .nav-item{
        margin-left: 5px;
        margin-right: 5px;
      }

      .nav-pills .nav-link {
        background-color: #ccf7f1;
        border-radius: 3px;
      }

      .nav-pills .nav-link.active{
        background-color: #ffdd00; 
        color: #1c1c1c;
        border-radius: 3px;
      }
      
      .nav-pills .nav-link:hover {
        text-decoration: underline dotted;
        color: #0F096A;
      }

      </style>
---

::: nav-pills
::: panel-tabset


## home

::: {.grid}

::: {.g-col-2}
:::

::: {.g-col-8}

[![](existence_proof.png)](https://xkcd.com/1856/)

:::

::: {.g-col-2}
:::

:::

::: {.grid}

::: {.g-col-6}

###  {{< bi compass color=#40CB2D >}} Coordinates

- **Where**: SSB 134
- **When**: C slot - Mon (10 am), Tue (9 am), Wed (8 am), Fri (12 pm)


### {{< bi person-fill color=#40CB2D >}} Course staff

- **Instructor**: [Yadu Vasudev](https://yaduvasudev.github.io/) (yadu@cse.iitm.ac.in)
- **TAs**:
  - Alan (cs24m006@smail)
  - Aditya (cs25m007@smail)
  - Drone (cs22b005@smail)
  - Kunal (cs25s020@smail)
  - Mihir (cs22b004@smail)
  - Nagashri (cs21d004@smail)
  - Sutanay (cs21d005@smail)
  - Swapnil (cs25m051@smail)
:::

::: {.g-col-6}

### {{< bi link-45deg color=#40CB2D >}} Important links

- [Moodle](https://courses.iitm.ac.in/course/view.php?id=9775) 
- [Ed Discussions](https://edstem.org/us/courses/80766) \
  Join using your smail/iitm ids via [this link](https://edstem.org/us/join/2z3GaR)
- [Anonymous course feedback](https://forms.gle/Ks6qFLxgW5xgAQiy5)

:::

:::
---

::: {.grid}


::: {.g-col-12}

### {{< bi calendar-month color=#40CB2D >}} Course calendar

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=2&ctz=Asia%2FKolkata&showPrint=0&mode=WEEK&title=CS%201200%20(July%20-%20Nov%202025)&src=Y19jZjgxZDRkM2QxODEzNTA5YTMwODg0NWVkZWQ3YzE1Y2IwNDY0YmJiNzMxZDdlYjI4YmNiNzczYzdmNzM4YzAxQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%237cb342" style="border:solid 1px #777" width="1100" height="600" frameborder="0" scrolling="no"></iframe>

:::

:::
  
## contents

::: {.grid}

::: {.g-col-10}

#### {{< bi body-text color=#40CB2D >}} About this course

Design of computer systems involve describing specifications of the systems, developing algorithms that meet the specifications, and developing the actual system/program that implements the algorithms. At each step of this process, we require a way to describe the system in a formal/mathematical way so that the solutions can then be verified. We will study the underlying mathematical abstractions that are necessary to perform these tasks, and methods to mathematically prove the correctness of our designs/constructions. 

This course is mathematical in nature, and will require you to state and prove theorems. You will not be actually designing computer systems in the course, but the topics are motivated by the applications that you will see in computer science.

**Prerequisites** - There are no formal prerequisites for the course, apart from high-school mathematics. This course together with CS1202 (Discrete Math for CS - II) form a prerequisite for almost all courses in the CS curriculum.
---

#### {{< bi card-list color=#40CB2D >}} Course contents

The course will look at the following three broad themes. The order of the topics covered may vary.

- **Sets, logic and proofs** - Representation of sets, propositional and predicate logic, truth tables, deduction and resolution, mathematical proofs, infinite sets - countable and uncountable sets, Cantor's diagonalization, mathematical induction
- **Counting and combinatorics** - Sum and product rule, principle of inclusion-exclusion, pigeonhole principle, double counting and counting by bijections, recurrence relations, generating functions
- **Structures on sets** - relations, functions, graphs and trees, posets, lattices, and Haase diagrams, fixed points

---

#### {{< bi book-fill color=#40CB2D >}} Course resources

Our main sources of reference will be the following textbooks.

1. **Discrete Mathematics and its Applications** (Kenneth H. Rosen)
2. **[Mathematics for Computer Science](https://courses.csail.mit.edu/6.042/spring18/mcs.pdf)** (Eric Lehman, F. Thomas Leighton, Albert R. Meyer)

Apart from this, there are a lot of resources available online. We may refer to them occasionally. Both the books contain a number of exercise problems for practice. 

:::

:::

## administrivia

::: {.grid}

::: {.g-col-10}

#### {{< bi clock-fill color=#40CB2D >}} Weekly schedule

There are four lecture slots per week. We will have tutorials and short exams after every 5-6 lectures. The exact schedule is given in the course calendar that is shared. The tutorials are ungraded and meant for solving practice problems associated with the concepts taught during the lectures. They are vital for gaining better understanding of the material and must not be missed.

Apart from the tutorials, you are welcome to use the course discussion forum to clarify doubts with the instructor and the TAs. 

---

#### {{< bi percent color=#40CB2D >}} Grading policy (tentative)

- Short exams: 3*10 = 30% 
- Quizzes: 2*15 = 30%
- End-semester exam = 40%

---

#### {{< bi calendar-fill color=#40CB2D >}} Important dates (tentative)

- Tutorials (ungraded): Aug 13, Aug 25, Sep 10, Sep 22, Oct 3, Oct 15, Oct 29, Nov 11
- Short exams: Aug 29, Oct 1, Nov 3
- Quizzes (according to institute calendar): Sep 3, Oct 8
- End-semester (according to institute calendar): Nov 18 

---

#### {{< bi chat-dots-fill color=#40CB2D >}} Communication

Please sign up on the course discussion forum [here](https://edstem.org/us/join/2z3GaR). This will be the first point of contact for any issues related to the course. For general questions related to the course (any comments/doubts), please create a thread in the correct category and add your question/comment there. You are encouraged to reply and clear the doubts of your friends. To encourage this interaction, **the forum supports anonymous posts and answers**. **Please be courteous to others when you are posting anonymously**.

:::

:::

## lectures

::: {#lectures}


:::

:::

:::
