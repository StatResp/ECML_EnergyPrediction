# Energy and Emission Prediction for Mixed-Vehicle Transit Fleets Using Multi-Task and Inductive Transfer Learning
This repo contains the codes used to develop the paper under the title of "Energy and Emission Prediction for Mixed-Vehicle Transit Fleets Using Multi-Taskand Inductive Transfer Learning" submitted to ECML 2021.

All code for the paper is in the form of jupyter notebooks and are in the app/ directory. Notebook descriptions:

* segments.ipynb: generates the trip segments discussed in Section 3.
* join.ipynb: joins the various data sources with the trip segments (Section 3), generates the data samples for training/testing.
* models.ipynb: model training, experiments and evaluation presented in Section 4.
* figures.ipynb: formats the output files from the experiments in models.ipynb to be used in LaTex figures in the paper.

Configuration file for accessing our Mongo database is in the config/ directory. Access to the config file for our database will be made available on a request basis. The email address to contact
is suppressed for blind review at this time.

The directory output_r is where the output files from the data processing and experiments in the app/ notebooks are written to.