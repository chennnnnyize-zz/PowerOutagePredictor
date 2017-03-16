# Power Outage Predictor

As the name suggests, Power Outage Predictor is a python package dedicated to predict power outages given certain weather conditions. Although the package can be implemented in any, the package was developed using utilities and weather data in Seattle, WA; hence caution should be made on prediction power outage elsewhere. A GUI implementation of the package is also available, though it is not complete.

## License
Since we do not plan to commercialize this, this project is under the permissive MIT license. If anything changes, we will be sure to update accordingly. If you do happen to want to use any parts of this project, please do give reference. For more details, please read LICENSE.md

## Software Dependencies

* matplotlib
* scikit-learn
* numpy
* pandas

## Repository Structure

### Data
Contains the data used in this project. It also contains a directory "backup" that contains pre-processed data; this directory should be ignored except by contributors to this project.

### Docs
Presentations and posters related to this project.

### GUI demo
GUI implementation of this project. Note that this is still not fully functional.

### Graphs
Workflow and images pertaining to design considerations.

### PowerOutagePredictor
The meat (or tofu if you are vegetarian) of this project. Contains all the python packages and modules of machine learning methods to predict power outages.
