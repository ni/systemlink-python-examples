# systemlink-server-examples

This repository contains Python-based NI SystemLink examples.

## Using systemlink-server-examples

### Jupyter examples

The **jupyter** folder contains Jupyter notebook examples that exercise the different SystemLink Services APIs (Tag, File, TDMReader and Test Monitor) and applications (Analysis Automation). To be able to run these examples, you need to have the "NI SystemLink Server - JupyterHub Module" installed. From the Jupyter interface in SystemLink, create an examples folder and upload all the content of the jupyter folder. For additional documentation on how to upload/download files to a Jupyter server, check https://jupyterlab.readthedocs.io/en/stable/user/files.html. Once the notebooks are uploaded, follow the instructions on each notebook.

### Test Monitor examples

The **dashboards** folder contains example layouts and tile configurations for customized use.
- [testmonitor/OEE](./dashboards/testmonitor/OEE) - Overall Equipment Effectiveness

The **python** folder contains examples of accessing the SystemLink server via Python clients.
- [testmonitor/results](./python/testmonitor/results) - Upload test results and steps to the Test Monitor service.
