# FIJI script for automated cellular network timelapse analyses
Code for automated network feature extraction for in vitro and in silico angiogenesis-like network formation timelapses used for the following publications:
> https://www.biorxiv.org/content/10.1101/2024.08.06.606790v2.full


# Code design
There are two code files in this project: "InVitro.ijm" and "InSilico.ijm" to analyze _in vitro_ timelapses or computational model output images respectively. Both are designed to automatically select subfolders in a given directory and analyze all network timelapses embedded in those folders. For the _in vitro_ timelapses, the tool will go through all (sub)folders 

# Getting started
1.  Download the example timelapse or model output in a folder you will be able to locate easily
2.  Open the code in FIJI or ImageJ, preferably a recent version
3.  Turn off Batch mode, "setBatchMode(true)", so you can see what is happening
4.  Turn on "save_overview=true" to appreciate the output image
5.  Turn on "testmode"=true" to activate all checkpoints
6.  Run the code
7.  You will be asked to select a directory which contains your timelapse(s)
8.  You will be asked to select a folder to store the output data
9.  Because of testmode, the code will pauze after every step. Differences in FIJI versions or settings can cause the segmentation to fail. If any of the checkpoints fail, change the code according to the suggestion and run it again.   
