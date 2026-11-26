# funding-service-cfs-utility
This repo holds the utility project for Archival process. It moves data based on Query from Azure cosmos to Azure Cosmos/Azure Blob The Project is basically for Developer Use and not Business.
# Getting Started
1)Pull the code 
2)verify the App config to make sure the right envirnemnt/PaaS Service is pointed.
3)Verify the CosmosQuery in App Config
4)verify correct partition key is given (if partition key is needed for cosmos)
5)You need to add your IP in the Azure cosmos Networking Section.



# Build and Test
1)Select ArchiveTool project.
2)Run the code (F5) and provide select the right option.
3)Validate the number of files read by Utility is exacty same as you mentioned in App Config query

# Contribute
Other Developers can Pull the code and push the changes to improve performace or add another functionality
