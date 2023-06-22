# Climate Change Prediction Repository

This repository contains a Flask application, a nice interface for a climate change prediction tool which you can run locally on your computer.

To run this project on your laptop please follow the instructions provided below:
1. Install dependencies (git, python, pip) - find tutorial on internet if you don't know how to

2. Clone project to you PC.
```
https://github.com/osanan25/ClimateChangePrediction
```

3. Open project folder
```
cd ClimateChangePrediction
```

4. Open terminal in the project directory and run command
```
python -m venv venv
```
or
```
python3 -m venv venv
```
depending on how you installed python

6. Activate venv with command
- windows: 
```
venv\Scripts\activate
```

- mac and linux:
```
source venv/bin/activate
```

7. Install pip-compile tool
```
pip install pip-tools
```

8. Create dependencies file
```
pip-compile --output-file=requirements.txt requirements.in
```

9. Install all dependencies with command:
```
pip3 install -r requirements.txt
```

10. In neotebook choose venv you created before as kernal

11. WHen you run any cell first time IDE will ask you if you want to install Jupyter - agree and proceed

12. After Jupyter installation you can start work with notebook


### Research
Lateset research ML you can find in file training_models.ipynb
