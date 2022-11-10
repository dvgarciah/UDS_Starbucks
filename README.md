# Starbucks-Capstone-Project
Udacity Data Scientist Nanodegree

## Project Overview
Starbuck provide a data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

The task is to combine transaction, demographic, and offer data to determine which demographic groups respond best to which offer type.


## Files description
The data is contained in three files:

- portfolio.json — containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json — demographic data for each customer
- transcript.json — records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variables in the files:
```

portfolio.json

	- id (string) — offer id
	- offer_type (string) — type of offer ie BOGO, discount, informational
	- difficulty (int) — minimum required spend to complete an offer
	- reward (int) — reward given for completing an offer
	- duration (int) — time for offer to be open, in days
	- channels (list of strings)

profile.json

	- age (int) — age of the customer
	- became_member_on (int) — date when customer created an app account
	- gender (str) — gender of the customer (note some entries contain ‘O’ for other rather than M or F)
	- id (str) — customer id
	- income (float) — customer’s income

transcript.json

	- event (str) — record description (ie transaction, offer received, offer viewed, etc.)
	- person (str) — customer id
	- time (int) — time in hours since start of test. The data begins at time t=0
	- value — (dict of strings) — either an offer id or transaction amount depending on the record
```

## Project motivation
It is the Starbuck's Capstone Challenge of the Data Scientist Nanodegree in Udacity. We get the dataset from the program that creates the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers. We want to make a recommendation engine that recommends Starbucks which offer should be sent to a particular customer.

## Results
You can find the results of this exercise [here](https://medium.com/@dvgarciah/how-is-the-behavior-of-customers-within-the-mobile-rewards-application-87c6cd3d1554) 

## Acknowledgements
I consulted the following Github repositories to be able to carry out this project:

- https://github.com/Chintan5384/Starbucks-Capstone-Project/blob/master/Starbucks_Capstone_notebook.ipynb
- https://github.com/joshuayeung/Starbucks-Capstone-Challenge/blob/master/Starbucks_Capstone_notebook.ipynb
- https://github.com/LailaSabar/Starbucks-Capstone-Challenge/blob/master/Starbucks_Capstone_notebook.ipynb
- https://github.com/JcFreya/Starbucks-Capstone-Challenge/blob/master/Starbucks_Capstone_notebook.ipynb
- https://github.com/joshuayeung/Starbucks-Capstone-Challenge/blob/master/Starbucks_Capstone_notebook.ipynb
- https://github.com/susmithagudapati/Starbucks-Capstone-Challenge/blob/master/Starbucks_Capstone_notebook.ipynb
- https://github.com/AmalAlzaidi/Starbucks-Capstone-Challenge-Project/blob/master/Starbucks_Capstone_notebook_final.ipynb
- https://github.com/kiranukamath/Starbucks-Capstone-Challenge/blob/main/Starbucks_Capstone_notebook.ipynb
- https://github.com/data-clash/Starbucks-Capstone-Challenge/blob/main/Starbucks_Capstone.ipynb
