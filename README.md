# Data Visualization with Amazon QuickSight and Amazon S3

## Overview
This project demonstrates how to visualize data using Amazon QuickSight and Amazon S3. We use a dataset consisting of Amazon bestseller data to create visual insights. The project involves uploading data to an S3 bucket, creating a data source in QuickSight, and visualizing the data.

## Features
- **Data Storage**: Utilize Amazon S3 to store and manage data.
- **Data Visualization**: Use Amazon QuickSight to create visual representations of the data.
- **Manifest File**: Leverage a manifest file to streamline data import into QuickSight.

## Technologies Used
- **Amazon Web Services (AWS)**: Cloud computing services.
  - **Amazon S3**: Scalable storage for data.
  - **Amazon QuickSight**: Business intelligence service for data visualization.
- **Bright Data**: Data extraction tool.

## Steps

### Step 1: Create S3 Bucket and Upload Data
1. **Open AWS Console**: Log in to your AWS account.
2. **Create S3 Bucket**: 
   - Search for S3 in the AWS console.
   - Create a new bucket named `aws-project-amar`.
3. **Upload Data**:
   - Upload the Amazon bestseller dataset and a manifest JSON file to the S3 bucket.

### Step 2: Set Up Amazon QuickSight
1. **Open QuickSight**:
   - Open a new browser tab and search for Amazon QuickSight.
   - Create an account in Amazon QuickSight if you haven't already.
2. **Create New Data Set**:
   - Click on the "New Data Set" button on the top left.
   - Go back to your S3 bucket, open the manifest JSON file, and copy the URL.
   - In QuickSight, select "S3" as the data source and provide a name for the data source.
   - Paste the copied URL from the S3 manifest JSON file.
   - Load the data into QuickSight.

### Step 3: Visualize Data
1. **Create Visualization**:
   - Drag and drop the `brands` data onto the visual board.
   - Name the sheet "Most Popular Brands."
   - Arrange the data in ascending order to visualize the popularity of the brands.

     ![Screenshot 2024-08-03 232319](https://github.com/user-attachments/assets/5b67a93b-0229-4975-b401-3b208a90cd00)
2. **Create Pie Chart**:
   - Drag and drop the `product_id` data onto the visual board.
   - Select the pie chart as the visualization type.
   - Name the sheet "Product ID "
   - Adjust the chart to clearly display the distribution of `product_id` categories.

    ![Screenshot 2024-08-03 232348](https://github.com/user-attachments/assets/cb8a29d4-3359-4ccc-82b3-07042df3fc23)
### Step 4: Complete the Project
- Review the data visualizations to ensure they accurately represent the dataset.
- Save and share your QuickSight dashboard.

## Conclusion
This project demonstrates the integration of Amazon S3 and Amazon QuickSight to create insightful data visualizations. By following these steps, you can leverage AWS services to transform raw data into meaningful visual insights.
