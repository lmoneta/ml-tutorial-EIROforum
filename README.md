# Deep Learning Tutorial at the 6th EIROforum school on Instrumentation


This repository contains the Jupyter notebooks for the hands-on tutorial for the Artificial Intelligence session at the 6th EIROforum school on Instrumentation.

See the [agenda page](https://indico.cern.ch/event/777129/timetable/#20190516.detailed)



## Opening the Jupyter notebooks

The notebooks can be opened and run on SWAN ( swan.cern.ch ), the CERN Jupyter notebook service using your personal CERN account (for CERN users) or using the temporary accounts provided for the course.

The notebooks can also be used directly on your computer, if you have all the needed software installed, Python, Jupyter and the machine learning software stack (Kara's, sci kit-learn and tensor flow).


### How to open the Jupiter notebooks in SWAN

Here we provide the step by step instructions on how to start working in SWAN. 


*   Click on the following link

[![SWAN](http://swanserver.web.cern.ch/swanserver/images/badge_swan_white_150.png)](https://cern.ch/swanserver/cgi-bin/go?projurl=https://github.com/lmoneta/ml-tutorial-EIROforum)

*  When starting SWAN a page appear to configure the environment. It is recommended to select the the **95a Python3** software stack.
For the other configuration parameters you can use the default values.

*  Click on  `Start my Session` at the button of the page. 

   *  Starting the session might take some time, especially if many users are doing it at the same time. 
   *  In case you observe an error when staring the session, it is likely that your CERNBox account has been not activated. In this case you should get a message: *Do you have CERNBOx account? If not click [here](https://cernbox.cern.ch)* By clicking on the provided link, you will be directed to [CERNbox]((https://cernbox.cern.ch) and by doing this your CERNBox account will be automatically validated.
   *  After having validated CERNBox you can click again on `Start my Session`. You might need to logout and login again if case an error occours.
   
*  When a SWAN session is started you will be in the `My Project` page. Click on the ``+`` button (*Add  new Project*) located at the top right

*  Enter the URL for the notebook GitHub repository (the link is also available in the Indigo agenda page)

```
https://github.com/lmoneta/ml-tutorial-EIROforum
```

*  Open the SWAN Project ``ml-tutorial-EIROforum``.

Now the notebook will be visible in your SWAN project area and you can start using them, by clicking on the file names. 

### How to download notebooks in your computer

Here we provide instructions on how to download the notebook directly from GitHub in your computer. 


*  Open a Terminal 
*  Clone the GitHub  repository 
```
git clone  https://github.com/lmoneta/ml-tutorial-EIROforum
```
* The notebooks will be in the directory *ml-tutorial-Europium*. Go to this directory
* Run the Jupyter notebook service by doing from the terminal
```jupyter notebook``
* A browser window will appear and the notebooks will be visible there and you can open by clicking on them 


Note that you can also just download the notebook repository directly in SWAN from the SWAN terminal Window. By doing this the ``ml-tutorial-EIROforum`` will be visible in the Cernbox area accessible from SWAN. 

## SWAN and Jupyter notebooks quick start ##

Once you have access to the notebooks, after having open them, you can run interactively the code. The notebooks are capable of running code in a wide range of languages. However in this tutorial we will use the Python language. 

Here you can find a quick start information on what are the Jupyter notebooks and how to running code. 

* [What is a jupyter notebook?](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/What%20is%20the%20Jupyter%20Notebook.ipynb)
* [Notebook Basics](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb)
* [Running Code](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Running%20Code.ipynb).

For information on using SWAN, see the SWAN website: https://swan.web.cern.ch

In a nutshell, "SWAN (Service for Web based Analysis) is a platform to perform interactive data analysis in the cloud". It gives you access to a coherent software stacks for data analysis used at CERN (e.g. ROOT software framework, various scientific Python software packages, etc..) and to a storage facility (CERNBOX). 


* You need to have an active **CERNBOX** to use swan (https://cernbox.cern.ch/). If you don't have a CERN account, please use the temporary accounts provided to you. 
In that case you need to sign a form and we will provide you the credential for the SWAN account. 

