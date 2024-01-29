# portfolio-VaR
This project goes over the mathematical foundations of risk measurement tools used on financial portfolios and provides a software tool for calculating risk on an arbitrary portfolio. The following files are included:

### <code>Model_Documentation.pdf</code>
The purpose of this document is to review the mathematical intuition behind three common Value at Risk (VaR) and Expected Shortfall (ES) techniques: Monte Carlo, parametric, and historical.

### <code>Software_Design_Documentation.pdf</code>
This document focuses on the software needed to execute our equity portfolio VaR model. In particular, it gives the software architecture and end user documentation.

### <code>Project_Code.ipynb</code>
The software used for calculating VaR and ES.

### <code>Test_Plan_and_Results_Documentation.pdf</code>
This document serves to test our model. It includes component testing (looking at intermediate results of the model to see if they are reasonable), accuracy testing (comparing the results of the model to those which have been found by previous researchers), and robustness testing (changing many different inputs and checking if the model still performs as expected).

### <code>Testing_Repository.ipynb</code>
The code used for the resultes in the <code>Test_Plan_and_Results_Documentation.pdf</code> document.
