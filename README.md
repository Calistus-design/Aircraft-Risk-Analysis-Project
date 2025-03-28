#  **Aircraft Purchase Risk Analysis**

## **Overview**
> The aim of this project is to analyze which aircraft are the lowest risk for a company to start as a new business endeavor using actionable insights derived from In-depth data analysis.

## **Business Problem**

To determine the safest aircraft with the lowest risk for a company to purchase when starting a new business endeavor. This will be decision will be guided by actionable insights from analysis


## **Data Understanding**

The dataset contains aviation accident data, with 31 columns detailing various aspects of each incident. 

It includes information on:

- Aircraft details: Make, model, number of engines, engine type, amateur-built.

- Accident Details: Date, location (city/state/country), phase of flight, weather conditions, and accident severity.

- Operational Factors: Purpose of flight , regulatory information (FAR description), and air carrier details.

- Injury & Damage Information: Number of fatalities, serious injuries, minor injuries, and uninjured passengers.


> To gain these insights begin by:
1. Importing required libraries
2. Loading the dataset
3. Displaying an overview

## **Data Preparation**
### **Data cleaning**

> In this step after I will further explore and understood the data. Then I will be clean it so that what is left are the relevant columns with clean rows
#### **1.Select relevant features** 
#### **2.Deal with missing values**
#### **3. Imputing**
#### **4. Deal with duplicate values in the dataframe**
#### **5. Ensure consistent formatting in the Categorical columns**
#### **6. Validate that the data is clean**

## **Data Analysis**

> Here I identify key insights from the cleaned dataset to help the company make data-driven decision about which aircraft to buy
### **The Visualization include**
#### **1. Average Injury Rate by Aircraft Make**
#### **2. Average Injury Rate by Aircraft Model**
#### **3. Average Injury Rate by Engine Type**
#### **4. Average Injury Rate by Aircraft Damage Category**
#### **5. Average Injury Rate by Number of Engines**

## **Business Recommendations**

This analysis leads to **three Business recommendations**:

1. For a safer fleet, it is advisable to prioritize the **Boeing** aircraft, as they appear to be less prone to severe accidents

2. The aircraft models **180** and **152** have shown consistently lower injury rates. Opting for these models could significantly mitigate the risk of injury
3. Aircraft with more powerful engines tend to have higher injury rates. To minimize risk, focus on aircraft powered by **Turbo Fan** or **Turbo Jet engines**, which typically offer a better balance of performance and safety

## **Conclusion**
> Based on the analysis, selecting aircraft from manufacturers like **Boeing**, focusing on models such as the **180** and **152,** and choosing aircraft with **Turbo Fan** or **Turbo Jet engines**, will likely reduce the overall risk of accidents and injuries.



