# Analyze_ab_test_results
Udacity Advanced Data Analysis project
A/B tests are very commonly performed by data analysts and data scientists. For this project, We will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. The goal is to work through this notebook to help the company understand if they should:

Implement the new webpage,
Keep the old webpage, or
Perhaps run the experiment longer to make their decision.
Below is the description of the data, there are a total of 5 columns:

Data columns	Purpose	Valid values
user_id	Unique ID	Int64 values
timestamp	Time stamp when the user visited the webpage	-
group	In the current A/B experiment, the users are categorized into two broad groups.
The control group users are expected to be served with old_page; and treatment group users are matched with the new_page.
However, some inaccurate rows are present in the initial data, such as a control group user is matched with a new_page.	['control', 'treatment']
landing_page	It denotes whether the user visited the old or new webpage.	['old_page', 'new_page']
converted	It denotes whether the user decided to pay for the company's product. Here, 1 means yes, the user bought the product.	[0, 1]
