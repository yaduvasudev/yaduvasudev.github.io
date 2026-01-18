---
title: "CS4700 Advanced Data Structures"
subtitle: Jan - May 2026
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

::: {.g-col-6}

###  {{< bi compass color=#40CB2D >}} Coordinates

- **Where**: SSB 134
- **When**: G slot - Mon (12 pm), Wed (5 pm), Thu (10 am), Fri (9 am)


### {{< bi person-fill color=#40CB2D >}} Course staff

- **Instructor**: [Yadu Vasudev](https://yaduvasudev.github.io/) (yadu@cse.iitm.ac.in)
- **TAs**:
  - Aditya (cs25m007@smail)
  - Alan (cs24m006@smail)
  - Chetan (cs25s022@smail)
  - Deepak (cs25m019@smail)
  - Neha (cs21d408@smail)
  - Shivam (cs25m048@smail)

:::

::: {.g-col-6}

### {{< bi link-45deg color=#40CB2D >}} Important links

- [Moodle](https://courses.iitm.ac.in/course/view.php?id=11117) 
- [Ed Discussions](https://edstem.org/us/courses/91442/discussion) \
  Join using your smail/iitm ids via [this link](https://edstem.org/us/join/xtCSfa)
- [Anonymous course feedback](https://forms.gle/q7fLYEMwryHJ3pt7A)

:::

:::
---

::: {.grid}


::: {.g-col-12}

### {{< bi calendar-month color=#40CB2D >}} Course calendar

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=2&ctz=Asia%2FKolkata&showPrint=0&mode=WEEK&src=Y180NjUwN2FhOThiMWMxOWI4ZTRiYzY3NTg3OGU1ZmZmNjhhYjgwYmU2N2NmODJhOWQzNTcwOTBjNTQ2MzE3M2ZlQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%23c0ca33" style="border:solid 1px #777" width="1100" height="600" frameborder="0" scrolling="no"></iframe>
:::

:::
  
## contents

::: {.grid}

::: {.g-col-10}

#### {{< bi body-text color=#40CB2D >}} About this course

This is a second course in data structures, and builds on the material covered in CS2700 (Programming and data structures). We will look at the design of various data structures for dictionaries, priority queues, dynamic graphs, and range queries . There will be an emphasis on understanding the design principles for various data structures, and a rigorous analysis of their complexity. At the end of the course, the student is expected to know the design and analysis of a variety of advanced data structures, and be able to design new data structures for specific applications.

**Prerequisites** - Programming and data structures (CS2700) or an equivalent course is a prerequisite for this course. A course in algorithm design and analysis would be useful, but not necessary. Programming experience is not necessary, but is recommended.
---

#### {{< bi card-list color=#40CB2D >}} Course contents

The following are the broad topics that will be covered in this course.

- **Recall of algorithm analysis** - Asymptotic notation, amortized analysis, basics of probablistic analysis.
- **Dictionaries** - Hash tables, skip lists, balanced search trees, tries
- **Priority queues** - Recall of binary heaps, min-max heaps, mergable heaps - binomial and Fibonacci heaps
- **Geometric data structures** - Range queries and searching, kd-trees, segment trees
- **Dynamic graphs** - Link-cut trees, Euler-tour trees, heavy-light decomposition, dynamic connectivity
- **Persistent data structures** - Partial and fully persistent data structures for lists, trees, heaps

---

#### {{< bi book-fill color=#40CB2D >}} Course resources

There is no single textbook for the course. The following two books contain some of the material that will be covered in the course, especially the first half.

1. **[Open Data Structures](https://opendatastructures.org/)** by Pat Morin
2. **Introduction to Algorithms** by Cormen, Leiserson, Rivest, and Stein

Apart from this, there are a lot of resources available online. We may refer to them occasionally. 

:::

:::

## administrivia

::: {.grid}

::: {.g-col-10}

#### {{< bi clock-fill color=#40CB2D >}} Weekly schedule

There are four lecture slots per week. We will convert some of them into tutorial sessions and short exams. The tentative schedule is given below. You are welcome to use the course discussion forum to clarify doubts with the instructor and the TAs. 

---

#### {{< bi percent color=#40CB2D >}} Grading policy (tentative)

- Assignments: 2*10 = 20%
- Short exams: 2*10 = 20% 
- Quizzes: 2*15 = 30%
- End-semester exam = 30%

---

#### {{< bi calendar-fill color=#40CB2D >}} Important dates (tentative)

- Assignment (deadlines): Mar 9, Apr 27
- Short exams: Feb 11, Apr 15
- Quizzes (according to institute calendar): Feb 25, Mar 27
- End-semester (according to institute calendar): May 14 

---

#### {{< bi chat-dots-fill color=#40CB2D >}} Communication

Please sign up on the course discussion forum [here](https://edstem.org/us/join/xtCSfa). This will be the first point of contact for any issues related to the course. For general questions related to the course (any comments/doubts), please create a thread in the correct category and add your question/comment there. You are encouraged to reply and clear the doubts of your friends. To encourage this interaction, **the forum supports anonymous posts and answers**. **Please be courteous to others when you are posting anonymously**.

:::

:::

## lectures

::: {#lectures}


:::

:::

:::
