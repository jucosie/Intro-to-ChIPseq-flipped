# Workshop Schedule

> **NOTE:** The *Basic Data Skills* [Introduction to the command-line interface](https://hbctraining.github.io/Intro-to-shell-flipped/schedule/) workshop is a prerequisite.


## Pre-reading:

* Please **study the contents** and **work through all the exercises** within the following lessons:
  * [Shell basics review](https://hbctraining.github.io/Intro-to-rnaseq-hpc-salmon-flipped/lessons/shell_review.html)
  * [Best Practices in Research Data Management (RDM)](https://hbctraining.github.io/Intro-to-rnaseq-hpc-salmon-flipped/lessons/04a_data_organization.html)
  
  
## Day 1

| Time |  Topic  | Instructor |
|:-----------:|:----------:|:--------:|
| 09:30 - 09:45 | [Workshop Introduction]() | Meeta |
| 09:45 - 11:00 | [Introduction to ChIP-seq]() | [Dr. Shannan Ho Sui]() |
| 11:00- 11:05 | Break|  |
| 11:05 - 11:50 | [Working in an HPC environment](https://hbctraining.github.io/Intro-to-rnaseq-hpc-salmon-flipped/lessons/03_working_on_HPC.html) | Radhika |
| 11:50 - 12:00 | Overview of self-learning materials and homework submission | Jihe |

### Before the next class:

1. Please **study the contents** and **work through all the code** within the following lessons:
  * [Experimental design considerations and understanding the ChIP-seq workflow]()
  * [Dataset overview and project organization]()
  * [Quality Control of Sequence Data: Running FASTQC and evaluating results]()
  * [Alignment using Bowtie2]()

    > **NOTE:** To run through the code above, you will need to be **logged into O2** and **working on a compute node** (i.e. your command prompt should have the word `compute` in it).
    > 1. Log in using `ssh rc_trainingXX@o2.hms.harvard.edu` and enter your password (replace the "XX" in the username with the number you were assigned in class). 
    > 2. Once you are on the login node, use `srun --pty -p interactive -t 0-2:30 --mem 1G /bin/bash` to get on a compute node or as specified in the lesson.
    > 3. Proceed only once your command prompt has the word `compute` in it.
    > 4. If you log out between lessons (using the `exit` command twice), please follow points 1. and 2. above to log back in and get on a compute node when you restart with the self learning.

2. **Complete the exercises**:
   * Each lesson above contain exercises; please go through each of them.
   * **Copy over** your code from the exercises into a text file. 
   * **Upload the saved text file** to [Dropbox]() the **day before the next class**.

### Questions?
* ***If you get stuck due to an error*** while runnning code in the lesson, [email us](mailto:hbctraining@hsph.harvard.edu) 
* Post any **conceptual questions** that you would like to have **reviewed in class** [here](https://PollEv.com/hbctraining945).

## Day 2

| Time |  Topic  | Instructor |
|:-----------:|:----------:|:--------:|
| 09:30 - 10:15 | Self-learning lessons review |  |
| 10:15 - 11:00 | [Filtering BAM files]() |  |
| 11:00- 11:05 | Break|  |
| 11:05 - 12:00 | [Peak calling]() |  |

### Before the next class:

1. Please **study the contents** and **work through all the code** within the following lessons:

 * [Handling peak files using `bedtools`]()
 * [Creating bigWig files]()
 * [Visualization of signal profiles using deepTools]()

2. **Complete the exercises**:
   * Each lesson above contain exercises; please go through each of them.
   * **Copy over** your code from the exercises into a text file. 
   * **Upload the saved text file** to [Dropbox]() the **day before the next class**.
   
### Questions?
* ***If you get stuck due to an error*** while runnning code in the lesson, [email us](mailto:hbctraining@hsph.harvard.edu) 
* Post any **conceptual questions** that you would like to have **reviewed in class** [here](https://PollEv.com/hbctraining945).

***

## Day 3

| Time |  Topic  | Instructor |
|:-----------:|:----------:|:--------:|
| 09:30 - 10:00 | Self-learning lessons review | All |
| 10:00 - 10:45 | [Troubleshooting your ChIP-seq analysis]() | |
| 10:45- 10:50 | Break|  |
| 10:50 - 11:50 | [Automating the ChIP-seq workflow]() | |
| 11:50 - 12:00 | Wrap-up |  |



* Downloadable Answer Keys (Day 2 exercises): 
  * ...

* Downloadable Answer Keys (Day 3 exercises): 
  * ...

* [Automation Script])

***

## Resources

***

## Building on this workshop

***
*These materials have been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*