---
title: Common Languages and Tools for Research Computing
last_modified_at: 2019-09-11
primary_reviewers: k8hertweck
---

## Getting Started

Fred Hutch offers training resources for many of the common languages and tools listed below. For more information on training opportunities, cooperative learning groups, and how to get started, please see the [reference page](/scicomputing/reference_overview/).


## [R, RStudio](/scicomputing/software_R/)

R is a programming language and also a software development environment. It is widely used among statisticians and has strong capabilities for statistical modeling and data analysis. While R's core functions are fairly small, there is a robust community of user-contributed R 'packages' (eg. see "Bioconductor" on the target reference page). You can [download](https://cran.r-project.org/) R for your computer, install it from Center IT's Self Service (on [Macs](https://centernet.fredhutch.org/cn/u/center-it/help-desk/mac-support/jamf-pro.html) or on PCs), or run R on SciComp's computing clusters using [environment modules](/scicomputing/compute_environments/).

RStudio is a graphical frontend to R that also improves upon a basic R installation, providing syntax-highlighting and code-completion, static or dynamic reports (via RMarkdown documents), and easing the creation of R packages, among other functionalities. It is considered an [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment) which functions much like a wrapper around R itself, to create a graphic user interface, and easy access to various tools and functions that enhance the user's experience of using R.  


## [Python](/scicomputing/software_python/)

Python is another language used extensively within the bioinformatic community. A very high-level comparison of Python to other commonly used languages is that it’s generally on the easier side for being able to learn and understand, but it doesn’t give you as much detailed control over the details of computation compared to C. In other words, it’s easier to use, but not quite as performant. One of the nice things about Python in recent years has been that there is a large community of software developers contributing highly efficient code as installable modules, which makes the entire codebase more valuable for your average user.


## [Managing and Sharing Code](/scicomputing/software_managecode/)

While version control software has evolved over time, a new evolution that is happening more and more is the need for a wider group of researchers to actively use version control resources to manage their code and documentation of processes that are ongoing in their research. From the perspective of reproducibility, shareability and interoperability, the need for a sharing platform that integrates version control and collaboration is becoming more and more a critical part of a researcher’s toolkit. Thus, regardless of the degree to which code plays a direct role in a research project, more and more often at least a cursory understanding of what GitHub is and how it can be utilized in scientific research is important.

## [Linux, Unix and Shell Resources](/scicomputing/software_linux101/)

Unix is the foundation for both Linux and macOS, and is the operating system that is most commonly used for developing and executing bioinformatic software tools. In order to navigate a Unix-based operating system and execute commands, it is extremely useful to use the command line interface, which is generally referred to as BASH (Bourne-Again SHell).


## Other Languages and Tools for Data Analysis

### Proprietary (Licensed) Statistics Software

We encourage the use of free, open-source software at the Hutch, especially for academic research use. For projects and researchers who prefer not to use open-source software, Fred Hutch supports proprietary software through shared licenses for the following statistical analysis and visualization software: [**SAS**](https://www.sas.com/en_us/software/stat.html), [**SPSS**](https://www.ibm.com/analytics/spss-statistics-software), [**Stata**](https://www.stata.com), and [**Matlab**](https://www.mathworks.com/products/matlab.html?s_tid=hp_products_matlab) users. Please see the [Resource Library](compdemos/matlab/) for information on accessing Matlab on Fred Hutch compute resources. For more information on obtaining access to licensed software, please contact Center IT.

There is an active [**Tableau**](https://www.tableau.com) data visualization community at Fred Hutch. For more information on help sessions, meetups, and Q&A, please see the #tableau-user-comm channel on [The Coop Communities Slack](https://fhbig.slack.com/).


### Workflow Managers

Workflow managers are software that facilitate the setup, execution, and monitoring of scientific analyses involving multiple steps. These are especially important for complex bioinformatic analyses that require various software dependencies and resource requirements, and can make your analysis both easier to troubleshoot and more reproducible. Workflow managers common for scientific processes include: [Snakemake](https://snakemake.readthedocs.io/en/stable/), [Cromwell](https://cromwell.readthedocs.io/en/stable/tutorials/FiveMinuteIntro/), [Toil](https://toil.readthedocs.io), [CWL](https://www.commonwl.org), and [Nextflow](https://www.nextflow.io/). For more information on running **Nextflow**, please see [this demo](compdemos/nextflow/).


### Other languages

The [**Julia**](https://docs.julialang.org) language aims to combine the accessible syntax of R or Python with the speed of C/C++ programs. While not currently as functional as R or Python for bioinformatic tasks, there is a growing collection of resources for [Julia for bioinformatics](http://ucidatascienceinitiative.github.io/IntroToJulia/).

**Go**, or [GoLang](https://golang.org/doc/), also has some [support for data science](https://blog.chewxy.com/2017/11/02/go-for-data-science/).

[**Perl**](https://www.perl.org) is a computational language often found in bioinformatic analyses. The language was originally developed in 1987. [perl.org](https://www.perl.org/learn.html) has numerous tutorials and modules for learning the language.