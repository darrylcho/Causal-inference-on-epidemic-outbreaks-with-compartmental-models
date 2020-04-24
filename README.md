# Causal inference of the policy Strategy on the epidemic outbreaks  


## Authors 

[Qingtao Cao](https://www.researchgate.net/profile/Qingtao_Cao), [Junyao Wang
](https://towardsdatascience.com)

## Abstract
The epidemic of 2019 Novel Coronavirus is spreading very fast around the world. Without the useful antivirial drugs and the vaccines to repond the cov-19, the soical distanceing is a main approach to slower the spread of covid-19 becuase this disease spreads primarily from person to person. As an authoriative policy, social-distaning is applied in many different communities. According to own situation, each community begins to employ the social-distancing policy at differnt time point and applys it with different strength. The following analysis focuses on the causal effect of the three inventions, incudling the density of the community, the policy power and the moment when the policy begin to be applied, on the peak number of the infected case. First of all, we build a SIR model based on a pyhiscal-contact based network, and then run the model with the Gillespie algorithm. The Gillespie algorithm can be also descirbed as a directed acycile graph. Based on this directed acycle graph, the causal effect of above three interventions on the peak number can be quantified by two methods. One is the tranditional mathematical analysis by solving the ordinary differential equaiton and then condtion on the equation in the peak time. The other one is the observation/data analysis. In the absence of available data, we simulates the epidemic spread in our SIR model, and then use the outcome of the simulation to check the causal effect of each intervention and build a nerual netowrk prediciton model. Our results can compare the causal effect of two different policy strategies, inculding how and when applied it. What's more, we do a conterfactual analysis with the given peak number and the moment of policy being applied: if the poplicy is appled eailer, what the change is.

[See video abstract](https://www.youtube.com/watch?v=o3GfnEjTdIQ)

## How to explore this project

In this section, you will explain to other people how to navigate your project.

I am going to use this section to explain how to set up your project directory.

Put your project in the appropriate project directory. Create a subdirectory for your project and give it a clear name that reflects specific elements of your project.  It should not conflict with other group's names, obviously.  For example, some students who analyzed Airbnb data analyzed Bay Area real estate, while others analyzed Austin TX.  So good subdirectory names would be "airbnb model bay area" and "airbnb model austin".

Set up your project directory as you see fit.  The two most important things are **presentation** and **reproducibility**.

### Presentation

Presentation means you have done your best to make it easy for future students to understand and learn from your work.  A bad presentation is having many badly named notebooks with lots of code, and little text explanation.  NEU students will be penalized for poor presentation.

Presentation also means clean code.  **Python code must adhere to [flake8](http://flake8.pycqa.org/en/latest/index.html#quickstart)**, even if the code is inside Jupyter notebooks.  R code should follow R conventions.  I suggest the [tidyverse style guide](https://style.tidyverse.org/).

**Avoid unneccesary code and output in notebooks**.  If loading a package in your R notebook causes a bunch of warnings and messages to be printed, turn message printing and warning printing off in that block of code.  Don't import libraries in your Jupyter notebook if you are not going to use them.  Don't have `!pip install ...` lines, just tell us what to install.  Don't have long-run on lines

### Reproducibility

**Reproducibility** means that someone can easily clone this repo and reproduce your work.  Ideally, you should have notebooks (R Notebook or Jupyter notebooks) that you can be run directly.

* Make it clear what libraries need to be installed.
* You can put data, figures, code, slides, and other files in their own directories.  If you do, explain them in your version of this README.md.
* If you want to get fancy, you can [wrap your analysis in an R package](https://www.r-bloggers.com/creating-an-analysis-as-a-package-and-vignette/), or a Python library, or use the [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/).  But this is purely a matter of personal preference. 

Other notes:
* Above, there is a link to a video abstract.  You **must** create a **short** video summary of your work.  No more than 5 minutes.
* Use links in the author's section to link you your own websites, Linkedin, online portfolios,
