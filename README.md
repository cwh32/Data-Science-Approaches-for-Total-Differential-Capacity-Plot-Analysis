## Data-Science-Approaches-for-Total-Differential-Capacity-Plot-Analysis      <img align="center" src="images/UW_ChemE.jpg" width="100"> 
### Documentiation and demonstration of the "chachies" directory
The objective of this GitHub repository is to show the documentation and demonstration of the codes in the "chachies" repository. (https://github.com/cwh32/chachies)

"Chachies" is a package that can be used to quantitatively analyze raw cycling data as differential capacity plots. Differential capacity plots (dQ/dV) can be very powerful for uncovering battery performance characteristics, as the peaks that appear in these plots correspond to the various electrochemical events. However, because of the large amount of data gathered many researchers report subsets of cycles and purely qualitative conclusions. This package adds the ability to quantify this type of analysis by cleaning battery cycling datasets and obtaining peak locations, widths, amplitudes, and other descriptors for every charge/discharge cycle in the data. To this end, this tool develops individualized models for each charge and discharge cycle in the data set, comprised of a gaussian baseline and pseudo-voigt distributions at each peak location.

### Essential Python files
There are 8 essential python files in the "data-science-appraoches-for-tdcp-analysis" directory, including
```
app.py
chachifuncs.py
databasefuncs.py
databasewrappers.py
databasewrappers_forjupyter.py
descriptors.py
process_alldata.py
version.py
```

### Documentations
There are 5 jupyter notebooks files in the "docs" directory, serving as the documentation for those essential python files above, including
```
chachifuncs.ipynb
databasefuncs.ipynb
databasewrappers.ipynb
databasewrappers_forjupyter.ipynb
descriptors.ipynb
```

### Demonstrations
There are 2 jupyter notebooks files in the "examples" directory, serving as the demonstrations for the main process of this analysis, including
```
process_data_example.ipynb
machine_learning_example.ipynb
```

### User Interface
#### To install
```
pip install chahies
```
#### Software Dependencies 
- Python3 
- For python packages see requirements.txt
#### Data Visualization 
Make sure to install the following dash libraries
```
pip install dash==0.21.0  # The core dash backend
pip install dash-renderer==0.11.3  # The dash front-end
pip install dash-html-components==0.9.0  # HTML components
pip install dash-core-components==0.18.1  # Supercharged components
pip install plotly --upgrade  # Latest Plotly graphing library
```

To run the app run the following in terminal:
```
python app.py
```
Which should return
```
 * Running on http://someurl/ (Press CTRL+C to quit)
```
Type that URL in browser to launch
#### Preview of app 
![Preview](images/gif3_interactivegraph.gif)

