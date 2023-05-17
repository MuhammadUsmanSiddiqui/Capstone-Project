## Title: Automated Analysis Tool for Distribution Loads using Python/OpenDSS

## Description

This repository hosts the code for our Capstone Project (from batch of ECE 2023) Habib University. The project aims to develop an automated analysis tool for distribution loads using Python/OpenDSS in collaboration to swiftly understand and complete distribution analysis on a network. The tool is built around a DSS script which represents a circuit and an editable Python interface that can interact with the OpenDSS engine, to show a complete distribution analysis of an IEEE 13 bus distribution test feeder, ranking violations incurred from placing loads/DERs/PV cells at different positions. The user-friendly GUI ensures that engineers can quickly generate analysis results without having to run multiple power flow profiles, thereby increasing their productivity and improving the reliability of the network.
 
Keywords: Automated Analysis Tool, Distribution Loads, Python, OpenDSS, IEEE 13 Bus Distribution Test Feeder, DERs, PV cells, Distribution Analysis, Power Flow Profiles, Open Source, Jupyter Notebook

## Installation

To install this application, you need to have pip already installed. If you don't have pip installed, you can follow the instructions [here](https://pip.pypa.io/en/stable/installation/).
You also need python 3.7 or above installed. If you don't have python installed, you can follow the instructions [here](https://www.python.org/downloads/).

Once you have, you need run the following commands in your terminal/command prompt:

```bash
pip install py-dss-interface, os, pathlib, matplotlib, numpy, math, folium, pandas
```

## Authors

[Muhammad Usman Siddiqui](https://github.com/MuhammadUsmanSiddiqui)  
[Muhammad Ali]()  
[Taher Qutubuddin]()  

## License

[MIT License](LICENSE)
