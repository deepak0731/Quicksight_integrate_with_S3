# Quicksight_integrate_with_S3
Created data visualizations using Amazon S3 and Quicksight, working with a large dataset of Amazon products.

In this project, you'll learn how to create visualizations from a large dataset using Amazon S3 and Amazon Quicksight. We'll be working with a dataset of 50,000 best-selling products on Amazon.com.

Step #1: Download the Dataset.

Navigate to Quicksight_integrate_with_S3 to download the "Amazon Bestseller Dataset" CSV file and the "manifest.json" file.
Save both files onto your computer.

Step #2: Store this dataset in Amazon S3

"Create Bucket" with S3 console  
Name the bucket (e.g., "deepak-aws-project") and keep the settings as default.
Upload the CSV file and the "manifest.json" file into the bucket.
Replace the URL in the "manifest.json" file with the S3 URL of your dataset.

Step #3: Connect S3 Bucket with Amazon Quicksight

Open Quicksight on Managment console.
Select Amazon S3 and tick the box for the S3 bucket you created.
Enter the link to your "manifest.json" file and connect to Quicksight.
Select "interactive sheet" to start creating visualizations.

Step #4: Create Visualizations

Drag fields into the graph to create visualizations (e.g, Most popular brand etc).
Sort, filter, and customize the graphs according to you.
You can try different types of graphs like bar charts, pie charts, line graphs, etc.
