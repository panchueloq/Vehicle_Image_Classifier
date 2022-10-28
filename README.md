# 1. Description

# 2. Steps to download and use the classifier
### 2.1 Downloading the data
- go to: https://drive.google.com/drive/folders/1aNwsdVzy_M9aVNQUZXCRXa_WA7I7AiZ3
- download and paste all three folders into the classifier's directory

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