# Data Science Environment using Conda

This is the Conda virtual environment for the projects in http://pythonforengineers.com/data-science-lessons/.

I recommend you use this environment, as it will contain the exact same versions of libraries I'm using, avoiding the version hell, or *Works on my machine* syndrome.

To start off, install  Anaconda for Python 3. This is what I recommend: https://www.continuum.io/downloads

There is a miniconda version for those short of space, but I haven't tried it.


**Next:**

Download the environment.yml file in this directory.

Next, open a command prompt. On Windows, make sure you use the the one provided by Conda. If you go to the 

Start menu->All programs - > Anaconda -> Anaconda Command Prompt

and run that.

On Linux, Conda just works in normal bash, last time I tried.

**Create Environment**

    conda env create -f environment.yml

**Activate the new environment**:

    Linux, OS X: source activate data
    
    Windows: activate data

For details, see here: http://conda.pydata.org/docs/using/envs.html

Now, when you run python or ipython notebook, it will use the *data* environment's version of Python.

Once you have created the conda environment, the 2nd time around, you don't need to run activate again, as (at least on Windows) Anaconda creates a shortcut to your environment. See the highlighted parts below, Anaconda has created short cuts to the Data environment:

![](https://raw.githubusercontent.com/shantnu/Data-Science-Conda-Env/master/conda.png)
