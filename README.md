# DS4002_Project2
UVA DS 4002 Spring 2024 Group 13 Project 3 Files
## Software and Platform Selection
### Software Selection
- In this project, we have decided to use R to manipulate data. This project can also be applied to Python as well.
### Additional Packages Utilized
- Pandas package was used to manipulate and create data
- keras and Tensorflow packages to create the convolutional neural network
- ggplot2 package to create plots in R
- jpeg package to display images in R

### Platform 
Both Mac and Windows machines were used during the process, project will replicable in both environments

## Map of the Documentation
#### There are 6 main files and some of them include subfolders within them 
- Root
  - DATA
    - TEST
        - NORMAL
        - PNEUMONIA
    - TRAIN
        - NORMAL
        - PNEUMONIA
    - VAL
        - NORMAL
        - PNEUMONIA
  - OUTPUT
    - dataset_distribution.jpg
    - model_val_accuracy.jpg
    - pneumonia_lung.jpg
  - SCRIPTS
    -  P3_Analysis.Rmd = master script
    -  ** no preliminary dataset cleaning was required **
  - README.md
  - LICENSE
  - References

## Reproducing Results
To replicate results of this study, first step will downloading the original dataset from the Data folder in github, X-rays
After donwloading the original dataset, next step will be running the master script, meanwhile, make sure that your train, test, val, file locations are specified within your operating system.
