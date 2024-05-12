# Autonomous Robotics: GNSS Raw Measurements (Ex0)

## Overview

This project explores the basic principles of the Global Navigation Satellite System (GNSS), focusing on the implementation of a naive positioning algorithm using the Root Mean Square (RMS) of selected pseudo-ranges. It involves parsing GNSS raw measurements from a log file, calculating satellite positions in Earth-Centered, Earth-Fixed (ECEF) coordinates, and implementing an algorithm to compute positional data (X,Y,Z) and its corresponding geographic coordinates (Latitude, Longitude, Altitude).

## How to run

Edit the path of your GNSS txt file in the ReadGNSS.ipynb file (the field "input_filepath").
Then, you can execute all cells in the order.
The output will be saved as a pandas Data,CSV file and KML file.


### Prerequisites

- Required Python packages: `numpy`, `pandas`, `matplotlib`, `simplekml`, `georinex`, `xarray`, `unlzw3`, `navpy`


### Created by
Daniel Rivni, Ori Elimelech, Nitay Levy