---
layout: lesson
root: .
# Overall title for the Lesson.
# This should be in the form of a question if possible.
title: "Lesson Title"

# Single Sentence purpose for this lesson.
short-purpose: "This lesson will show you how to visualize pedigree with helium pedigree visualization application."

# Single-Sentence describing the researchers
# who will be helped by this tutorial.
who: "Pulse Crop Researchers focused on variation data."

# A comma-separated list of maintainers for this lesson.
maintainers: "Reynold Tan, Ruobin Liu"

# A short paragraph describing why we created this lesson.
# What question is it trying to solve and why is that question important.
why: "This lesson is aiming to guide our pulse crop researchers through the procedure of Helium Exporter peidgree visualizing. Helium Exporter module can be used to visualize your pedigree to guide or predict ___ growing season. "

# A short list of items researchers will learn in this lesson.
learn:
- "How to install and configure Helium Exporter"
- "How to export your data from KnowPulse"
- "How to load your data into Helium Exporter"
- "How to visualize your data"

data-description: "Phenotypic Data"
---

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
