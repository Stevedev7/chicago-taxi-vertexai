# Chicago Taxi Trip Pipeline
---
An end to end machine learning pipeline to predict taxi fare in chicago. This pipeline runs on **Google Cloud Platform's Vertex AI**.

### Run the pipeline on GCP
1) Create a Vertex AI Workbench Notebook instance.
1) Start the notebook and clone the repository.
1) Run the **first 3** notebook cells to install dependencies.
1) Replace the BUCKET_NAME variable in the 6th cell with your own bucket.
1) In line number 16 of model_deploy component, replace the PROJECT_ID variable with your own project id.
1) Run the rest of the cells once the kernel restarts. 
1) Scroll down to the last cell and click on the link in the output box of the last cell to veiw the pipeline.