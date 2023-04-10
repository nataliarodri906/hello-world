# hello-world
A place where I store ideas, resources, or even share and discuss things with others.
### This is a practice for what I will be doing for the: Azure Synapse 1-click POC environment with pre-populated dataset, pipeline, notebook

# **Module 2: Synapse ADX pool guide** 
Module 2 will be focused on the basic steps to load and analyze the Trip Data (time-series data) with Data Explorer for Azure Synapse

## Create a Data Explorer Pool on Azure Synapse
1. In Synapse studio, on the left-side pane, select **Manage > Data Explorer pools**
2. Select **New**, and then enter the following details on the **Basics** tab:  
   | Setting | Value | Description |
   |:------|:------|:------
   | Data Explorer Pool Name | adxpooltaxitrip | This is the name the Data Explorer pool will have |
   | Workload | Compute Optimized | This workload provides a higher CPU to SSD storage ratio. |
   | Node Size | Small(4 cores) | Set this to the smallest size to reduce costs for this quickstart |  
 3. Select **Review + Create > Create.** Your data explorer will start the provisioning process. 

## Create a Data Explorer Database  





