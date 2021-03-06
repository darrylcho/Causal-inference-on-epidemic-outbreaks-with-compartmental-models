# Causal inference of the policy Strategy on the epidemic outbreaks  


## Authors 

[Qingtao Cao](https://www.researchgate.net/profile/Qingtao_Cao), [Junyao Wang
](https://towardsdatascience.com)

## Abstract
The epidemic of 2019 Novel Coronavirus is spreading very fast around the world. Without useful antiviral drugs and the vaccines to respond to the COVID-19, the social distancing is the main approach to slow the spread of COVID-19 because this disease spreads primarily from person to person. As an authoritative policy, social-distancing is applied in many different communities. According to own situation, each community begins to employ the social-distancing policy at a different time point and applies it with different strength. The following analysis focuses on the causal effect of three interventions, including the density of the community, the policy‘s strength, and the moment when the policy begins to be applied, on the peak number of the infected case. First of all, we build a SIR model based on a physical-contact based network, and then run the model with the Gillespie algorithm. The Gillespie algorithm can be also described as a directed acyclic graph. Based on this directed acyclic graph, the causal effect of the above three interventions on the peak number can be quantified by two methods. One is the traditional mathematical analysis by solving the ordinary differential equations, and then condition on equations in the peak time. The other one is the observation/data analysis. In the absence of available data, we simulate the epidemic spread in our SIR model and then use the outcome of the simulation to check the causal effect of each intervention and build a neural network prediction model. Our results can compare the causal effect of two different policy strategies, how and when applied it. What's more, we do a counterfactual analysis with the given peak number and the moment of the policy being applied: if the policy is applied earlier, what the change is.    

[See video abstract](https://www.youtube.com/watch?v=bljicHhzc64&feature=youtu.be)

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
