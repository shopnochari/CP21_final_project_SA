
# Audio Dispersion with FFT

This is the final project on my class Computational Physics (Fall 2021). I am interested to do a simple task. Using FFT seperate the audio frequencies from audio data . My goal is to clean out noisy audio data using FFT. I am going to take some audio data using the phyphox app. More about phyphox could be found here [PhyPhox](http://phyphox.org). 


## Project Structure

This project is focused on audio dispersion. There are 4 key parts for this project which are : a) Waves b) Fourier Transfor c) Phyphox and d)Example (in Jupyter noteboke) .
The codes are under the following license  *http://www.apache.org/licenses/*
More about waves can be found here at * https://openstax.org/books/university-physics-volume-1/pages/16-introduction *. 
The examples and codes regarding FFT can be found here at * https://pythonnumericalmethods.berkeley.edu/notebooks/chapter24.03-Fast-Fourier-Transform.html *.
The project is written on jupyter notebook in this repository. I have used the docer image * ubsuny/cp1-hw8 * to tun this jupyter notebook. 
There is also a YouTube video *link here*.

To read about and follow my project I suggest reading the documentation including all references. 




## Setup

The following commands get you started:

Firt , I  Cloned the ripository into local computer with the following command :

git clone "link to  the repository" 

The from inside the repository I have run my docker image.

Running docker image in terminal : 
 
docker run --rm -v ${PWD}:/results -p 8888:8888 ubsuny/cp1-hw8:latest

This will provide a link for opening the juphyter notebook in browser. Just copy the link and paste it in web browser and it will open the jupyter notebook. 


Converting to pdf :

fromt the terminal I have used the following command to get the pdf file:

pandoc audio_disperson.ipynb -o audio_dispersion.pdf   

It will convert the ipynb file to pdf .


## Participation

If you want to participate feel free open an issue with the appropiate labels and/or fork my project and create a pull request against the *dev* branch.



References : 

a)https://openstax.org/books/university-physics-volume-1/pages/16-introduction
b)https://phyphox.org