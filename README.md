# source-code-analyser
This project explored a data-driven approach to source code analysis for C/C++ functions. A total of 3 models were created and trained on software metrics outlined in the [Common Weakness Enumeration](https://cwe.mitre.org/data/definitions/699.html). 

The [datasets](https://osf.io/d45bw/) used for training, validation and testing were too large to upload to this project, but can be installed separately in HDF5 format.

Results are included and graphically displayed on confusion matrices near the bottom of the notebook.

A front-end was implemented via Gradio and will analyse any inputted C/C++ functions against the 3 models. Model certainty can be changed with the slider provided in the front-end. 

![gradio-front-end](https://user-images.githubusercontent.com/72401174/170880993-8f3674bb-867b-47f9-b699-5aacb20fadbe.PNG)
