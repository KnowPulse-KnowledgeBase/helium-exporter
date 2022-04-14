---
title: "How to export rawphenotypic data and germplasm using Helium Data Exporter"
teaching: 10
exercises: 10
questions:
- "How to select an experiment and it's subsequent datails from Helium Data Exporter?"
- "How to download both pedigree and categorical data from Helium Data Exporter?"


objectives:
- "Providing a step by step guide showing users how to download a pedigree file and a categorical file from an experiment of interest from KnowPulse."
keypoints:
- "Login KnowPulse with your user account before downloading any data."
- "You can only download experimental data from your registered experiment."
---
## Select an experiment, germplasm, and trait

Pedigree and categorical data from your registered experiment(s) can be downloaded from [Helium Exporter module](https://knowpulse.usask.ca/helium-exporter)(requires login to access).


1. Select an experiment of your interest from the **Experiment** selector. (You have to be the user of an experiment before you can access any data under it, talk to us if you have any permission issue).
 
2. Then choose the germplasm of your interest from **Germplasm/lines selector with search functionality**.  From here, on your left hand side, checkboxes allow you to choose the desired germplasm. Germplasm field supports an inline search for specific germplasm. In the below screenshot, for example, there are 50 germplasms available and we are insterested in 27 of them. On your right hand side, in the field control, you can either use **Search** to look up for specific germplasm from the field, or click on **All** to select the full dataset. 


3. Followed by the germplasm section is the **Trait/categorical data selector with search functionality**. Again, on your left hand side, there is a trait search field that supports inline search for any traits of interest. On your right hand side, in the field control, you can either use **Search** to look up a specific trait from the field, or click on **All** to select all the available traits.

4. Below the **Trait**, there is an additional filter called **Parental Relationships Only**. Click on it allows you to choose only the maternal and parental relationships of the germplasm, therefore, only male and female parents of a line are returned. 

5. Finally, click on the **Download** button to submit your request. 

![Screenshot of main code listing](../fig/helium-exporter-11.png)

## Download your pedigree and categorical data

Helium from there will return you two tab-separated-value files, with the extension name of .helium. One is for pedigree data, the other is for categorical data. It may take the exporter a few seconds to generate the files for you. Those two files can be saved onto your local computer, followed by loaded to Helium for visualization. We will talk more visualization details in the next episode.

![Screenshot of main code listing](../fig/helium-exporter-3.png)


