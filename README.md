# Customer Loyalty Program Data Analysis

This project analyzes and visualizes customer data stored in **IBM Cloud Object Storage (COS)**.
The dataset used is `Customers.csv`, retrieved securely from a COS bucket, and loaded into a pandas DataFrame for exploration.

## 📁 Project Description

The notebook connects to IBM Cloud Object Storage using the `ibm_boto3` library, retrieves the customer dataset, and loads it into Python for analysis.
It demonstrates:

* Connecting to COS with API credentials
* Reading a CSV object into pandas
* Previewing the dataset with `df.head()`
* Preparing for further analysis and visualizations

## 📦 Dependencies

The notebook uses the following Python libraries:

* `pandas`
* `ibm_boto3`
* `botocore`

These are typically available in IBM Watson Studio / watsonx.ai environments.

## 🔐 Important Note About Credentials

The notebook originally contained IBM COS credentials.
**Before publishing or sharing this project, remove or mask your credentials** to avoid exposing sensitive information.

## 📂 Data Source

* **Bucket:** `sample-bucket`
* **Object Key:** `Customers.csv`

The dataset includes fields such as:

* Customer ID
* Name and location
* Email and phone number
* YTD sales
* Credit card information
* Sales representative details

## ▶️ How to Run

1. Ensure your IBM Cloud Object Storage credentials are correctly set.
2. Run the setup cells to create the COS client.
3. Execute the data-loading cell to read the CSV file into a DataFrame.
4. Continue building analysis or visualizations as needed.

## 📊 Next Steps

* Perform exploratory data analysis (EDA)
* Clean or transform the dataset
* Visualize customer trends
* Build customer segmentation or loyalty predictions

---

Feel free to modify this README based on the final scope of your analysis.
