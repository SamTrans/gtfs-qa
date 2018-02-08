# gtfs-qa

Methods for inspecting [SamTrans GTFS data](http://www.samtrans.com/developer.html). 
For more GTFS resources checkout this [awesome-transit](https://github.com/CUTR-at-USF/awesome-transit) collection.


## Quick start

[Binder](https://mybinder.org) is an convenient tool that runs code notebooks live from anywhere. 

Click here to launch this repo:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/SamTrans/gtfs-qa/master)


## Project structure

`data/` contains all the GTFS related data.

`notebooks/` contains Python [Jupyter](https://jupyter.org/) notebooks for data exploration.

`tools/` is intended to house refined code from the notebooks that could be run 
either via the CLI, or imported for reuse in other notebooks. 


## Local development

Git clone this repo, or git clone your fork of this repo.

Create a virtual environmemnt and install python requirements. 
*We'll use Python2 for now because of [google/transitfeed](https://github.com/google/transitfeed).*
```
cd gtfs-qa
virtualenv -p python2 venv
source venv/bin/activate  # Or source venv/Scripts/activate 
pip install -r requirements.txt
```

Start a notebook server.
```
jupyter notebook
```

Visit http://localhost:8888

Make and save changes. Git add, commit, push. 
