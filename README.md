# Cancer Data Repository
> This repository contains data of cancer patients, intended to be used for analysis of diagnosis and outcome trends by demographic group. 
>
# What is in this repository?
#### The repository contains two `.csv` files under the ["data"](https://github.com/melcotsa/Cancer-Data--Demographic-Analysis/tree/main/data) folder: 
1. The raw cancer data sourced from the [Cancer Data Aggregator](https://cda.readthedocs.io/en/latest/interactive/) found via the [Cancer Research Data Commons](https://datacommons.cancer.gov/cancer-research-data-commons)
2. A subset of the data that only includes the sex of the patients and their primary diagnosis site. 
#### Additionally, the repository contains 2 instructional documents in the ["instructions"](https://github.com/melcotsa/Cancer-Data--Demographic-Analysis/tree/main/instructions) folder:
1. A Python notebook detailing how to create the aforementioned data subset from the raw data using Python3.
2. A document detailing how to create the data visualization/graph found later in this README file.
---
# Purpose
#### What can this data be used for?
- This data is a resource for scientists, or anyone, who is interested in cancer research and who wants to investigate cancer trends by demographic groups.
#### What might this data, and its analysis, show us?
- The data subset will outline the most common diagnoses of cancer patients by sex, which will allow scientists to see what cancers either sex is at higher risk for. This information can be incredibly useful for doctors and cancer advocates' preventative health measures. An example of how the data might be manipulated and used can be found in the following section.
---
# Data Visualization
- The following graph was constructed in Excel using the data subset in the "data" folder.
- On the x-axis, the reported areas of the primary diagnosis sites are listed. On the y-axis, the number of cases occurring in that diagnosis site is given.
*Note: This particular graph excludes primary diagnosis sites that are sex-dependent (e.g. ovary, prostate gland, cervix, etc.).*
<img width="652" alt="image" src="https://github.com/user-attachments/assets/1da97359-3030-4b4d-b813-88122350d181">

#### Why is this data visualization relevant?
- The graph allows for easier comparison between the frequencies of cancer diagnosis sites in females and males. For example, it reveals that, in this set of patient data, males developed cancer in their kidneys at a much higher rate than females. 
- Using information about comparative frequencies of cancer diagnosis sites, cancer researchers could do a couple of things:
> 1. Conduct studies to find out why there are sex disparities in rates of cancer in specific parts of the body. Doctors and researchers could attempt to develop ways to mitigate the factors that lead females or males to have such high incidence rates in those areas.
>
> 2. Implement new standard screening procedures. For example if, after further analysis of patient data, researchers conclude that males are at significantly higher risk for kidney cancer, they may suggest new screening guidelines for kidney cancer with the hopes of catching the cancer in an earlier stage, thereby increasing the likelihood of successful treatment and management of the disease.
>
---
## Acknowledgments
This repository was created for Prof. Gotzler's English-105-75 class at UNC-CH, as a project for our unit on writing in the Natural Sciences.

## Licensing
This repository and the files found within it are open for public use under the Creative Commons Zero (CC0) License. 
