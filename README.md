Azure Data Factory Project Requirements:
1. we have an Azure blob storage account where we are getting all raw data ( employee, department) in JSON format.
2. we need to create a pipeline and schedule it on a daily basis which will pick data from raw containers to specific employees and department container and we need to dump files in CSV format.
3. we need to create a pipeline which will be able to join the employee and department file based on the department ID and need to store it into the emp_dept container.
4. we should be able to save aggregated information of total department wise employee salary and grouping of job id.
