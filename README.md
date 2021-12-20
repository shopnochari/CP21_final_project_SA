
# Audio Dispersion with FFT

This is the final project on my class Computational Physics (Fall 2021). I am interested to do a simple task. Using FFT to cleanout audio data by denoising lower frequencies from the signal. I am going to take some audio data using the phyphox app. More about phyphox could be found here [PhyPhox](http://phyphox.org). The audio data will be imported into a jupyter notebook where I can use FFT to perform the task. 


## Project Structure

This project is focused on audio dispersion. There are 4 key parts for this project which are : a) Waves b) Fourier Transfor c) Phyphox and d)Example (in Jupyter noteboke).\
The codes are under the following license  * [apache 2.0](http://www.apache.org/licenses/) * .\ 
The examples and codes regarding FFT can be found here at * [FFT](https://pythonnumericalmethods.berkeley.edu/notebooks/chapter24.03-Fast-Fourier-Transform.html ) *.\
The project is written on jupyter notebook in this repository. I have used the docker image * [UBSUNY](docker pull ubsuny/cp1-hw8) * to run the jupyter notebook. \
There is also a YouTube video * www.youtube.com/sayeedsust *.

To read about and follow my project I suggest reading the documentation including all references. 

## Setup

The project is completed in github repository using docker image mentioned above. 

Firt , I  Cloned the repository into local computer with the following command :

 * git clone https://github.com/ubsuny/CP1_FinalProjectTemplate *\

The from inside the repository I have run the  docker image.

the command used for running  docker image in terminal : 
 
* docker run --rm -v ${PWD}:/results -p 8888:8888 ubsuny/cp1-hw8:latest *\

This will provide a link for opening the juphyter notebook in browser. Just copy the link and paste it in web browser and it will open the jupyter notebook.\

After completing the  notebook, I have used the following git commands to publish the notebook and related data to the repository:\

* git add <file names> *\

* git commit -m "Commit messaged" *\

* git push * \

Finaly, the juoytor notebook file (.ipynb) is converted to pdf. from the terminal I have used the following command to get the converted pdf file:\

 * pandoc file_name.ipynb -o file_name.pdf  *\
 
It will convert the ipynb file to pdf .


## Participation

If you want to participate feel free open an issue with the appropiate labels and/or fork my project and create a pull request against the *dev* branch.



References : 

a) https://openstax.org/books/university-physics-volume-1/pages/16-introduction
b) https://phyphox.org
c) https://pythonnumericalmethods.berkeley.edu/notebooks/chapter24.03-Fast-Fourier-Transform.html
d) https://towardsdatascience.com/understanding-audio-data-fourier-transform-fft-spectrogram-and-speech-recognition-a4072d228520
e)https://pandas.pydata.org/docs/index.html