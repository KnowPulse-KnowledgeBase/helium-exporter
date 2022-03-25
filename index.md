---
layout: lesson
root: .
# Overall title for the Lesson.
# This should be in the form of a question if possible.
title: "How to use KnowPulse Helium Exporter to downnload pedigree and categorical data and for visualization using Helium Pediree Visualization Framework"

# Single Sentence purpose for this lesson.
short-purpose: "This lesson will show you how to export raw phenotypic data and germplasm for visualization using Helium Pedigree Visualization Framework."

# Single-Sentence describing the researchers
# who will be helped by this tutorial.
who: "Pulse Crop Researchers focused on variation data."

# A comma-separated list of maintainers for this lesson.
maintainers: "Ruobin Liu and Reynold Tan"

# A short paragraph describing why we created this lesson.
# What question is it trying to solve and why is that question important.
why: "This lesson is aiming to guide our pulse crop researchers use the Helium Data Exporter and setup Helium Pedigree Visulization Framework.Helium Pedigree Visualization Framework can be used for visualization of large-scale plant pedigrees and overlay categorical, numerical or quantitative data. This visualization tool will help improve breeders ability to predict and visualize the inheritance of genes to make better decisions."

# A short list of items researchers will learn in this lesson.
learn:
- "How to export raw phenotypic data and germplasm usinng Helium Data Exporter"
- "How to download and install Heliumm Pedigree Visulaization Framework in your computer"
- "How to load and visualize your pedigree and categorical data into Helium Pedigree Visualization Framework"

# data-description: 
- "Raw phenotypic data"
- "Germplasm data"

The KnowPulse KnowledgeBase focuses on short question-based lessons to help researchers get their work done.

- **Purpose:** {{ page.short-purpose }}
- **Who:** {{ page.who }}
- **Maintainer(s):** {{ page.maintainers }}

{{ page.why }}

<strong>Some of the things you will learn include:</strong>
<ul>
	{% for item in page.learn %}
	<li style="font-weight:bold">{{ item|markdownify }}</li>
	{% endfor %}
</ul>

> ## Getting Started
>
> The KnowPulse KnowledgeBase lessons are hands-on, so participants are
> encouraged to use their own computers to ensure the proper setup of tools
> for an efficient workflow. To most effectively use these materials,
> please make sure to download the data and install everything before
> working through this lesson.
>
> This workshop assumes no prior experience with the tools covered in the
> workshop.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
{: .prereq}


> ## Data
>
> {{ page.data-description }}
{: .prereq}
