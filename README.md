# ProjectName Goes Here

This project contains shared documentation, results, and code for the blah blah blah ... details aboout your project in the Drylands Ecosystem Research Team at Arizona State University.

All data for this project are stored: _details on data storage goes here. Note that all data should be stored in ASU DERT Dropbox (work with Heather if there is some need for an exception to this location_

All code in this repo should be structured so that it will run from within this repo, reading data from the DERT Dropbox and writing summary data files, figures, analysis results, and other output in Dropbox.

Note that each user will need a copy of the file "config.yml" in their local copy of this repo. The config.yml file will direct R to the correct Dropbox path to read and save files in Dropbox. The ".gitignore" file must have "config.yml" in it (see gitignore in this repo as an example). For more information on this, please see the file "DERT Data and Code Storage" in our Dropbox (DERT/Field and Lab SOPs/Data SOPs).

The project is structured with the following folders:

    doc: contains text files and other documentation for the project. This folder should either contain all needed metadata, or an indication of where data         are stored (which should be Dropbox if not GitHub)
    code: source code (.R or .qmd) for analyses in R

Note that additional subfolders can be added for code and doc if needed, but these should be carefully added in a hierarchical structure. A single R project should reside in the root directory of the repo. 

Contact Information/
_all users should add their information here_/
Heather Throop: heather.throop@asu.edu 
