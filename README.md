# Concrete Crack Images for Classification
## Description
The dataset contains concrete images having cracks. The data is collected from various METU Campus Buildings.
The dataset is divided into two as negative and positive crack images for image classification. 
Each class has 20000images with a total of 40000 images with 227 x 227 pixels with RGB channels. 
The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). 
High-resolution images have variance in terms of surface finish and illumination conditions. 
No data augmentation in terms of random rotation or flipping is applied. 

## Challenges and the solutions
1) If you utilise Google CoLab, it will take a long time to transfer the dataset into Google Dive because the dataset are so big.
2) The other way from upload the file into goggle colab if you are google colab user without waiting a long time to upload into google drive.
   Make a folder using the Google Colab's left size. After creating a folder, run the following code:-
   
       a) !wget https://prod-dcd-datasets-cache-zipfiles.s3.eu-west-1.amazonaws.com/5y9wdsg2zt-2.zip
       
       b) !mkdir dataset
       
       c) !unzip "5y9wdsg2zt-2.zip" 
       
       d) !unrar -e "Concrete Crack Images for Classification.rar" 
       
4) The other way from google colab you also can use visual studio code and upload the file into your own pc, it will not take a long time to unzip and upload the file.
5) The first training and the last training will both take a considerable amount of time, thus I advise Google Colab users to switch the hardware accelerator to a GPU with a TPU GPU type. They should also adjust the epoch to a small number.

## The installation and how to run the project 

### Steps for installation

##### There are various methods to download the code of github on your system:-

Clone repository

1) Go to that particular repository
2) Click on the download icon
3) Copy the repo link(you can also copy this from page URL)
4) go to your terminal and type git clone <link> 

Download Zip

1) Go to repository
2) Again click on download icon
3) Click on download zip
4) Now your Zip will be downloaded , unzip and use it.

Get raw code

If you don't want the whole repository, or want to use only one or two files ,

1) Go to that file
2) Click on Raw and you will see the page with raw code ,
3) At this point you can download that page, or you can also copy the code.
4) To download the page simply run wget <pageUrl> 

### Steps for running the project 
Here are the steps to compile and run a GitHub project:

1) Clone the repository: Use the "git clone" command in a terminal/command prompt to download the project files to your local machine.
2) Navigate to the project directory: Use the "cd" command to navigate to the directory where the project files are located.
3) Install dependencies: If the project requires any external libraries, install them using the package manager specified in the project's documentation (e.g., pip, npm, etc.).
4) Compile the project: Depending on the language and framework used, compile the project using a build tool (e.g., make, gradle, etc.) or by executing a script provided in the project files.
5) Run the project: Execute the compiled binary or run the script to launch the project.

## Output of the project
##### Training process using Tensorboard
  
![Training process plotted using Tensorboard](https://github.com/firasamirah/YPAI03-Assessment3/assets/91971387/daaefb57-e698-4fd2-ae42-b6df80b6f5bb)

## Credits
https://data.mendeley.com/datasets/5y9wdsg2zt/2
