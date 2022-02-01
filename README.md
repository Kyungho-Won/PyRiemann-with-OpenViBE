# PyRiemann-with-OpenViBE
Example use of PyRiemann with OpenViBe Python scripting box
This script aims to decode multi-class motor imagery (e.g., left/right hands, tongue, feet)

Parts (under developing)
1. Scenario - collecting EEG without feedback (calibration)
2. Calculating mean covariance matrices for each class using calibrated EEG - (independent Python script)
3. Scenario - online classification in OpenViBE Pythobn scripting box

OpenViBE 3.0.0 and newer has built-in Riemannian geometry, but a bit difficult to modify.
Graz visualization basically assumes binary classification, so online applications with more than two classes need changes
