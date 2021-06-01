# AUTOSAR - Specification of Secure Hardware Extensions

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yxh1126/secure-hardware-extensions/HEAD?filepath=script)

This project provide a Jupyter Notebooks based Python3 script to illustrate the steps of computing the M1, M2, and M3 messages as defined in the AUTOSAR SHE Specification for the Key Update Protocol in a ECU CAN network. 

The slides in the project is a introduction of the AUTOSAR - Specification of Secure Hardware Extensions document.

The docs folder also include other documents helps to complete the Key Update Protocol script.

## Prerequisites

#### Installing Python

Make sure that you have [Python installed](https://realpython.com/installing-python/) on your machine.

You might want to use [venv](https://docs.python.org/3/library/venv.html) standard Python library
to create virtual environments and have Python, `pip` and all dependent packages to be installed and 
served from the local project directory to avoid messing with system wide packages and their 
versions.

#### Installing Dependencies

Install all dependencies that are required for the project by running:

```bash
pip install -r requirements.txt
```

#### Launching Jupyter Locally

All demos in the project may be run directly in your browser without installing Jupyter locally. But if you want to launch [Jupyter Notebook](http://jupyter.org/) locally you may do it by running the following command from the root folder of the project:

```bash
jupyter notebook
```
After this Jupyter Notebook will be accessible by `http://localhost:8888`.

#### Launching Jupyter Remotely

In case if you want to _change_ the code and _experiment_ with demo notebook you need to launch the notebook in [Binder](https://mybinder.org/). You may do it by simply clicking the binder badge below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yxh1126/secure-hardware-extensions/HEAD?filepath=script)
