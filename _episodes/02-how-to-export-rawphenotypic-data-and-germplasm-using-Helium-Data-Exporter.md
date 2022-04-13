---
title: "How to export rawphenotypic data and germplasm using Helium Data Exporter"
teaching: 10
exercises: 10
questions:
- "How to download both pedigree and categorical data through the use of Helium Data Exporter?"

objectives:
- "Providing a step by step demonstration on how to download a pedigree file and a caregorical file from an experiment of interest from KnowPulse. "
keypoints:
- "Log in KnowPulse with your user account before download your data."
- "You can only download pedigree and categorical data from your registered experiment."
- "You need to always load in the pedigree file first, then the categorical file to overlay the information." 
---
## How to select an experiment, germplasm, and trait

Pedigree and categorical data from your registered experiment(s) can be downloaded from [Helium Exporter module](https://knowpulse.usask.ca/helium-exporter)(requires log in to access).


1. Select an experiment of your interest from the **Experiment** selector. (You have to be the user of an experiment before you can access any data under it, talk to us if you have permission issue).
 
2. The next field is the **Germplasm/lines selector with search functionality**.  From here, on your left hand side, checkboxes allow you to choose the desired germplasm. Germplasm field supports inline search for a specific germplasm. In the below screenshot, for example, there are 50 germplasms available and we are insterested in the 27 of them. On your right hand side, in the field control, you can either use **Search** to look up for a specific germplasm from the field, or click on **All** to select the full dataset. 


3. Followed by the germplasm section is the the **Trait/categorical data selector with search functionality**. Again, on your left hand side, there is a trait search field supports inline search for the traits of interest. On your right hand side, in the field control, you can either use **Search** to look up for a specific trait from the field, or click on **All** to select all the available traits.

4. Below the **Trait**, there is an additional filter called **Parental Relationships Only**. Click on it means you to choose to view only the maternal and parental relationships of the germplasm, therefore, only male and female parents of a line are returned. 

5. Finally, click on the **Download** button to sumbit your request. 

![Screenshot of main code listing](../fig/helium-exporter-11.png)

## How to download your pedigree and categorical data

Helium from there will return two files for you. One is for pedigree data, the other is for categorical data. The exporter may take a few seconds to generate the files for you. Those two files can be saved onto your local computer, followed by load to Helium for visualization.

![Screenshot of main code listing](../fig/helium-exporter-3.png)


## Load your data into Helium Exporter

1. Open the Helium Exporter from your local computer. 

2. First, we want to upload the pedigree file from your local computer into Helium Exporter from the Overview Panel for visualization.
![Screenshot of main code listing](../fig/helium-exporter-5.png)
 Pedigree file allows you to view pedigree relationship between germplasm in Main Pedigree Visualization Panel.
[Missing demo screenshot]

3. Then, let us repeat the same step with categorical file to load in the traits.
![Screenshot of main code listing](../fig/helium-exporter-6.png)


