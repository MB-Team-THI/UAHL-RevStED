# UAHL-RevStED
Official repository for the real vehicle state estimation dataset and UAHL architecture 

 **Overview** 

This repository currently contains a sample dataset for vehicle state estimation, collected using ADMA, Correvit and onboard sensors. The dataset includes time-synchronized vehicle state measurements that can be used for research and development in virtual sensors, sensor fusion, and vehicle state estimation.

**Sample Datasets**
1) ADMA_data_sample.csv
This dataset contains a 10-second measurement of vehicle dynamic states, captured from both the ADMA system and the Correvit sensor. It provides valuable data on vehicle behaviour for analysis and model development.

2) OBD_sample.csv
This dataset includes onboard sensor measurements along with the vehicle's sideslip angle obtained from the Correvit sensor. It was used in our paper submitted to the Intelligent Vehicles Symposium 2025. Currently, the values are rounded to three decimal places for improved readability. Note: The speedometer shows higher speeds than individual wheel speeds due to EU Regulation Directive 75/443/EEC.

The complete ReVStED dataset is available for download in [📄 Zenodo](https://zenodo.org/records/15270060), and dataset quantities are explained in the [📊 ReV-StED Description.xlsx](ReV-StED%20Description.xlsx) file.

**Videos**

1) A drone-captured video showcasing slalom manoeuvres performed on the test track.
  [![Watch the Video](https://github.com/MB-Team-THI/UAHL-RevStED/blob/main/Drone.png)](https://github.com/MB-Team-THI/UAHL-RevStED/blob/main/Drone_slalom_compressed.mp4)
2) A video demonstrating the UAHI-deep fusion architecture, developed as a virtual sensor for vehicle sideslip angle estimation.
[![Watch the Video](https://github.com/MB-Team-THI/UAHL-RevStED/blob/main/Virtual-sensor_predictions.png)](https://github.com/MB-Team-THI/UAHL-RevStED/blob/main/Virtual_sensor_prediction.mp4)
Note: Load the CSV files using Python, MATLAB, or any data processing tool. 

