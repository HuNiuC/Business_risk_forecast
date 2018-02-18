Business shutdown risk forecast

Background:
Traditional enterprise evaluation mainly based on the financial information of enterprises, credit records and other information to determine the business status of the company, and whether it is possible to default and other credit information. For financially sound, large and medium-sized enterprises that have records in traditional areas of bank lending, the evaluation method is undoubtedly more objective and reasonable. However, for a large number of small and medium-sized micro-enterprises, they can neither publicly obtain the real financial information of enterprises nor the open credit information of these enterprises. How to use the weak variables to objectively and justly evaluate the operating conditions of enterprises in the absence of strong variables The main problem to be solved.
The contest from the country more than 20 million enterprises extracted part of the business (after desensitization), to provide business entities in many aspects of behavioral footprint information data. The teams need to build predictive models of whether the business will run poorly in the future through data mining techniques and machine learning algorithms, and output the risk prediction probability values.

Mission Details:
Focusing on the enterprise, the training data set is constructed around the behavioral footprint left by the main body of the enterprise, and whether the enterprise will exit the market due to poor management in the next two years as the target variable to predict.
The participants need to use the enterprise information data in the training data set to construct the algorithm model, and use the algorithm model to verify the data centralized enterprise, and give the forecast result and the risk probability value.
Predictive results are based on the AUC value as the primary criterion for evaluation, with AUC values (Precision and Recall) in the case of the same AUC value (retained after 4 digits of the decimal point).

Data introduction:
This question provides two kinds of data
(1) Enterprise identity information and the behavior data of the enterprise within a certain period of time. This data is the same for both the training set and the evaluation set.
(2) target data. The target value for the business in August 2017 when the operating conditions: closed down 1, normal operation 0
This table only has training data.

Training data contains :
entbase.csv
alter.csv
branch.csv
invest.csv
right.csv
project.csv
lawsuit.csv
breakfaith.csv
recruit.csv
qualification.csv
