# bdt_project_lodgings_bologna

This repo contains a project for a Big Data Technology University course.  It aims to analyse offer of lodgings in Bologna, cluster them and make suggestions to a potential host.  

The notebok can be accessed here in its Binder version:
https://hub.gke2.mybinder.org/user/isadario-bdt_pr-odgings_bologna-yple5mmj/notebooks/app.ipynb

To interact with the notebook as dashboard it needs to be downloaded and the environment activated (activating the yml file or creating a new environment with the requirements.txt file) so to have the Voila button (should have been deployed on Binder - tried also with Heroku - but I kept on stumbling on issues with the nbextension/nbconfigurator). 
Here below the GIFS are meant display how it can be viewed: 

This is one of the maps for the geospatial high-level analysis of the area: 
![Most common area](demo_gif/mostcommon.gif)

Here below a demo for the filter on top of the clustering (from PCA scores) function: 
![clustering](demo_gif/clustering.gif)

To a certain extent (in terms of schema reliability) it's also possible to use one's own csv file for detailed listings
![upload](demo_gif/upload.gif)
