# Simple Automatic Speech Recognition
The aim of the project is to build a simple automatic speech recogintion model that can correctly classify the simple voice commands ```["up", "down" ,"left" , "right"]```


# Data Source:
<a href="https://www.kaggle.com/code/zakikurdya/commands-recognition-with-tensorflow/data">Kaggle Commands Recognition</a>



# Startup the project

The initial setup.

Create virtualenv and install the project:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv ~/venv ; source ~/venv/bin/activate ;\
    pip install pip -U; pip install -r requirements.txt
```

Unittest test:
```bash
make clean install test
```

Check for simple_ASR in github.com/{username}.
If your project is not set please add it:

- Create a new project on `github.com/{username}/simple_ASR`
- Then populate it:

```bash
##   e.g. if username is "{group}" and project_name is "simple_ASR"
git remote add origin git@github.com:{username}/simple_ASR.git
git push -u origin master
git push -u origin --tags
```

Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
simple_ASR-run
```

# Install

Go to `https://github.com/lee-noidas/simple_ASR` to see the project, manage issues,
setup you ssh public key, ...

Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:lee-onidas/simple_ASR.git
cd simple_ASR
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
simple_ASR-run
```
