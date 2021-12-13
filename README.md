# Virtual Data Cosmos

Where do cosmic X-rays come from? Every new unidentified X-ray source could potentially revolutionize our understanding of the universe. The international collaborative astronomy project EXTraS aimed at automatically classifying new sources of X-ray emission (e.g., stars or galaxies) in the large observation database of an X-ray satellite. Because the data archives have reached dimensions of big data astronomers used different machine-learning (ML) algorithms that performed the classification process.

For my bachelor thesis in design, I was interested in the challenge to visualize these big data sets in an interactive and intuitive way to facilitate the visual exploration of its internal structures and relationships. The VIRTUAL DATA COSMOS is an interactive data visualization tool in virtual reality (VR) for scientists to explore multidimensional data sets.

# Concept
The aesthetics and atmosphere of the entire virtual world is defined by the data. By interacting with a virtual environment users can explore the abstract and non-visual data space. The VR experience consists of two spaces (class room and parameter space) where users can move continuously from one space to another.

## Class room 
This room visualizes the classification results of the X-ray sources by different ML algorithms as color-coded point clouds. This room allows users to explore the class probability distribution within the data base. Each ML algorithm results in a color-coded point cloud following the principle of similarity. Objects close to the center of a sphere have a high probability of belonging to that class. This probability decreases with distance and objects are oriented towards spheres of alternative classes.

Users may explore the relationships between data points of different class spheres by changing the position of the spheres in real-time. For each source, users can activate its quantitative information on demand or zoom into its parameter space

## Parameter space 
This room provides an overview of the parameter values used by a ML algorithm for activated source. Each parameter is represented by a (semi-) circle, which forms a characteristic trace for a X-ray source. Similar objects occupy the same regions in space which demonstrates the sorting process of each algorithm.

# The DNA of your data!
The goal of this data visualization was, that data parameters define the visual parameters of the virtual world. In the class room this is achieved by mapping the data objects by similarity. In addition, every data objects can be activated to reveal a pie chart showing additional information of the underlying classification model. The challenge of visualizing all dimensions of the data sets was faced in the parameter space. 

In order to show all parameters at once, the properties of a source are mapped onto the outline of (semi-) circles. During the classification process the ML algorithm has ranked the parameters according to their characterization power. This ranking is used to define the order and size of each parameter circles. This way circles of each source form a characteristic path in space, like DNA. Similar sources occupy overlapping regions, while those of different classes are separated. By actively changing the parameter ranking users can define their own classification scheme and explore the results to critically evaluate the results of the ML algorithm.

# Documentation
https://annok.de/vdc-2/

# License 
This project is licensed under the terms of the GNU General Public License v3.0
