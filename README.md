# benchmarkpysyft
File to test the federal learning speed of Pysyft library

Make sure you installed pysyft and torch correctly. I advice you to follow this steps: https://github.com/OpenMined/PySyft/blob/dev/INSTALLATION.md

First, you should run the files startserverworker.py and startserverworker2.py after modifying your IP address accordingly.

Then you can open either:
- PredictPytorchBreastCancerWithoutValidationAndTest.ipynb to test pure PyTorch model
- PredictPytorchBreastCancerFederateWith2workers.ipynb to test the Federal Learning with PySyft. (don't forget to change your IP address accordingly).

