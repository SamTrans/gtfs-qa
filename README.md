# gtfs-qa

Methods for inspecting [SamTrans GTFS data](http://www.samtrans.com/developer.html). 
For more GTFS resources checkout this [awesome-transit](https://github.com/CUTR-at-USF/awesome-transit) collection.


## Quick start

[Binder](https://mybinder.org) is an awesome tool that runs code notebooks live from anywhere. 
Click on the snazzy button to launch this repo with binder:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/SamTrans/gtfs-qa/master)


## Local development

Git clone this repo, or got clone your fork of this repo.

Create a virtual environmemnt and install python requirements. 
**We'll use Python2 for now because of [google/transitfeed](https://github.com/google/transitfeed).**
```
cd gtfs-qa
virtualenv -p python2 venv
source venv/bin/activate
pip install -r requirements.txt
```

Start a notebook server.
```
jupyter notebook
```

Visit http://localhost:8888

Make and save changes. Git add, commit, push. 
