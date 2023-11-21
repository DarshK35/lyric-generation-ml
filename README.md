# Lyric Generation using Machine Learning
Natural Language Processing Project created by:  
Darsh Kumar  
Jiya Bansal  
Swathi Baiju  

## Requirements
### Hardware
CPU: AMD Ryzen 7 5000 series or Intel Equivalent  
GPU: Nvidia RTX3060 or AMD Equivalent  
GPU VRAM: At least 6 GB  
RAM: At least 16 GB  

### Software
#### Python Libraries
* `numpy`
* `pandas`
* `pickle`
* `seaborn`
* `matplotlib`
* `wordcloud`
* `tensorflow`
* `keras`
* `gensim`
* `langdetect`
* `sentence_transformers`
* `scikit-learn`
* `jupyter`

#### Other Software
* Visual Studio Code
* Jupyter
* Nvidia CUDA 12.2
* Nvidia CUDNN 8.7

**It is recommended to run this code on Linux operating system since Windows version of TensorFlow lacks GPU acceleration and requires WSL2 to enable it.**  
**WSL rapidly increases the CPU and RAM resource comsumption.**  

## Testing System Specifications
The code in this repository was tested on a system with the following specifications:

CPU: AMD Ryzen 9 5900HX
GPU: Nvidia RTX3060 Mobile
GPU VRAM: 6GB
RAM: 16 GB
Operating System: Manjaro Linux
Linux Kernel Version: 6.5.11
Nvidia Driver version: 535.129.03

## Running The Code
To run the repository, simply open the file `CodeTesting.ipynb` in Jupyter or Visual Studio Code. Visual Studio Code will require extensions to display and run `.ipynb` files.  

The required python libraries can be installed by passing the following command in the terminal:
```bash
pip install numpy pandas pickle seaborn matplotlib wordcloud tensorflow[and-cuda] keras gensim langdetect sentence_transformers scikit-learn jupyter
```

Then you can run the code from the code cells.