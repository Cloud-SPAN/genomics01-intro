---
layout: page
title: Frequently Asked Questions
---

Thank you for your interest in hosting or teaching this Cloud-SPAN workshop. Below you will find answers to some frequently asked questions about this curriculum. If the answer to your question doesn’t appear, please contact [cloud-span-project.york.ac.uk](mailto:cloud-span-project.york.ac.uk) or open an issue in one of [our Github repos]("https://github.com/Cloud-SPAN"). 

* [For Hosts](#hosts)
* [For Instructors](#instructors)

## <a id="hosts"></a> Hosts

### What does this workshop cover? 

This workshop teaches data management and analysis for genomics research including: best practices for organization of bioinformatics projects and data, use of command line utilities, use of command line tools to analyze sequence quality and perform variant calling, and connecting to and using cloud computing. 

### What experience do learners need to have before this workshop? What will they be able to do by the end of the workshop? 

This lesson assumes no prior experience with the tools covered in the workshop. However, learners are expected to have some familiarity with biological concepts, including the concept of genomic variation within a population. By the end of the workshop, learners will be able to: 

- structure their metadata, and organize and document their genomics data and bioinformatics workflow;
- navigate their file systems, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards;
- use command-line tools to perform quality control, align reads to a reference genome, and identify and visualize between-sample variation;
- work with Amazon AWS cloud computing and transfer data between their local computer and cloud resources.

### What are the software, hardware, and connectivity needs for this workshop?

Learners will need to bring a laptop (not a tablet). Learners using a Windows machine will also need to download and install Git Bash](https://gitforwindows.org). There are no other hardware or software requirements. Learners will need a stable, strong internet connection in order to work on the remote computing system used for this workshop and participate in the online video call.

### My institution has its own compute cluster, or our research group uses a different cloud computing resource. Can we deliver the workshop using that system?

This course is based on a genomics workshop developed by [The Carpentries]("https://datacarpentry.org/genomics-workshop/"). To ensure a consistent workshop experience for learners and Instructors, all workshops organized by The Carpentries (“centrally-organized workshops”) use a stable, community-tested curriculum and technical set-up. We have adapted this curriculum and setup to suit our and our users' needs. Currently, this means all our Genomics workshops are taught using Amazon Web Services, although we may be interested in supporting other systems in the future. 

If you are interested in using a different platform to teach this curriculum in a self-organized workshop, all of our materials are publicly available and licensed [CC-BY](https://creativecommons.org/licenses/by/4.0/), so are freely remixable (with credit). Find all our resources, notes and data on [our GitHub]("https://github.com/Cloud-SPAN").

### What experience do helpers need to have for this workshop?

Anyone who has some experience using the Bash shell can be an effective helper for this workshop. Helpers do not need to have experience working with genomics data or the specific command line tools taught in this workshop. 

### Where can I find more information about this workshop?
For a full description of this workshop, including what content is covered, and what dataset we use to teach, visit the [Genomics Workshop Overview](https://cloud-span.github.io/genomics01-intro/) page. 

## <a id="instructors"></a> Instructors

### What background and technological skills do I need to have to teach this workshop?

You will need experience using a bash shell (the default shell on Mac OS and most Linux systems), including writing your own small bash scripts and running programs written by others from the command line. You do not need to have specifically used the command-line programs that are used in these lessons. You do not need to have prior experience working with Amazon Web Services (AWS), but some experience logging on to remote computers would be useful. You should have experience working with genomic sequences in FASTQ format. 

### How can I prepare to teach this material? 

Each lesson has a set of Instructor Notes that provide information about the design of the lesson, commonly encountered problems, and technical tips and tricks. You can access Instructor Notes in the “Extras” menu on each individual lesson page. Instructor Notes are written collaboratively by our Instructors, so please contribute your own notes after your workshop!

### What are common problems that arise during this workshop?

The best place to get information about common problems that arise during workshops is in the Instructor Notes for each lesson. You can access Instructor Notes through the Extras menu in the top navigation bar that appears across the head of each lesson. Instructors are strongly encouraged to contribute back to the Instructor Notes based on their workshop experience. To contribute to the Instructor Notes, click the “Improve this page” menu option in the upper right corner of the Instructor Notes page. 

### Does the AWS image location matter? Do I need to set up an AMI in a different region if my workshop will be held outside of the Eastern US?

We have run this workshop in locations across the United States and Europe with no noticeable difference in instance speed. If you experience any issues, please [let us know](team@carpentries.org).
