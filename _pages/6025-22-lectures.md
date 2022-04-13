---
layout: single
permalink: courses/6025/22/lectures.html
classes: wide
sidebar:
  nav: "courses"
title: CS6025 Sublinear Algorithms
---

## Jan-May 2022

{::options parse_block_html="true" /}
<div class="notice--info">
The lecture videos and notes written during the lectures are available in the links below.
- [Lectures](https://drive.google.com/drive/folders/1Ip-Ow2DhP5-cBkDiI44uJ_mwhnMZjyhN?usp=sharing) (till Jan 27)
- [Scribbles](https://drive.google.com/drive/folders/1bpaONejdSOU0yu0blv9rYYdGxIw6OqFZ?usp=sharing)
</div>
{::options parse_block_html="false" /}

Week 1, Jan 17-21
: Outline of the course; logistics; reservoir sampling; parameter estimation; basic probability and concentration bounds; Probabilistic counting - Morris counter.
- References:
    - Probability and Computing - Mitzenmacher and Upfal (Chapters 1-4 for brushing up basic discrete probability)
    - Jelani Nelson's [notes](https://www.sketchingbigdata.org/fall20/lec/notes.pdf)
    - [Notes](https://drive.google.com/file/d/1DIy1HJbasqZ6vkkQNNToWniEeGQ36F_f/view?usp=sharing) from a previous offering of this course (incomplete and unedited)
- Additional reading: [Optimal bounds for approximate counting](https://arxiv.org/pdf/2010.02116.pdf) - Nelson and Yu

---

Week 2, Jan 24-28
: Frequency moments - counting distinct elements; Flajolet-Martin algorithm; BJKST's algorithm and analysis; Pairwise-independent hash families.
- References:
    - Jelani Nelson's [notes](https://www.sketchingbigdata.org/fall20/lec/notes.pdf)
    - [Notes](https://drive.google.com/file/d/1DIy1HJbasqZ6vkkQNNToWniEeGQ36F_f/view?usp=sharing) from a previous offering of this course (incomplete and unedited)
- Additional reading:
    - [HyperLogLog - the analysis of a near-optimal
cardinality estimation algorithm](http://algo.inria.fr/flajolet/Publications/FlFuGaMe07.pdf) - Flajolet, Fusy, Gandouet, Meunier
    - [Wikipedia entry](https://en.wikipedia.org/wiki/HyperLogLog) for HyperLogLog
    - [Counting distinct elements in a data stream](http://cs.haifa.ac.il/~ilan/randomized_algorithms/bar-yosef_jayram.pdf) - Bar-Yossef, Jayram, Kumar, Sivakumar, Trevisan.

---

Week 3, Jan 31-Feb 4
: Counting distinct elements in turstile streams; Linear sketching; Nisan's PRG; Frequency moments - AMS algorithm and sketch for $$F_2$$.
- Videos: [Jan 31](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=42e74864dbe623c846e861e45d910040), [Feb 2](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=eb934d595ad3fef69250bd9d6ae9034c), [Feb 3](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=1366544ba2063cab74ffddcf42f8f2b8)
- References:
    - Jelani Nelson's [notes](https://www.sketchingbigdata.org/fall20/lec/notes.pdf)
    - [Notes](https://drive.google.com/file/d/1DIy1HJbasqZ6vkkQNNToWniEeGQ36F_f/view?usp=sharing) from a previous offering of this course (incomplete and unedited)
- Additional reading:
    - [The Space Complexity of Approximating the Frequency Moments](https://www.sciencedirect.com/science/article/pii/S0022000097915452) - Alon, Matias, Szegedy.
    - [Stable Distributions, Pseudorandom Generators,
Embeddings, and Data Stream Computation](https://dl.acm.org/doi/10.1145/1147954.1147955) - Indyk.

---

Week 4, Feb 7-11
: Heavy-hitters problem - CountMin sketch and Count sketch; $$\ell_0$$-sampling and sparse recovery.
- Videos: [Feb 7](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=54451fc296a8f5b77beb3a51d4a36898), [Feb 9](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=20e707c952c4a84a7ed0cb094c1a5e75), [Feb 10](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=f9c84ea6f2739c71d3918393d65ff073)
- References:
    - Jelani Nelson's [notes](https://www.sketchingbigdata.org/fall20/lec/notes.pdf)
    - [Notes](https://drive.google.com/file/d/1DIy1HJbasqZ6vkkQNNToWniEeGQ36F_f/view?usp=sharing) from a previous offering of this course (incomplete and unedited)
- Additional reading:
    - [An Improved Data Stream Summary: The Count-Min Sketch and its Applications](http://dimacs.rutgers.edu/~graham/pubs/papers/cm-full.pdf) - Cormode, Muthukrishnan.
    - [Finding Frequent Items in Data Streams](https://people.cs.rutgers.edu/~farach/pubs/FrequentStream.pdf) - Charikar, Chen, Farch-Colton.

---

Week 5, Feb 14-18
: $$\ell_0$$-sampling and sparse recovery (contd.), Graph streams - connectivity, spanners, sparsifiers, triangle counting.
- Videos: [Feb 14](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=8d17a8b838d8baa21dc0ec3b40eb2df2), [Feb 16](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=38bed31dc1a2157766879db2e8611dbe), [Feb 17](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=a2e11c1002dcd4c5f6b6755e283aca82)
- References:
    - Jelani Nelson's [notes](https://www.sketchingbigdata.org/fall20/lec/notes.pdf)
    - [Notes](https://drive.google.com/file/d/1DIy1HJbasqZ6vkkQNNToWniEeGQ36F_f/view?usp=sharing) from a previous offering of this course (incomplete and unedited)
    - [Graph Stream Algorithms: A Survey](https://people.cs.umass.edu/~mcgregor/papers/13-graphsurvey.pdf) - McGregor

---

Week 6, Feb 21-25
: Graph streams - random walks; Graph sketches - connectivity in fully dynamic streams; Lower bounds for streaming algorithms - intro to communication complexity.
- Videos: [Feb 21](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=aefeeeb2de301c298ad56963b61bf5b0), [Feb 23](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=ca8288e765ff71a09fb6e8c5c3930dcb), [Feb 24](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=67088186eb70992b4321a897e95d3040)
- References:
    - [Notes](https://drive.google.com/file/d/1DIy1HJbasqZ6vkkQNNToWniEeGQ36F_f/view?usp=sharing) from a previous offering of this course (incomplete and unedited)
    - [Graph Stream Algorithms: A Survey](https://people.cs.umass.edu/~mcgregor/papers/13-graphsurvey.pdf) - McGregor
    - **[RY]**
- Additional reading:
    - [Estimating PageRank on Graph Streams](https://www.cs.dartmouth.edu/~ac/Teach/CS49-Fall11/Papers/dassarma-pagerank.pdf) - Das Sarma, Gollapudi, Panigrahy.

---

Week 7, Feb 28-Mar 4
: Lower bounds for streaming algorithms using communication complexity.
- Videos: [Feb 28](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=7bb4806f9ea8da95ac6a3730cdf3605f), [Mar 2](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=b54bf1f8631965859b691b93b2a19fab), [Mar 3](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=475e1c361c22f6f5308e7044d2c41f58)
- References:
    - [Notes](https://drive.google.com/file/d/1DIy1HJbasqZ6vkkQNNToWniEeGQ36F_f/view?usp=sharing) from a previous offering of this course (incomplete and unedited)
    - **[RY]**

---

Week 8, Mar 7-11
: Introduction to property testing; Testing linearity - the BLR test; Fourier analysis of Boolean functions.
- Videos: [Mar 7](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=127b8359dda7331d11e1a31c2f2efb2a), [Mar 9](https://iitmadras.webex.com/iitmadras/ldr.php?RCID=5147e543a3ebe24cc7944f0f358a9b00)
- References:
    - Chapter 1 - [Analysis of Boolean Functions](https://arxiv.org/pdf/2105.10386.pdf) by O'Donnell

---

Week 9, Mar 14-18
: PAC learning and Fourier concentration - decision trees; Dictatorship testing.
- References:
    - Chapters 2, 3, 7 - [Analysis of Boolean Functions](https://arxiv.org/pdf/2105.10386.pdf) by O'Donnell

---

Week 10, Mar 21-25
: Testing monotonicity of Boolean functions; Lower bounds for monotonicity testing; Graph property testing in the dense model - biclique and bipartiteness.
- References:
    - Servedio's [lecture notes](http://www.cs.columbia.edu/~rocco/Teaching/S14/Scribe/lecture8.pdf)
    - Chapter 8 - [Introduction to Property Testing](https://www.wisdom.weizmann.ac.il/~oded/PDF/pt-v3.pdf) by Goldreich

---

Week 11, Mar 28-Apr 1
: Canonical testers for graph properties; Triangle-freeness testing; Szemeredi regularity lemma and characterization of constant-query testable properties; Testing properties of sparse graphs
- References
    - Chapter 8,9 - [Introduction to Property Testing](https://www.wisdom.weizmann.ac.il/~oded/PDF/pt-v3.pdf) by Goldreich
    - Chapter 17 - The Probabilistic Method by Alon, Spencer
    - [Lecture notes](https://ocw.mit.edu/courses/18-217-graph-theory-and-additive-combinatorics-fall-2019/a5281a219e31cddd10e5fe74434087a9_MIT18_217F19_ch3.pdf) on Regularity lemma and graph removal lemmas by Zhao
    - [Three Theorems Regarding Testing Graph Properties](http://theory.stanford.edu/~trevisan/pubs/gt03.pdf) by Goldreich, Trevisan

---

Week 12, Apr 4-8
: Connectivity testing; estimating the number of connected components; Cycle-freeness - one-sided and two-sided testers; One-sided tester for bipartiteness; Lower bound for bipartiteness testing
- References
    - Chapter 9 - [Introduction to Property Testing](https://www.wisdom.weizmann.ac.il/~oded/PDF/pt-v3.pdf) by Goldreich
    - [Property Testing in Bounded Degree Graphs](https://www.cs.princeton.edu/courses/archive/spr04/cos598B/bib/GoldreichR-boundedG.pdf) - Goldreich and Ron
    - Assadi's [lecture notes](https://people.cs.rutgers.edu/~sa1497/courses/cs514-s20/lec2.pdf)
- Additional reading:
    - [A Sublinear Bipartiteness Tester for Bounded Degree Graphs](https://www.cs.princeton.edu/courses/archive/spr04/cos598B/bib/GoldreichR-bipartTest.pdf) - Goldreich and Ron

---

Week 13, Apr 11-15
: Partition oracles and applications - testing minor-closed properties
- References
    - Chapter 9 - [Introduction to Property Testing](https://www.wisdom.weizmann.ac.il/~oded/PDF/pt-v3.pdf) by Goldreich
    - [Local Graph Partitions for Approximation and Testing](https://math.mit.edu/~kelner/publications/localPartitioningConference.pdf) - Hassidim, Kelner, Nguyen and Onak
