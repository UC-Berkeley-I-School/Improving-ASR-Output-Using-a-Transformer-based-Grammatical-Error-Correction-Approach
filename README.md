# Improving-ASR-Output-Using-a-Transformer-based-Grammatical-Error-Correction-Approach

**DATASCI 266 Natural Language Processing with Deep Learning Final Project**
*Group*: Rachel Gao, Juliana Gómez-Consuegra, Erica Nakabayashi  
*Emails*: rachelgao, julianagc, ericanaka @berkeley.edu

## Abstract
In this work, we introduce a transformer-based encoder-only grammatical error correction approach for improving automatic speech recognition by utilizing both a grammatical acceptability classifier (GAC) and a grammatical error correction model (GEC). We investigate different strategies for optimizing the models and show that using raw data to train our GAC model generates better outputs than using cleaned and augmented data. We also find that the model which punctuates and proper-cases the input data by means of Named Entity Recognition (NER) yields better results than other GEC models, leading to reduced over-correction. Considering phonetics also improved model performance, and the performance differs between gender and emotions. 

## Code
The code support for this project is at the linked Google Drive below. Please email the authors to gain read access to the shared drive if you have trouble accessing it.

[Shared Drive](https://drive.google.com/drive/folders/1-kUZBCnI3WtDwBriTz3rT6J5hDK5yE8p?usp=drive_link)

Please find below instructions on how to navigate our project files.

### Files and Folders

Throughout our project, we had three major milestones reflected on respective folder:
- [Data Gathering, Exploring, and Cleaning,](https://drive.google.com/drive/folders/1Ubs6s__tiLIwQOW41rcEsamPDV_YyEMn?usp=drive_link)
- [Modeling Grammatical Acceptability Classifier](https://drive.google.com/drive/folders/18bjvA4QLd8mLmIr3iHop2ieJGjTAD84J?usp=drive_link),
- [Modeling Gramatical Error Corrector](https://drive.google.com/drive/folders/1XfpGsZ3cklmOQDSP6LnW4ffJTkAHhaW0?usp=drive_link).

#### Data
Please find on [Data](https://drive.google.com/drive/folders/1Ubs6s__tiLIwQOW41rcEsamPDV_YyEMn?usp=drive_link) all [raw data gathered](https://drive.google.com/drive/folders/1fL5ADWogLhiNWLtahW1WAEg9k7KDc7Qw?usp=drive_link),  [data cleaning notebooks](https://drive.google.com/drive/folders/1jYS1-q7DfvvYWmQmvqGsv5XGuvG_Io6x?usp=drive_link) and explorations related to the original data, and base[cleaned data](https://drive.google.com/drive/folders/11a-bo5yQkhjoLo0C1ySn96rP1lzQmUqt?usp=drive_link) ready for use in both of our models. Also in this root folder, it is possible to find all our experimentation data related to our [GEC's  models](https://drive.google.com/drive/folders/1nQ24aFa9c4RcuN7mQl0yQf-kPJFb0n6o?usp=drive_link) for analytical evaluation purposes.

#### Grammatical_Acceptability_Classifier

Please find on [Grammatical Acceptability Classifier Folder](https://drive.google.com/drive/folders/18bjvA4QLd8mLmIr3iHop2ieJGjTAD84J?usp=drive_link) our [Experiments](https://drive.google.com/drive/folders/11TgCINEzNaurDiPb_D5bcQ3wAH3ChEwY?usp=drive_link%29) notebooks, a [comparison sheet](https://docs.google.com/spreadsheets/d/1JfALr1jY1kalv8c3G5QNa9EKgkTfOwYBEgaC6_QWX-A/edit?usp=drive_link) and the [Final](https://drive.google.com/drive/folders/1Xjqt5AuSXhPgX9XIwK4anCtk2BvC6bVO?usp=drive_link) model.

#### Grammatical_Error_Correction

Please find on [Grammatical Error Correction](https://drive.google.com/drive/folders/1XfpGsZ3cklmOQDSP6LnW4ffJTkAHhaW0?usp=drive_link) different approaches on GEC models architectures. 
As described on our paper, we used five different processes. In each folder please find the given model architecture with different thresholds, k-beams, and other parameters as it applies.

[0.SimpleGEC](https://drive.google.com/drive/folders/1EVi_l_XUT1XOmAc8TJg5N3948zDbzjvn?usp=drive_link)
[1.FineTuneGEC](https://drive.google.com/drive/folders/18c688ofGc_4T8uAXxNifk74fdrft9i-N?usp=drive_link)
[2.Dynamic GEC](https://drive.google.com/drive/folders/1I5kfjErLwA6x6VPxJDeqe_pdKWGwta4a?usp=drive_link)
[3.PhoneticGEC](https://drive.google.com/drive/folders/16H3caQUppu5rabBYEUP4869IAeSf9LHR?usp=drive_link)
[4.RawGEC](https://drive.google.com/drive/folders/1icSbDSgRiBQzSDuwX-P8KdYMsv9jvxXe?usp=drive_link)
[5.TwoGramRawGEC](https://drive.google.com/drive/folders/12dP7U9wVU3kYMTTA3q7FGaJIjIiuEXnQ?usp=drive_link)

At this root folder, you can also find:
- Spreadsheet with metrics on 50 sentences of out reduced set to get a glimpse of all fine tunning attempts.
- [Evaluation](https://drive.google.com/drive/folders/1un-pDGHmBXDDILLKNQi1IUcrzLP41KkG?usp=drive_link)  notebooks on all reduced training data for all final models.
- Tryouts to different functions and functionalities, with folders name's starting with "TO_".

#### References

[Here](https://drive.google.com/drive/folders/1qkn7eClRiC-jk1_eFmAqbGifs3g2RNuL?usp=drive_link) you can find all references used on our paper.

# Paper

Please find it [Here](https://drive.google.com/file/d/1VtADkBkai54WzTz2LJmuF_kQJGn423FS/view?usp=drive_link)  the final project report.
Also, previous deliverables can be found [here](https://drive.google.com/drive/folders/16pl4T7XwFJVBoaZR1k40xJ-LXOe4vPer?usp=drive_link).
