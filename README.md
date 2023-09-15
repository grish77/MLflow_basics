# MLflow_basics
MLflow is a versatile, expandable, open-source platform for managing workflows and artifacts across the machine learning lifecycle. It has built-in integrations with many popular ML libraries, but can be used with any library, algorithm, or deployment tool. It provides tools and APIs that help data scientists and developers track, reproduce, deploy, and collaborate on machine learning tasks.

### Some of the important features of MLflow involve:
 Markup : 1. Model Tracking 
 The MLflow Tracking component is an API and UI for logging parameters, code versions, metrics, and output files when running your machine learning code and for later visualizing the results. For many popular ML libraries,Model tracking can be easily implemented in the ML code by simply adding mlflow.autolog() function call. If we are using one of the supported libraries, this will automatically log the parameters, metrics, and artifacts of the run. 
MLflow Tracking is organized around the concept of runs, which are executions of some piece of data science code. In each run, the information about the model such as code version, start and end time, source, parameters, metrics, artifacts, etc. MLflow Tracking is organized around the concept of runs, which are executions of some piece of data science code.

              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
Model Tracking
