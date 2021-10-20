---
---

[Cloud-SPAN](https://cloud-span.york.ac.uk) is a project run by the Biology Department of the University of York with the aim to develop advanced modules covering specialised knowledge and skills to generate and analyse 'omics data using cloud-based High Performance Computing (HPC) resources.

This course is based on the Data Carpentry's [Genomics Workshop](https://datacarpentry.org/genomics-workshop/), streamlined and extended to serve as the foundation course for the Cloud SPAN advanced modules. [Data Carpentry](https://datacarpentry.org/)’s aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain.

The course teaches data management and analysis for genomics research including: (1) best practices for organization of bioinformatics projects and data, (2) use of command-line utilities to connect to and use cloud computing and storage resources, (3) use of command-line tools for data preparation, (4) use of command-line tools to analyze sequence quality and perform and automate variant calling.

The course is designed to be taught over four half days of instruction.

> ## Frequently Asked Questions
> Read our [FAQ](https://cloud-span.github.io/genomics01-intro/faq/index.html) to learn more about the Cloud SPAN advanced modules and scholarships for individuals from underrepresented groups that might otherwise be unable to participate in training including funds to cover childcare required to undertake self-paced learning.
{: .callout}

> ## Getting Started
>
> This course assumes that learners have no prior experience with the tools covered in the course.
> However, learners are expected to have some familiarity with biological concepts, including the
> concept of genomic variation within a population. Participants should bring their own laptops and plan to participate actively.
>
> To get started, follow the directions in the [Setup](setup) tab to get access to the required
> software and data for this workshop.
{: .prereq}

> ## Data
>
> This course uses data from a long term evolution experiment published in 2016: [Tempo and mode of genome evolution in a 50,000-generation experiment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/) by Tenaillon O, Barrick JE, Ribeck N, Deatherage DE, Blanchard JL, Dasgupta A, Wu GC, Wielgoss S, Cruveiller S, Médigue C, Schneider D, and Lenski RE. (doi: 10.1038/nature18959)
>
> All of the data used in this workshop can be [downloaded from Figshare](https://figshare.com/articles/Data_Carpentry_Genomics_beta_2_0/7726454).
> More information about this data is available on the [Data page](https://datacarpentry.org/organization-genomics/data/).
{: .prereq}

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [Project management for cloud genomics](https://cloud-span.github.io/genomics02-proj-mngt-cloud-genomics/) | Learn how to structure your data and metadata, plan for an NGS project, log onto a cloud instance and start navigating using the command line.|
| [Using the command line](https://cloud-span.github.io/genomics03-using-the-command-line/)    | Learn to use the command line to navigate your file system, create, copy, move and remove files and directories, and search within your files.|
| [Data preparation and organisation](https://cloud-span.github.io/genomics04-data-preparation-organisation/) | Learn how to automate commonly used workflows, organise your file system for a new project, and use command-line tools to perform quality control.|
| [Data processing and analysis](https://cloud-span.github.io/genomics05-data-processing-analysis) | Learn how to filter out poor quality data, align reads to a reference genome, identify and visualize between-sample variation, and automate these tasks for efficiency and accuracy.|

# Teaching Platform

This workshop is designed to be run on pre-imaged Amazon Web Services (AWS) instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI). To access your AMI instance remotely, follow the directions in the [Setup](setup).
