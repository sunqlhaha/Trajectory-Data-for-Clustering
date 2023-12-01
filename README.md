# Trajectory-Data-for-Clustering

Title: Dataset Description for Trajectory Data

Abstract:
This document outlines the details of the simulated and actual datasets used in the research study titled "An Efficient Parallel Incremental Clustering Algorithm for Trajectory Data." The datasets comprise simulated vehicle trajectory data and real-world driving data, providing a comprehensive foundation for analysis and experimentation.

1. Simulated Data:
The simulated dataset consists of synthetic vehicle trajectory data designed to mimic different driving scenarios. Each data point represents the state of a vehicle at a specific moment, including attributes such as 'VehicleID,' 'Time,' 'Latitude,' 'Longitude,' 'Speed,' and 'OffsetAngle.' The dataset is categorized into four classes (A, B, C, and D), each with distinct characteristics:

Class A (No Lane Change, Constant Speed):
600,000 data points.
Speed: Fluctuates between 63 and 66.
Offset Angle: Random values between 0 and 5.

Class B (Lane Change, Constant Speed):
600,000 data points.
Speed: Fluctuates between 63 and 66.
Offset Angle: Random values between 30 and 80.

Class C (No Lane Change, Variable Speed):
600,000 data points.
Speed: Fluctuates between 56 and 102.
Offset Angle: Random values between 0 and 5.

Class D (Lane Change, Variable Speed):
607,500 data points.
Speed: Fluctuates between 56 and 102.
Offset Angle: Random values between 30 and 80.

2. Actual Data:
The actual dataset includes two tables, namely GOVNightDriveAlarm_SelectedData.csv and GOVOverSpeedAlarm_SelectedData.csv, extracted from real-world driving records. Both tables share common fields, including 'VehicleID,' 'BDate,' 'BTime,' 'BLongitude,' 'BLatitude,' 'EDate,' 'ETime,' 'ELongitude,' 'ELatitude,' and 'AvgSpeed.'

GOVNightDriveAlarm_SelectedData.csv: Records: 30,711
GOVOverSpeedAlarm_SelectedData.csv: Records: 280,134

3. Use Case:

Researchers can leverage this dataset for various applications, including but not limited to driver behavior analysis, anomaly detection, and algorithm validation in the context of intelligent transportation systems. The combination of simulated and real-world data offers a diverse and realistic foundation for experimentation and evaluation.

