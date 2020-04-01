# zeppelinTo

Python Client to Convert a Zeppelin Notebook into: Python or Jupyter Notebook fies


## Installation Instructions (virtualenv)

### Install pip & virtualenv

`pip3 install virtualenv`

### Grab a copy of the github project  

`git clone https://github.com/stvoutsin/zeppelinTo.py.git`

### Initialize a virtual environment in the project directory

`virtualenv --python=/usr/bin/python3 zeppelinTo/`

### Activate the virtualenv 

`cd zeppelinTo/`
`source bin/activate`


### Install ZeppelinTo using pip 

`pip3 install zeppelinTo/`

## Run Python and import ZeppelinTo

`bin/python3.4` 

..

`from zeppelinTo import ZeppelinTo`
ZeppelinTo.convert_to_python("data/sample-notebook.json")
ZeppelinTo.convert_to_jupyter("data/sample-notebook.json")

..
