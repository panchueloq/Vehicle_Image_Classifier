# 1. Description
This is my first ML solo project after a series of courses and tutorials that started in April 2022. It included various iterations of searching and cleaning data, trying out different model architectures, modifying them in different ways, and keeping a log of everything. 
<br/>
<br/>
After months of working with models that worked flawlessly, as they were embedded in some course or tutorial, this was the perfect way to get my hands dirty and dive into the whole process. From finding and handling the raw data to making small hyperparameter tweaks, it gave me great understanding of the impact every small decision has over outcome. 
<br/>
<br/>
Some of the challenges I encountered were: overfitting, not powerful enough models, GPU memory restrictions, bad data, little amounts of data, more data stuff, and the list goes on. But with every challenge came a lesson and a solution. There was regularization, data augmentation, different approaches to transfer learning, hours of eyeing the samples one by one and cleaning the data, etc. (I actually got a 10% performance increase from that last one at some point!)
<br/>
<br/>
Now I intend to continue the learning process with this model and take it to the next level which would be deployment. 

# 2. Steps to download and use the classifier
### 2.1 Downloading the data
- go to: https://drive.google.com/drive/folders/1aNwsdVzy_M9aVNQUZXCRXa_WA7I7AiZ3
- download and paste all three data folders into the classifier's directory
- download the models folder into the classifier's directory to load trained model

### 2.2 Creating a virtual environment
In the terminal:
- Create Virtual Environment
    - python3 -m venv vehicle_class
- Activate Virtual Environment
    - source vehicle_class/bin/activate (Linux)
    - vehicle_class\Scripts\activate.bat
- Attach to Jupyter
    - pip install ipykernel
    - deactivate (to install kernel outside venv)
    - python3 -m ipykernel install --name=vehicle_class --user
- Check Jupyter Kernels
    - jupyter kernelspec list

Make sure you are using the vehicle_class kernel in Jupyter Notebooks.