# Store Sales - Time Series Forecasting
<img width="560" height="280" alt="image" src="https://github.com/user-attachments/assets/aabbe0f7-dd35-4ed6-80b1-585a32f729b7" />

# Goal of the Competition
In this “getting started” competition, you’ll use time-series forecasting to forecast store sales on data from Corporación Favorita, a large Ecuadorian-based grocery retailer.

Specifically, you'll build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores. You'll practice your machine learning skills with an approachable training dataset of dates, store, and item information, promotions, and unit sales.

# Context
Forecasts aren’t just for meteorologists. Governments forecast economic growth. Scientists attempt to predict the future population. And businesses forecast product demand—a common task of professional data scientists. Forecasts are especially relevant to brick-and-mortar grocery stores, which must dance delicately with how much inventory to buy. Predict a little over, and grocers are stuck with overstocked, perishable goods. Guess a little under, and popular items quickly sell out, leading to lost revenue and upset customers. More accurate forecasting, thanks to machine learning, could help ensure retailers please customers by having just enough of the right products at the right time.

Current subjective forecasting methods for retail have little data to back them up and are unlikely to be automated. The problem becomes even more complex as retailers add new locations with unique needs, new products, ever-transitioning seasonal tastes, and unpredictable product marketing.

# Potential Impact
If successful, you'll have flexed some new skills in a real world example. For grocery stores, more accurate forecasting can decrease food waste related to overstocking and improve customer satisfaction. The results of this ongoing competition, over time, might even ensure your local store has exactly what you need the next time you shop.

# Evaluation
The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

The RMSLE is calculated as:
<img width="248" height="56" alt="rmsle" src="https://github.com/user-attachments/assets/6f3ea95c-5a0e-4691-b97e-a528167c5357" />

Where:
- n is the total number of instances,
- y^i is the predicted value of the target for instance (i),
- yi is the actual value of the target for instance (i), and,
- log is the natural logarithm.

# Submission File
For each id in the test set, you must predict a value for the sales variable. The file should contain a header and have the following format:
<img width="449" height="120" alt="submission" src="https://github.com/user-attachments/assets/57c5e8fc-43aa-4341-8215-f51bcb29ae01" />
