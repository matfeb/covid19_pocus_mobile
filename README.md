# **Automatic Detection of COVID-19 for POCUS on Mobile Device**

## Summary

### News
WORK IN PROGRESS.
This repo is a fork of https://github.com/jannisborn/covid19_ultrasound which contains the code for the paper `Accelerating Detection of Lung Pathologies with Explainable Ultrasound Image Analysis`.


### Goal
This is an ongoing ultrasound data collection initiative for COVID-19. Please help growing the [database](https://github.com/jannisborn/covid19_ultrasound/data/README.md).

### Dataset
Feel free to use (and cite) the paper dataset. They currently have >200 LUS videos. For details see [https://github.com/jannisborn/covid19_ultrasound/data/README.md](https://github.com/jannisborn/covid19_ultrasound/data/README.md).
Please note: The founders/authors of the repository take no responsibility or liability for the data contributed to this archive. The contributing sites have to ensure that the collection and use of the data fulfills all applicable legal and ethical requirements.

## Contribution
Work in progress

### Motivation:
From the ML community, ultrasound has gained much less attention than CT and X-Ray in the context of COVID-19.
But many voices from the medical community have advocated for a more prominent role of ultrasound in the current pandemic.

### Summary
We developed methods for the automatic detection of **COVID-19** 
from **Lung Ultrasound** (LUS) recordings. Our results show that one can accurately distinguish LUS samples from COVID-19 patients from healthy controls and bacterial pneumonia. Our model is validated on an external dataset (ICLUS) where we achieve promising performance. The CAMs of the model were validated in a blinded study by US experts and found to highlight relevant pulmonary biomarkers.
Using model uncertainty techniques, we can further boost model performance and find samples which are likely to be incorrectly classified.
Our dataset complements the current data collection initiaves that only focus
on CT or X-Ray data. 

#### Evidence for ultrasound
From https://github.com/jannisborn/covid19_ultrasound
> Ultrasound is **non-invasive**, **cheap**, **portable** (bedside execution),
**repeatable** and **available in almost all medical facilities**. But even for
trained doctors detecting patterns of COVID-19 from ultrasound data is challenging and
time-consuming. Since their time is scarce, there is an urgent need to simplify,
fasten & automatize the detection of COVID-19.
  
## Installation 

### Ultrasound data
Find all details on the current state of the database in the [data](https://github.com/jannisborn/covid19_ultrasound/data)
folder.

### Deep learning model (`pocovidmobile`)


## Contact 
- If you experience problems with the code, please open an
[issue](https://github.com/matfeb/covid19_pocus_mobile/issues).
- If you have questions about the project, please reach out: `mathieu.febvay@eric.univ-lyon2.fr`.

# Citation

Please use the following bibtex entries:
```bib

```
