In this project, I have learn how to create visualizations from a large dataset using Amazon S3 and Amazon QuickSight. I have been working with a dataset of 50,000 best-selling products on Amazon.com.

## Step #1: Store the Dataset in Amazon S3
1. Open the **Amazon S3** console and click **"Create Bucket."**
2. Name the bucket (e.g., "lucy-amazon-project") and keep the settings as default.
3. Upload the **"Amazon Bestseller Dataset"** CSV file and the **"manifest.json"** file into the bucket.
4. Replace the URL in the **"manifest.json"** file with the S3 URL of your dataset.

## Step #2: Connect S3 Bucket with Amazon QuickSight
1. Open the AWS management console and navigate to **Amazon QuickSight**.
2. Sign up for a free trial of the **Enterprise edition** if you don't have an account.
3. Select **Amazon S3** and tick the box for the S3 bucket you created.
4. Enter the link to your **"manifest.json"** file and connect to QuickSight.
5. Select **"interactive sheet"** to start creating visualizations.

## Step #3: Create Visualizations
1. Drag fields into the graph to create visualizations (e.g., most popular brands).
2. Sort, filter, and customize the graphs as desired.
3. Experiment with different types of graphs like bar charts, pie charts, and line graphs.

## Future Scope
Enhance visualizations with advanced analytics features, integrate real-time data updates, and explore machine learning models for predictive insights. Consider expanding to other data sources for a more comprehensive analysis.
