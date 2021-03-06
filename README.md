# Fonts-Classification

Deep Learning | DS201

UIT | 2020

## About

* This is a college course project involving the use of deep learning architectures to solve the problem of image-based font classification.
* Techniques applied:
> * Data collection and Data Processing for image classification task.
> * Models: LeNet and AlexNet.
> * Model Deployment.

## Data source

* See details: <a href="https://github.com/hanhdthds/Fonts-Classification/tree/main/Data" target="_blank">Data</a>
## Some Details 

* Task
> * `Input`: an image having character.
> * `Output`: font family of that character. 
<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/e31625830504711d2154f7def0ee3c4378954eb9/Image_Font_Project/Input_output.PNG" ></p>
<p align="center"><i>Fig. 1. Input and Output.</i></p>

* Approachs
> * Experiment with three types of fonts: Old School, Handwritten-Fancy and Horror-Fancy.
> * The task is approached to solve in two approaches: simultaneously approaching numerous characters (all Latin alphabet, 5 characters: A, B, C, D, E, F) and approaching each character individually with 5 types of characters A, B, C, D, E.


* Dataset
> * Data collection: Data is collected from various sources and extracted with different methods. Below is some images depicting the processes applied in data extraction.
>> `White background`
>> <p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/1771d085a61b49caa3d56015f85edd2bd0f38ad6/Image_Font_Project/Detect_white_background.png" width="700"></p>
<p align="center"><i>Fig. 2.Extract data from an image with a white background.</i></p>

>> `Simple background`
<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/1771d085a61b49caa3d56015f85edd2bd0f38ad6/Image_Font_Project/Detect_simple_background.png" width="700"></p>
<p align="center"><i>Fig. 3.Extract data from an image with a simple background.</i></p>

>> `Complicated background`
<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/1771d085a61b49caa3d56015f85edd2bd0f38ad6/Image_Font_Project/Detect_complicated_background.png" width="700"></p>
<p align="center"><i>Fig. 4.Extract data from an image with a complicated background.</i></p>

> * Dataset: 
>> `Dataset 1`: Images of all Latin characters (including lowercase and uppercase).
<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/7a13a385f9bdd34709a2e37a0d697e20c0700477/Image_Font_Project/DATASET1.PNG" width="700"></p>
<p align="center"><i>Fig. 5.Detailed information about dataset 1.</i></p>

>> `Dataset 2`: Images are classified into 5 separate character types (A, B, C, D, E), serving to approach each character independently.
<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/8f7480be3190c877271e9b3155fd8d2924d64b12/Image_Font_Project/DATASET2.PNG" width="700"></p>
<p align="center"><i>Fig. 6.Detailed information about dataset 2.</i></p>

>> `Dataset 3`: Images of 5 characters A, B, C, D, E for the approach of numerous characters.
<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/c7257a4e71d3126d3796b315db7a44b38542ff95/Image_Font_Project/DATASET3.PNG" width="700"></p>
<p align="center"><i>Fig. 7.Detailed information about dataset 3.</i></p>

* Results

<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/47b4dd951d483b2291756df62442438c0067123a/Image_Font_Project/Result.PNG" width="700" ></p>
<p align="center"><i>Fig. 8.Experimental results.</i></p>

* Deploy
<p align="center"><img src="https://github.com/hanhdthds/Fonts-Classification/blob/da43dc363a9a34e68d99b760495006efe234cac5/Image_Font_Project/deloyyy.png" width="700" ></p>
<p align="center"><i>Fig. 9.Experimental results.</i></p>

## Code

* All codes are in this repo are implemented in Google Colab.
* See code for character extraction with white background here: '<a href="https://github.com/hanhdthds/Fonts-Classification/blob/02785f293b2dd5dcb7ab833ea14347f7a04703e0/Extract_characters_dafont.ipynb" target="_blank">Extract_characters_dafont.ipynb</a>'.
* See code about the baseline training process here: '<a href="https://github.com/hanhdthds/Fonts-Classification/blob/02785f293b2dd5dcb7ab833ea14347f7a04703e0/base_line.ipynb" target="_blank">base_line.ipynb</a>'.

## Report

* This is detailed in attached report: <a href="https://github.com/hanhdthds/Fonts-Classification/blob/main/FONT_report.pdf" target="_blank">Report</a>

## References

* All references are cited in the report file.
