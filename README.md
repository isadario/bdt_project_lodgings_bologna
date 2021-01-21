# bdt_project_lodgings_bologna

This repo contains a project for a Big Data Technology University course.  It aims to analyse offer of lodgings in Bologna, cluster them and make suggestions to a potential host.  

The notebok can be accessed here in its Binder version:
https://hub.gke2.mybinder.org/user/isadario-bdt_pr-odgings_bologna-yple5mmj/notebooks/app.ipynb

To interact with the notebook as dashboard it needs to be downloaded and the environment activated (activating the yml file or creating a new environment with the requirements.txt file) so to have the Voila button (should have been deployed on Binder - trying also with Heroku, that's why the Procfile and runtime.txt- but I kept on stumbling on issues with the nbextension/nbconfigurator). 


Here below the GIFS are meant to display how it is viewed in Voila.   

This is one of the maps employed for the high-level geospatial analysis 
![popularity](demo_gif/mostcommon.gif)

and this to filter listings and display clustering (from PCA scores) labels: 
![clustering](demo_gif/clustering.gif)

