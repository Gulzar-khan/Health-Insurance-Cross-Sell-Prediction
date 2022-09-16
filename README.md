#Health-Insurance-Cross-Sell-Prediction

📖Project Workflow:

1. Importing Libraries

2. Loading the dataset

3.EDA on features

4. Feature Engineering

5. Feature selection

7. Applying some technique

8. Fitting the classification models

9. Cross validation and HyperParameter Tuning

10. Final selection of the model

11. Feature importance

12. Conclusion

📖Introduction:

As we all knew Cross-selling involves selling customers related items when they are making a purchase. It's important not only because it boosts revenue, but also because it increases customer satisfaction, builds engagement, and helps to create solid and lasting customer relationships.

Cross-selling insurance allows you to earn additional profit without the cost of searching for new leads. Additionally, you build your client relationship by staying up to date on events and changes in your client's lives which might require new or greater coverage. This can lead to improved client retention.

Our client is an Insurance company that has provided Health Insurance to its customers now they need our help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

After getting your model reports company can do some Digital marketing and automation to grow insurance agency in the field of vehicle insurance through cross-selling and increase their revenue via investing in reproductive marketing campaign.


📖Problem Statement:

Insurance is the process by which companies commit to guaranteeing compensation for specified loss, damage, illness, or death as reimbursement for a specific premium.

Like medical insurance, there is a car insurance policy where every year the customer needs to pay a premium to the insurance company so that in the event of a car accident, the insurance company will provide compensation (called a 'guaranteed amount') to the customer.

The objective of this project is to build a Model to predict whether the policyholders from the past year will also be interested in vehicle insurance provided by the same company. Creating a prediction model that a customer can be interested in Car Insurance is very helpful for the company as it can effectively plan its communication strategy to reach those customers and increase its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

📖 Abstract:

Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called 'sum assured’) to the customer. Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.


📖Dataset:

1. id: Unique ID for the customer

2. Gender: Gender of the customer

3. Age:  Age of the customer

4. Driving_License 0: Customer does not have DL, 1: Customer already has DL

5. Region_Code: Unique code for the region of the customer

6. Previously_Insured: 1: Customer already has Vehicle Insurance, 0: Customer doesn't have Vehicle Insurance

7. Vehicle Age:  Age of the Vehicle

8. Vehicle_Damage :1: Customer got his/her vehicle damaged in the past. 0: Customer didn't get his/her vehicle damaged in the past.

9. Annual_Premium: The amount customer needs to pay as premium in the year

10. PolicySalesChannel:  Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

11. Vintage: Number of Days, Customer has been associated with the company

12. Response:  1: Customer is interested, 0: Customer is not interested


Number of instances: 381109

Number of attributes: 12


📖Libraries:

Numpy
Pandas
Matplotlib
Seaborn
Scikit-Learn
Skopt


ML Models: applying 10 classification models






📖 Conclusion:

Our client is an insurance firm that has supplied Health Insurance to its customers. They now need assistance in developing a model to predict whether the policyholders (customers) from the previous year will be interested in the company's Vehicle Insurance.

Building a model to predict if a client is interested in Vehicle Insurance is extremely beneficial to the company because they can then plan communication strategy to reach out to those customers and optimise its business model and revenue.

Now, we have information about demographics (gender, age, region code type), vehicles (vehicle age, damage), policies (premium, sourcing channel), and so on to predict whether the customer would be interested in Vehicle insurance.


Key points:

Customers of age between 30 to 60 are more likely to buy insurance.

Customers with Vehicle_Damage are likely to buy insurance.

Customers with Driving License have higher chance of buying Insurance.

The variable such as Age, Previously_insured,Annual_premium are more affecting the target variable.

We can see that LGBM model preform better for this dataset.


Improvements:

By using a marketing and advertising approach, we can reduce the gender gap.

We can clearly see that we have a larger number of consumers without vehicle insurance, therefore we can easily target them directly with our campaign.

Since there are less policy holders with vehicles older than two years, we must pay more attention to the other two categories (1-2 years and >1 year). Because most sales agencies that offer vehicle insurance for the first year are actually our target and we can give them the best incentives to reduce competition in the market.

As we saw that we have nearly equal policy holders for both vehicle damage status, so we can target those policy holders whose vehicles are damaged in the past.



📖Best Model :

LGBM Classifier:

Train Recall = 95

Test Recall= 92



📖Execution Instructions

To run on your local system:
Step I: Use this command to install required libraries: pip install -r requirements.txt

Step II: After it run the ipynb file using any IDE on your local system.

You can directly run the ipynb file on google colab.
