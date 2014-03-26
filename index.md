---
css.file: _fileherd/markdown7.css
dirs.to.publish:
  - .
---

# STAT540 Statistical methods for high dimensional biology

## Course Information

### Credits and cross-listing

STAT 540 is a 3 credit course with a mandatory computing seminar.

Cross-listed as

  * STAT 540
  * BIOF 540
  * GSAT 540

### Instructors

* [Jennifer Bryan](http://www.stat.ubc.ca/~jenny), Course coordinator
  (email is jenny@stat.ubc.ca), Statistics and Michael Smith Labs

* [Gabriela Cohen-Freue](http://www.stat.ubc.ca/~gcohen/), Statistics

* [Paul Pavlidis](http://www.chibi.ubc.ca/faculty/pavlidis), CHiBi and Psychiatry

### TA(s)

* [Shaun Jackman](http://sjackman.ca), sjackman@gmail.com

* [Luolan (Gloria) Li](http://www.msl.ubc.ca/users/gloriali), glorialuolanli@gmail.com

### Google Group for Q & A (TAs will add students to group in due course)

[STAT540_2014](https://groups.google.com/forum/#!forum/stat540_2014)

### GitHub repository

Vast majority of course content, including source for this website, can be found here:

<https://github.com/jennybc/stat540_2014>

### Datasets

`photoRec` data

  * It's in the [course repository](https://github.com/jennybc/stat540_2014)
    - it's in the [examples/photoRec](https://github.com/jennybc/stat540_2014/tree/master/examples/photoRec) directory
  * It's in the course website.
    - it's in the [examples/photoRec](http://www.ugrad.stat.ubc.ca/~stat540/examples/photoRec/) directory

### Time and Location

06 January 2014 - 07 April 2014

#### Lecture (Sec 201)
Time : Mon Wed 9:30 - 11am

Location : [ESB 4192](http://www.students.ubc.ca/classroomservices/buildings-and-classrooms/?code=ESB&room=4192)

#### Seminar / computing lab (S2A) -- REGISTRATION IS REQUIRED!
Time: *officially* runs Wed 12pm - 1pm; *unofficially* students are welcome to come after class around 11am and begin a ~1 hour guided analysis with TA support; TA will remain in the lab until 1pm to help those who start as 12pm and for general office hours.

Location: ESB 1042 __and 1046__

### Prerequisites.

Officially none BUT here in reality ...

* Statistics: you should have already taken university level introductory statistics course.

* Biology: No requirements, but you are expected to learn things like the difference between a DNA and RNA and a gene and a genome.

* R: no experience required but be prepared to do *a lot* of self-guided learning. Go ahead and start now by [installing R](http://www.r-project.org/) and the HIGHLY RECOMMENDED "integrated development environment" (IDE) [RStudio](http://www.rstudio.com)! Students are expected to run R on their own computer or a computer they have plenty of access to and control over. The best set-up, if possible, is to bring your own laptop to the computing seminars.

### Evaluation

* Homework. Two assignments worth 25 points each. [Homework #1](homework/hw01/hw01_quality-exploration-DE.html) was due Thurs Feb 27. [Homework #2](homework/hw02/hw02_array-rna-seq-dea.html) is due Fri March 28. Instructions for [how to submit homework](homework/hw_submission-instructions.html).

* [Group project](project/index.html). Groups formed and projects conceived during January/February. Primary deliverable is a poster, presented in last class meeting. Each student also produces a short report. 40 points. More more information, [go here](project/index.html).

* 10 points for "other", e.g. participation in class, seminars, and the Google group, engagement with *small* computing exercises.

## Syllabus

### Week 1

seminar 00 | [R, RStudio Set Up & Basics](http://www.stat.ubc.ca/~jenny/STAT545A/block00_setup.html), borrowed from STAT 545A. Students complete/attempt on their own in advance. Bring any difficulties to first seminar.

lecture 01 | Introduction to high dimensional biology and the course (PP) | Mon Jan 06 | [slides as PDF](pvt/lect01_course-intro.pdf)

lecture 02 | Overview / review of probability and statistical inference, 1 of 2 (JB) | Wed Jan 08 | [slides as PDF](pvt/lect02_introToStatInf-probBasics.pdf)

seminar 01 | [R basics and exploring a small gene expression dataset](#seminar01) | Wed Jan 08

  * [R stuff](#seminar01) 11am - 12pm (or later, if necessary)
  * Molecular biology/genetics 101 (LL), 12pm - 1pm | [slides as PDF](pvt/lect00_biology-intro.pdf)

### Week 2

lecture 03 | Overview / review of probability and statistical inference, 2 of 2 (JB) | Mon Jan 13  | [slides as PDF](pvt/lect03_introToStatInf-endProbBasics-genInfReview.pdf)

lecture 04 | Exploratory analysis (PP) | Wed Jan 15  | [slides as PDF](pvt/lect04_explore.pdf)

seminar 02 | [Learn more R while reviewing probability](#seminar02) (LL) | Wed Jan 15

### Week 3

lecture 05 | Data QC and preprocessing (JB for GC-F) | Mon Jan 20  | [slides as PDF](pvt/lect05_dataCleaning-qualityControl.pdf)

lecture 06 | Statistical inference: two group comparisons, e.g. differential expression analysis (JB) | Wed Jan 22  | [slides as PDF](pvt/lect06_two-groups.pdf)

seminar 03 | [R graphics AND `knitr`, R markdown, and git(hub)](#seminar03) | Wed Jan 22

  * Introduction to `knitr`, R markdown, and git(hub) 11:15am - 12pm SJ will run a guided, hands-on tutorial in one of the labs
  * R graphics (LL) content is ready to work through in the other lab, from 12 - 1pm, or on your own.

Fri Jan 24: Project groups should be formed. 

### Week 4

lecture 07 | Statistical inference: more than two groups --> linear models (JB prep, GCF deliver) | Mon Jan 27 | [slides as PDF](pvt/lect07_beyond-two-groups.pdf)

lecture 08 | Statistical inference: linear models with 2 categorical covariates, greatest hits of linear models inference (JB prep, GCF deliver) | Wed Jan 29 | [slides as PDF](pvt/lect08_moreThanOneCatCovariate-linModGreatestHits.pdf)

seminar 04 | [Two group testing and data aggregation](#seminar04) (SJ) | Wed Jan 29

Fri Jan 31: Initial project proposals due.

### Week 5

lecture 09 | Statistical inference: linear models including a quantitative covariate, fitting many linear models at once (JB) | Mon Feb 03  | [slides as PDF](pvt/lect09_quantCovariate-manyLinModAtOnce.pdf)

lecture 10 | Large scale inference: Empirical Bayes, limma (JB) | Wed Feb 05  | [slides as PDF](pvt/lect10_limma.pdf)

seminar 05 | [Fitting and interpretting linear models (low volume)](#seminar05) (SJ) | Wed Feb 05

Fri Feb 07: [Homework #1 assignment](homework/hw01/hw01_quality-exploration-DE.html) is posted. Due Thurs Feb 27.

### Week 6

Mon Feb 10 is Family Day; no class

lecture 11 | Large scale inference: multiple testing (JB) | Wed Feb 12 | [slides as PDF](pvt/lect11_multiple-testing.pdf)

seminar 06 | [Fitting and interpretting linear models (high volume), limma package](#seminar06) | Wed Feb 12

Fri Feb 14: feedback to groups re: initial project proposals. Each group will be assigned an instructor or TA + instructor pair for extra support.

### Week 7

(Mon Feb 17 UBC closed for mid-term break)

(Wed Feb 19 UBC closed for mid-term break)

### Week 8

lecture 12 | Analysis of RNA-Seq data (PP), 1 of 2 | Mon Feb 24 | [slides as PDF](pvt/lect12_RNA-seq-1.pdf)

lecture 13 | Analysis of RNA-Seq data (PP), 2 of 2 | Wed Feb 26 | [slides as PDF](pvt/lect13_RNA-seq-2.pdf)

seminar 07 | [RNA-Seq analysis](#seminar07) (SJ) | Wed Feb 26

Thurs Feb 27: [Homework #1](homework/hw01/hw01_quality-exploration-DE.html) due. 

### Week 9

lecture 14 | Analysis of epigenetic data, focus on methylation (Elodie Portales-Casamar) | Mon Mar 03 | [slides as PDF](pvt/lect14_methylation.pdf)
 
Wed Mar 05: final project proposals due. 
 
lecture 15 | Principal component analysis (PP) | Wed Mar 05 | [slides as PDF](pvt/lect15_PCA.pdf)

seminar 08 | [Methylation analysis](#seminar08) (LL) | Wed Mar 05

Fri Mar 07: [Homework #2](homework/hw02/hw02_array-rna-seq-dea.html) assigned 

### Week 10

lecture 16 | Cluster analysis (GC-F) | Mon Mar 10 | [slides as PDF](pvt/lect16_cluster-analysis.pdf)

lecture 17 | Classification (GC-F) | Wed Mar 12 | [slides as PDF](pvt/lect17_supervised-learning.pdf)

seminar 09 | [Clustering and PCA](#seminar09) (LL) | Wed Mar 12

### Week 11

lecture 18 | Model and variable selection: cross validation and regularization (GC-F) | Mon Mar 17 | [slides as PDF](pvt/lect18_cross-validation.pdf)

lecture 19 | Regularization cont'd, Proteomics and missingness (GC-F) | Wed Mar 19 | slides as PDF: [variable selection](pvt/lect19_I-vble-selection.pdf), [proteomics and missing values](pvt/lect19_II-proteomics-missingValues.pdf)

seminar 10 | [Supervised learning, cross validation, variable selection](#seminar10) (SJ) | Wed Mar 19

### Week 12

lecture 20 | Analysis of gene function, 1 of 2: Gene set analysis (PP) | Mon Mar 24 | [slides as PDF](pvt/lect20_gene-set-analysis.pdf)

lecture 21 | Analysis of gene function, 2 of 2 (PP) | Wed Mar 26 | [slides as PDF](pvt/lect21_gene-networks.pdf)

seminar 11 | TA office hours during seminar time ... group project work | Wed Mar 26

Fri Mar 28: [Homework #2](homework/hw02/hw02_array-rna-seq-dea.html) due.

### Week 13

lecture 22 | Resampling and the bootstrap (JB)| Mon Mar 31

lecture 23 | Guest lecture by STAT540 alum [Dr. Sohrab Shah](http://compbio.bccrc.ca/people/dr-sohrab-shah/) | Wed Apr 02

seminar 12 | TA office hours during seminar time ... group project work | Wed Apr 02

### Week 14

lecture 24 | Poster session 9:30am - 12:00pm | Wed Apr 09 __<-- NOTE THIS IS ON WEDNESDAY__, instead of Monday. Location: Room 101, aka the multi-purpose room, on ground floor of the [Michael Smith Building](http://www.maps.ubc.ca/PROD/index_detail.php?locat1=083).

## Seminars (guided analyses)

We will borrow some material from [STAT 545A Exploratory Analysis](http://www.stat.ubc.ca/~jenny/STAT545A/quick-index.html), in addition to using content specific to STAT 540.

  * seminar 00 | [R, RStudio Set Up & Basics](http://www.stat.ubc.ca/~jenny/STAT545A/block00_setup.html), borrowed from STAT 545A.
  * seminar 01 Wed Jan 08 <a id="seminar01"></a>
    - [Basics of R/RStudio, workspaces, and projects](http://www.stat.ubc.ca/~jenny/STAT545A/block01_basicsWorkspaceWorkingDirProject.html), borrowed from STAT 545A.
    - [Basic care and feeding of data in R](http://www.stat.ubc.ca/~jenny/STAT545A/block02_careFeedingData.html), borrowed from STAT 545A.
    - [R objects (beyond data.frames) and indexing](http://www.stat.ubc.ca/~jenny/STAT545A/block03_basicObjects.html), borrowed from STAT 545A.
    - [Explore a small gene expression dataset](seminars/seminar01_basic-data-exploration.html)
    - [Prep work for later use of Git, GitHub, Rpubs, etc.](seminars/seminar90_getting-started.html)
  * seminar 02 Wed Jan 15 Pick (at least) one tutorial to work through. The latter two options get into control flow, writing functions, and base R graphics, which might be overwhelming for novices. <a id="seminar02"></a>
    - Gentlest, written by Jenny: [Play with probability distributions and simulations](seminars/seminar02_playing-with-probability.html)
    - More advanced, revision by Gloria: [Introduction To Simulation](seminars/seminar02_probability-simulation-gloria.html)
    - More advanced, original 2013 version by Andy: [Introduction To Simulation](seminars/seminar02_probability-simulation-andy.html)
  * seminar 03 Wed Jan 22 <a id="seminar03"></a>
    - Introduction to `knitr`, R markdown, and git(hub) (SJ) | [slides as PDF](pvt/seminar03_rmarkdown-and-github.pdf)
    - [The R graphics landscape](http://www.stat.ubc.ca/~jenny/STAT545A/block90_baseLatticeGgplot2.html), borrowed from STAT 545A.
    - [Exploration of `lattice` graphics](seminars/seminar03_graphics-lattice.html) (LL)
    - __NEW!__ [Exploration of `ggplot2` graphics](seminars/seminar03_graphics-ggplot2.html) (LL)
    - __Optional__ [Using colors in R](http://www.stat.ubc.ca/~jenny/STAT545A/block14_colors.html), read only if you're curious.
    - __Optional__ [Writing figures to file](http://www.stat.ubc.ca/~jenny/STAT545A/topic12_writeFigureToFile.html), you'll eventually need this but it's not wildly urgent.
  * seminar 04 Wed Jan 29 <a id="seminar04"></a>
    - [Two group testing and data aggregation](seminars/seminar04_compileNotebook-dataAggregation-twoGroupComparison.html)
    - [Data aggregation](http://www.stat.ubc.ca/~jenny/STAT545A/block04_dataAggregation.html), borrowed from STAT 545A. Certain sections are linked to from the seminar.
  * seminar 05 Wed Feb 05 <a id="seminar05"></a>
    - [Fitting and interpretting linear models (low volume)](seminars/seminar05_lowVolumeLinearModelling.html)
  * seminar 06 Wed Feb 12 <a id="seminar06"></a>
    - [Fitting and interpretting linear models (high volume), limma package](seminars/seminar06_highVolumeLinearModelling.html)
  * seminar 07 Wed Feb 26  RNA-Seq analysis <a id="seminar07"></a>
    - *optional material* [Getting read counts](seminars/seminar07_RNA-seq-bam.html)
    - [Using read counts for differential expression analysis](seminars/seminar07_RNA-seq.html)
  * seminar 08 Wed Mar 05 Methylation analysis <a id="seminar08"></a>
    - [Methylation analysis](seminars/seminar08_methylation.html)
  * seminar 09 Wed Mar 12 <a id="seminar09"></a>
    - [Clustering and PCA](seminars/seminar09_clustering-pca.html)
  * seminar 10 Wed Mar 19 <a id="seminar10"></a>
    - [Supervised learning, cross validation, variable selection](seminars/seminar10_classification.html)
