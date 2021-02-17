![](simulation_Demo_Output.gif)

This is a repository for the associated Python code for the manuscript titled: From spikes to intercellular waves: tuning intercellular Ca<sup>2+</sup> signaling dynamics modulates organ size control. The code was built by [Dr. Ramezan Paravi Torghabeh](https://www.linkedin.com/in/ramezan-paravi-torghabeh-phd-b432baa0/). The code was then later updated and adapted for creation of the figures in the manuscript by [Francisco Huizar](https://www.linkedin.com/in/francisco-huizar-82bb1a127/). Experimental work and validation was led by [Dharsan Soundarrajan](https://scholar.google.com/citations?user=AWv4OiIAAAAJ&hl=en). This work was done within the [Multicellular Systems Engineering Lab](http://sites.nd.edu/zartmanlab/) at the University of Notre Dame. Please direct any questions to the lab principal investigator, [Dr. Jeremiah Zartman](http://sites.nd.edu/zartmanlab/contacts/). 

All code was done using [Jupyter](https://jupyter.org/) notebooks where all code was run and the visible outputs are saved in the iPython notebooks. The code is available to be downloaded and run after installation of the latest version of [Jupyter](https://jupyter.org/) and [Python](https://www.python.org/). All simulation outputs were coded to be saved in the 'simulationResults' folder, and are labeled according to figure numbers. Use of [Epitools](https://epitools.ausvet.com.au/) was done to create a 2-D geometrically accurate representation of the Drosophila wing imaginal disc. The corresponding folder for this is in the 'epitools (Figure S1 Creation)' folder.

# Instructions to run the code
- You can download all of the associated code [here](https://github.com/fjhuizar/MSELab_Calcium_Cartography_2021/archive/master.zip)
  - Each notebook is labeled corresponding to its associated figure in the main text of the manuscript.
- Extract the downloaded .zip folder where you would like to run the code using Jupyter
- Within the now extracted folder extract the 'stochastic.zip' and 'geometry.zip' folders as well
- Install all necessary Python packages using the Anaconda Prompt terminal after Jupyter and Python have been installed.
  - This is done by entering the following into the terminal:
  ```
  pip install -r /path/to/requirements.txt
  ```
  - **NOTE**: 'path/to/' should be changed to the correct path where the code was extracted to
- Use Jupyter to open each individual notebook to run the simulations

# Acknowledgements
We would like to thank [Trent Robinett](https://www.linkedin.com/in/trent-robinett-5a8979161/) for his contributions towards completion of the manuscript. In particular, we would like to highlight his efforts in carrying out experiments alongside [Dharsan Soundarrajan](https://scholar.google.com/citations?user=AWv4OiIAAAAJ&hl=en).

The work in this manuscript was supported by NIH Grant R35GM124935 and NSF Award CBET-1553826. The authors gratefully acknowledge the Notre Dame Center for Research Computing (CRC) for providing computational facilities in addition to [members of the Zartman Lab](http://sites.nd.edu/zartmanlab/members/) for helpful discussions and feedback.

# Repository last updated: February 16, 2021 8:00PM EST
