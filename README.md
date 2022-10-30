# Customer-Segmentation

![GetPaidStock com -635e3d2331dbc](https://user-images.githubusercontent.com/73393430/198870602-4f89b39b-78f8-4626-ac4e-63d9943a0adf.jpg)

<div class="alert alert-block alert-warning">
Please note that plotly figure will not show when it is uploaded to GitHib due to static stuff. So you can rerun the code once you have it on your Local machine or check out the Link I include in the repo that display the notebook on web.

Click [here](https://nbviewer.org/github/ibrahim-ogunbiyi/Customer-Segmentation/blob/main/Customer%20Segmentation.ipynb) to see the note on nbviewer.
</div>

# Business Problem
Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

link to dataset: [here](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

# Methodology
- Jupyter environment (Jupyter Lab or Jupyter notebook) – for experimenting our project.
- Pandas – For loading data as a dataframe and wrangling the data.
- Numpy and Scipy for performing some basic mathematical computation.
- Scikit-Learn – For building our Customer Segmentation Model.
- Seaborn, Matplotlib and Plotly Express – for data visualization.
- KneeLocator

# Insights and Conclusion
Firstly from the EDA we saw that Income was really the key indicator that was determined the amount a customer will spend.
![newplot (19)](https://user-images.githubusercontent.com/73393430/198870765-0d4c8a32-31ea-4f8d-8b99-69f6a07ed760.png)


Also In terms of Education we noticed customers with graduate education level and above tends to spend 12 times higher than those customers with undergraduate education level. The reason for this is because customers with graduate education level and above earns above 2 times than customers with undergradute education level.
![newplot (18)](https://user-images.githubusercontent.com/73393430/198870733-ce31e564-c4ba-467f-a6dd-51eef514fbf0.png)


Also we noticed a trends in terms of total children and total amount spent. We saw that on average there was a decline on the amount spent as the total number of children increases.I.e, as children increases so do the amount spent on average reduces.

# Result From Clusters

![newplot (17)](https://user-images.githubusercontent.com/73393430/198870806-93fb7387-48cd-4c86-94fc-701b2d5bb458.png)

Thank you for reading.

