## data-science-appraoches-for-tdcp-analysis
This is a directory containing the essential python files, including

#### app.py 
constructs the DASH based app imports the databasewrappers.py file and uses that file as the "connection" between the app and the data processing 
#### chachifuncs.py 
does the majority cleaning, and calculating dQ/dV from raw files, and uses the databasefuncs.py file functions to save that cleaned data in the database
#### databasefuncs.py 
updates and gets data from the database
#### databasewrappers.py 
interacts with the database and the data processing
#### databasewrappers_forjupyter.py 
the adjusted  databasewrappers.py used for jupyter notebook
#### descriptors.py 
gathers the descriptors from the model, including functions for peak finding, model fitting, sorting those descriptors for each peak, and saving those descriptors to the database
#### process_alldata.py 
wraps up all functions for jupyter notebook
#### version.py

