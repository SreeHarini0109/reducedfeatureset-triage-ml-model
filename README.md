# reducedfeatureset-triage-ml-model

Changes Made
**Feature Set Reduction**
The following features were removed from the training and inference pipelines:

SBP (Systolic Blood Pressure)
MAP (Mean Arterial Pressure)
DBP (Diastolic Blood Pressure)
EtCO2 (End-tidal CO2)
The model now relies exclusively on:

HR (Heart Rate)
O2Sat (Oxygen Saturation)
Temp (Temperature)
Resp (Respiratory Rate)
