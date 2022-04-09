
# Project Title

Customer Cares center performance analysis is driven by how the executive performs and improves the rate of convergence. The Project aims to develop an AI based solution which will identify poor performers, suggest improvements and improve the overall performance of executives. 
Inline to the overall objective, the focus of team is to 

1. Identify what factors are impacting the Lead-Customer conversion
2. Create AI model to predict the conversion outcome and handle effective Quote/Lead assignment to Agent with high Binding Rate
3. Analyze and identify the attributes to improve Binding Rate of Poor Performing Agents.
4. Develop a model that supports the Insurance company in improving the overall binding rate


## Requirements

To deploy this project the following softwares are required

1. python 3.9
2. Jupyter Lab
3. pip


## Deployment

### To deploy this project follow below steps

1. Unzip the downloaded project file and Name it as below: 

    ```bash
    CustomerCareExecutivePerformanceAnalysis
    ```
    
2. Install python libraries required for the project

    a) Using file menu - open the below mentioned directory from the unzipped project file and open the terminal.

    ```bash
    /CustomerCareExecutivePerformanceAnalysis/App/main/project/utils
    ```

    a) Run below command to install required python libraries

    ```bash
    pip install -r requirements.txt
    ```

3. open jupyter lab 
    
    ```bash
    jupyter notebook
    ```

4. There is a ipynb notebook of project in the below mentioned location. Open the notebook in jupyter lab and run all cells. You can see the outputs at each cell and also our observations under each output

    ```bash
    /CustomerCareExecutivePerformanceAnalysis/App/main/notebooks
    ```


### API Endpoint visulaiztion

1. Create virtual environment
    
    a) Using file menu - open the below mentioned directory from the unzipped project file

    ```bash
    /CustomerCareExecutivePerformanceAnalysis/App/main
    ```

    b) open the terminal at above mentioned location and create the virtual environment as below:
    
    ```bash
    python -m venv capstone_gp_11
    ```
    
    c) Activate venv using 
    
    ```bash
    capstone_gp_11\Scripts\activate
    ```

3. Install python libraries required for the project

    a) Run below command to install required python libraries

    ```bash
    pip install -r /project/utils/requirements.txt
    ```
    
4. Run main.py to trigger the API Endpoint

    a) go to below mentioned folder

    ```bash
    /CustomerCareExecutivePerformanceAnalysis/App/main/project/api
    ```

    b) Run below command to start the API endpoint

    ```bash
    univcorn main:app --reload
    ```

    c) please check the terminal and you will find the local address where you can access the API endpoint of the project. Open browser and search for the same
    
    ```bash
    127.0.0.1:8000/docs
    ```
    d) Make sure 8000 port is avaiable. If not please check the terminal and you will find the local address where you can access the API endpoint of the project.
    





## Support

If yuo face any challanges please email us at 
    
    a) 2020aiml520@wilp.bits-pilani.ac.in
    b) 2020aiml520@wilp.bits-pilani.ac.in
    c) 2020aiml520@wilp.bits-pilani.ac.in
    d) 2020aiml520@wilp.bits-pilani.ac.in

