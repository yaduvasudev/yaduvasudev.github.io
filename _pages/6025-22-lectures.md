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
