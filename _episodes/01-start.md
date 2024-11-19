---
title: "Overview"
teaching: 20
exercises: 0
questions:
objectives:
- "Topics and technologies used during this workshop"
keypoints:
- "This part of the lesson will mostly be given in the form of a lecture"
apps:
- "Powerpoint"
---

## Target Audience and Main Aim

This two-day workshop is designed to provide participants with a fundamental understanding of the processes involved in **de novo genome assembly** using **long-read sequencing technologies**. The workshop emphasizes practical skills and hands-on experience to ensure participants can assemble and evaluate genomes.

### Target Audience

The workshop is tailored for:

- **Master’s and PhD students** or **early-career researchers** working in the **Life Sciences**, particularly in fields such as genetics, genomics, microbiology, and bioinformatics.
- Participants with prior knowledge of:
  - **Linux operating system**: Familiarity with basic command-line tools and operations is essential, as the workshop involves working directly with genomic data on Linux systems.
  - **Biological concepts**: A foundational understanding of **DNA structure, sequencing technologies, and genetic principles** will be beneficial for interpreting results and understanding the workflow.

### Scope of the Workshop
While the data provided during the workshop is derived from a **bacterial genome**, the principles and techniques covered are broadly applicable across a wide range of organisms, including:

- **Fungi**
- **Plants**
- **Mammals**

This makes the workshop suitable for anyone interested in expanding their genomic analysis skills, regardless of the specific organism they study.

### Main Aim
The workshop is built on the philosophy that **active participation** leads to deeper learning. You will:

1. **Perform hands-on genome assembly** to solidify your understanding of the steps and tools involved.
2. **Critically evaluate results** through guided discussions, enabling you to troubleshoot and refine assemblies effectively.


## Topics

This workshop covers the following key topics, focusing on the practical application of tools and methods for genome assembly and evaluation using long-read sequencing data:

### 1. **Read Quality Assessment**

Understanding the quality of your raw sequencing data is a crucial first step in any genome assembly workflow. You will:

- Use bioinformatics tools to evaluate the quality of raw reads from **PacBio** and **Nanopore** platforms.
- Learn to identify common issues such as low-quality reads and biases in sequencing.
- Understand the impact of read quality on downstream analysis and how to filter or preprocess reads for optimal assembly results.

### 2. **De Novo Assembly**

In this course, you will focus on creating genome assemblies from long-read sequencing data. You will:

- Work with **PacBio** and **Nanopore** data to produce genome assemblies.
- Explore popular tools for long-read assembly.
- Learn how the characteristics of long reads (e.g., length and error rate) influence assembly strategies and outcomes.

### 3. **Assembly Comparison**

Genome assemblies can vary significantly based on the type of sequencing data and the assembly tool used. In this course, you will:

- Compare genome assemblies generated from **PacBio** and **Nanopore** data.
- Use bioinformatics tools to evaluate differences in **contiguity**, **completeness**, and **accuracy**.
- Investigate potential discrepancies, such as gaps, misassemblies, or structural variations.

### 4. **Assembly Base Quality**

High-quality genome assemblies are critical for downstream analyses, but errors such as SNPs or indels can impact results. You will:

- Use **next-generation sequencing (NGS) data** to assess the accuracy of your assemblies at the base level.
- Identify **SNPs**, **indels**, and other discrepancies between assemblies using variant-calling tools.
- Discuss how these assembly errors can affect downstream analyses, such as gene annotation, phylogenetics, and comparative genomics.

## Google drive

To give feedback, solutions and other things you'd like to share, please use this [Google document](https://docs.google.com/document/d/10Vii37lR8TYYvJnYartqw2RxHooBfiWagJyHWOd6qXs/edit?usp=sharing).

## Presentation

[The presentation on long read technologies is also available for download.](../fig/LongReadAssembly.pptx)

{% include links.md %}
