* Deploy infrastructure with terraform
```
terraform init
terraform plan -out terraform.plan
terraform apply terraform.plan
....
terraform destroy
```
* Copy notebook and data into Databricks cluster
* Execute all the steps from "ML End-to-End Example" notebook

**Databricks:**:
![](images/dbw-natkw.png)

Importing notebook "ML End-to-End Example.dbc":
![](images/import.png)

Creating compute cluster:
![](images/cluster.png)

**Results:**

Screenshots from notebook:

![](images/plot_1.jpg)
![](images/plot_2.jpg)
![](images/data_1.jpg)
![](images/data_2.jpg)
![](images/data_3.jpg)
![](images/data_4.jpg)
![](images/plot_3.jpg)
