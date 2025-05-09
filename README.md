# SnowflakeLineage
Demonstration of Snowflake capabilities for Data and ML Model Lineage

This is a self-contained demo.  Simply download the notebooks and *.png files in this repo then import it as Notebooks in Snowsight (SnowflakeLineageDemo.ipynb and SnowflakeLineageDemo-Setup.ipynb).  Here's the step-by-step:

Environment Setup Instructions
1. Download all the files in this repo
2. In Snowsight,  click Projects->Notebooks. Click the drop-down by **+Notebook** in the upper right and select "**Import .ipynb file**". Navigate to the file SNOWFLAKELINEAGEDEMO-setup.ipynb that you just downloaded and click **Open**.
3. In the **Create Notebook** panel, select a location (datebase/schema) for this notebook. Under Python environment select "**Run on warehouse**", select a **Query Warehouse** and click **Create** at the bottom.
4. In the notebook, click the dropdown under **Packages** up top and search for **snowflake-ml-python**. Click on the name.
5. Run each cell in this notebook. 

Demo Execution Instructions
1. In Snowsight,  click Projects->Notebooks. Click the drop-down by **+Notebook** in the upper right and select "**Import .ipynb file**". Navigate to the file SNOWFLAKELINEAGEDEMO.ipynb that you just downloaded and click **Open**.
2. Import the *.png files into the notebook to support the narrative of the demo and provide additional info and context
     Open side panel on left
     Click "+"
     Drag the png files to the box in the center and click "Upload"
3. In the notebook, click the dropdown under **Packages** up top and search for **snowflake-ml-python**. Click on the name.

Now you're ready to go!  Execute each cell in order to demonstrate Snowflake Lineage capabilities for data and ML Models



