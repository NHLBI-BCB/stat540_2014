% Final project for STAT540

## Assignment

### General principles

Identify a biological question of interest and a relevant dataset. Develop and apply a statistical approach that allows you to use the dataset to answer the question.

We assume the biological question and data fall in the general area of high-throughput, large-scale biological investigations targetted by the course. Beyond that it is wide open: methylation, SNPs, miRNAs, CNVs, RNA-Seq, CHiP-Seq, gene networks, ... it's fair game. Avoid a dataset that doesn't have any/much *quantitative* data, i.e. contains only sequence or discrete data.

Note that _definitive_ answers are not necessarily expected.  Rather, aim to provide a critical appraisal of the data, the analytical approach, and the results. You will have to handle the competing pressures to "get it right" and "get it done". Shortcomings of the data, misfits between the data or the biological question and the statistical model, etc. are inevitable. Your goal is to identify such issues and discuss them critically, without becoming paralyzed. Demonstrate understanding of the statistical concepts and methods that are the foundation of your analytical approach.

We assume the analytical and computing task will have a substantial statistical component, probably enacted via R.  So beware of a major analytical or computational undertaking that is, nonetheless, _not_
statistical (example: constructing a database). Creating useful data visualizations can be absolutely vital and is arguably statistical, but your analysis should go beyond merely creating pretty pictures (but please do include some!). Key concepts, at least _some_ of which should come up in your analysis:

  * the (hypothesized, probably artificial) data-generating model

  * background variation, variance, signal to noise ratio, estimates and their associated standard error

  * relationship between biological factors and experimental factors, apparent relative importance in terms of "explaining" observed data

  * attention to large-scale inference, e.g. control of family-wise error rate or false discovery rate

### Group makeup

Groups should have 4 to 6 members. We strongly encourage that groups be diverse in terms of backgrounds. In practice, this probably means the students should registered in a mix of programs/departments. All groups and group projects must be approved by the instructors ahead of time.

### Initial deliverables

  * List of group members. In addition to names, include relevant info on grad program, lab, interests/expertise. We may organize submission via the Google Group or may ask each group to initialize their website, GitHub repository or whatever.

  * Initial project proposal describing basic idea of project. Think: a paragraph.

  * Final proposal that provides information on the goals and division of labour. Think: a page or less.

### Final deliverables

  * A poster, to be hosted and exhibited in our poster session on Wed Apr 09 from 9:30 am to 12 pm in Room 101, aka the multi-purpose room, on ground floor of the [Michael Smith Building](http://www.maps.ubc.ca/PROD/index_detail.php?locat1=083). Group-level deliverable. NOTE: you will secure your material to standard conference-type poster boards with push pins.

  * A digital supplement, to be made available to the TAs/instructors, at the very least.  This should contain the materials (or associated live links) an instructor would need to evaluate your work and that a group member would need to reproduce/reuse/extend the work. Group-level deliverable. The path of least resistance is to use a GitHub repository. Email the TAs with the location of the digital supplement (or open an issue and tag them). Content should include (but is not limited to!):

	  - a PDF of the poster
	  - important files, such as "inputs" (e.g. the dataset(s) you analyzed) and "outputs" (e.g. plain text files of your key statistical results or PDFs of your main figures); if you started with a publicly available file, you can link to it; if you started with private data, please do your best to describe 
    - the R code for the analysis, i.e. the thing that turns the inputs into outputs; can be pure R scripts or R Markdown; as you've probably learned, compiling R or R Markdown source to Markdown and committing is very helpful for the *consumer*
    - a link-y version of your bibliography (for example, live Pubmed or DOI links)
    - a big picture overview of the analysis; [this flow chart](https://github.com/sjackman/stat540-project) is one nice way to present this, but a good `README.md` can also do the job

  * A short individual report (1 - 2 pages max!) that covers:

    - _Concise_ summary of main role / contribution of each group member.
    - More detailed description and reflections on your specific role / contribution.
    - Observations about the group dynamic.  E.g. if someone really went above and beyond (or did not pull their own weight), state that, while striving to be fair, factual, and constructive.
    - Scientific reflections.  E.g., what worked well / poorly? what seems worth following up vs. a dead end? what was most difficult or most rewarding?
    - Submit this via your private GitHub repository, the one you used for homework. Create a new directory called `project` and, within it, store your report as `README.md`. Open an issue and tag the TAs as you did for homework submission.
    
  * Thoughtful assessment of three other posters, using a rubric.  Individual deliverable. To be completed in real time at the poster session.

## 2014 Dates 

Fri Jan 24 | Report project group membership.

Fri Jan 31 | Initial project proposals due = a paragraph.

Fri Feb 14 | Feedback to groups re: initial project proposals. Each group will be assigned an instructor or TA + instructor pair for extra support. This is available [here](../pvt/ProjectGroups.html) (*note: you will be prompted for the usual username and password*).

Wed Mar 05 | Final project proposals due = a page.

Wed Mar 26 and Wed Apr 02 | No formal computing seminar. Use time to work with your group, get help from TAs or instructors.

Wed Apr 09 | Poster session 9:30am - 12:00pm in Michael Smith Labs Room 101.

Fri Apr 11 | All the digital group and individual stuff due.

## Evaluation

Project mark worth 40% of course mark. The 40 points break out like so:

  * 20 points: Overall mark, i.e. all group members get same mark. Clarity of the problem statement, data description, and the analytical approach.  Suitability of the methodology, quality of the execution. Quality of presentation. Based on poster and digital supplement.
  * 5 points: Group formation on time, initial project proposal, final project proposal.
  * 5 points: Quality and impact of student's specific contribution to the project. Judged via individual reports (the self-report and that of fellow group members) and the primary deliverables (poster and digital supplement).
  * 5 points: Student's engagement with the group and insight into the scientific question.  Judged via individual reports.
  * 5 points: Thoughtful evaluation of other groups' projects. Judged via submission of completed evaluation forms.

Each student will mark posters of 3 other groups. TAs and instructors will mark all posters. Rubric and marking sheet: [PDF](poster-marking-sheet-rubric.pdf).

Jenny's post mortem notes from 2012. [PDF](jennyPostMortem2012.pdf)

## Student work from past runs of course

January - April 2014 posters

  1. Comparative Analysis of Cancer Cell Lines with RUNX and NOTCH1 Inactivation/Inhibition/Knockdown. Chen Di Gravio Jamieson-Lane Kucuk Mancarci Salehi. *permission to post PDF pending*
  2. Caregiver contact time and sex effects on methylation status in infants. Baik de Goede Erdelyi Gladish Islam Pilsworth. [PDF](previousStudentWork/2014-04/poster_caregiving-sex-methylation.pdf)
  3. Using RNA-Seq data to predict large-scale copy-number alterations in AML.  Bayly Chong Docking Dorri Hindalong Johnston. [PDF](previousStudentWork/2014-04/poster_rnaseq-acute-myeloid-leukemia.pdf) | [github](https://github.com/rdocking/stat540-group-project-aml-cnv)
  4. Comprehensive Methylome Analysis of Breast Cancer Cell Lines. Acton Attali Ezzat Zadeh Hor Lorzadeh Mingay. [PDF](previousStudentWork/2014-04/poster_breast-cancer-cell-lines-methylome.pdf)
  5. Metagenomic analysis of differential gene abundance across ocean, soil, and oil sands. Chu Durno Hammett Ievdokymenko Lever Nguyen. [PDF](previousStudentWork/2014-04/poster_ocean-soil-oil-sands-metagenomics.pdf)
  6. Gene expression profiling in Parkinson's Disease and Alzheimer's Disease. Gao Lubieniecki Ma Wang Zhang Zhu. [PDF](previousStudentWork/2014-04/poster_alzheimers-parkinsons.pdf)
  7. An exploration of DNA methylation in Stem vs. Somatic cells, and how it relates to gene expression. Brown Cen Hofmann Lee Lim. [PDF](previousStudentWork/2014-04/poster_stem-vs-somatic-methylation.pdf) | [github](https://github.com/scottdbrown/stat540-tissueSpecificMethylation)
  8. Expression Profiling in Inflammatory Bowel Disease. AlOmeir Sun Wafa Zhang. [PDF](previousStudentWork/2014-04/poster_expression-profiling-ibd.pdf) | [github](https://github.com/omaromeir/stat540-2014-project  )

January - April 2013 posters

  * Analysis of Gene Expression Omnibus Leukaemia Data from the Illumina HumanMethylation450 Array. 
Alice Zhu, Rachel Edgar, Shaun Jackman and Nick Fishbane. [PDF](previousStudentWork/2013-04/poster_methylationLeukemia.pdf), [digital supplement](http://sites.google.com/site/stat540diffmethleuk/), [github](https://github.com/sjackman/stat540-project)
  * DNA methylation changes in human neural tube defects. Michelle Cui, Sarah Goodman, Alexandre Lussier, Sam Peeters, Magda Price, Gina Zhong. [PDF](previousStudentWork/2013-04/poster_methylationNeuralTubeDefects.pdf)
  * THE ROLE OF CYSTEINE CATHEPSINS IN PANCREATIC CANCER. Shauna Crowley, Darlene Liying Dai, Marjan Farahbod and Nikolaus Fortelny. [PDF](previousStudentWork/2013-04/poster_proteomicsCathepsinsPancreaticCancer.pdf)
  * Normalization and Differential Expression Analysis Method Comparison: Identifying Differentially Expressed Genes in _Saccharomyces cerevisiae_. Adriana Sedeno, Celia Siu, Mayumi Iwashita, Wendy Xu, Wenqiang Shi. [PDF](previousStudentWork/2013-04/poster_yeastNutrientLimitatDEA.pdf), *digital supplement no longer available 2014-01-15* 
  * Exploring the Metastasis Process in Prostate Cancer using Interaction Networks. Raunak Shrestha, Josh Brown, Melissa Lee, Dorji Pelzom and Jake Yeung. [PDF](previousStudentWork/2013-04/poster_prostateCancerNetworkDEA.pdf), [github](https://github.com/jakeyeung/cancer-metastasis)
  * metaanalysis of topoisomerase data in yeast. Nicolas Coutin, Alex Cumberworth, Matthew Dahabieh, Yumian Hu, Govinda Sharma. [PDF](previousStudentWork/2013-04/poster_yeastTopoisomerase.pdf)



January - April 2012 posters

* Gene Expression In Peripheral Blood Can Discriminate Early From Dual Responses In Asthmatic Individuals Undergoing Allergen Inhalation Challenge. Fan S.Y., Firme M., Kwok W., Singh A. [PDF](previousStudentWork/2012-04/poster_asthma.pdf)

* Effects of Mutations in Histone Modifying Enzymes on Gene Expression
Profiles in Non‐Hodgkin Lymphoma. Alex Hammel, Andrew Wong, James
Proudfoot, Julia Pon. [PDF](previousStudentWork/2012-04/poster_lymphoma.pdf)

* Technical Variability on the Illumina HumanMethylation450
  Platform. Chris Kay, Ellyce Eddy, Ruiwei Jiang, Michelle
  Xia. [PDF](previousStudentWork/2012-04/poster_methylation.pdf)

* Gene expression evolution between ranges in an invasive weed. Turner
K, Tian A , Zoubarev A, Ch’ng C , Hodgins
KA. [PDF](previousStudentWork/2012-04/poster_ragweed.pdf)

* Developmental Expression Pattern of SET Domain Genes. Daryanaz
  Dargahi, Tyler Funnell, Calvin Lefebvre, Shing Hei
  Zhan. [PDF](previousStudentWork/2012-04/poster_SETdomain.pdf)
