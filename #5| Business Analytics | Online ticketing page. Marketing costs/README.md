NOTE: If you can't visualize all of the graphs in the JupyterNotebook file in this repository, please access it from here >>
https://nbviewer.org/github/martiiis/Practicum_DataAnalyst/blob/main/%235%7C%20Business%20Analytics%20%7C%20Online%20ticketing%20page.%20Marketing%20costs/%235%20%7C%20Business%20Analytics%20%7C%20Server%20logs%2C%20online%20ticketing%20page.ipynb

# Project description

As Junior Data Analyst in the analytical department, I have been given the following data:

* Server logs with data on Yandex.Afisha visits from June 2017 through May 2018
* Dump file with all orders for the period
* Marketing expenses statistics

We are going to study:
* How people use the product
* When they start to buy
* How much money each customer brings
* When they pay off

# Table of Contents

 1. **Preparing the data for analysis**
  
 2. **Reports and Metrics**
    - **2.1 Product**
        * How many people use it every day, week, and month?
        * How many sessions are there per day? (One user might have more than one session.)
        * What is the length of each session?
        * How often do users come back?
        
    - **2.2 Sales**
        * When do people start buying?
        * How many orders do they make during a given period of time?
        * What is the average purchase size?
        * How much money do they bring? (LTV)

    - **2.3 Marketing**
        * How much money was spent? Overall/per source/over time
        * How much did customer acquisition from each of the sources cost? 
        * How worthwhile where the investments? (ROI)
        
 3. **Conclusion and Recommendations**
    * What sources/platforms would we recommend? 
    * Metrics we focused on? Why? What conclusions did we draw after finding the metric values?
    

# Description of the Data

  * **The `visits` table (server logs with data on website visits):**
    * `Uid` — user's unique identifier
    * `Device` — user's device
    * `Start Ts` — session start date and time
    * `End Ts` — session end date and time
    * `Source Id` — identifier of the ad source the user came from


  * **The `orders` table (data on orders):**
    * `Uid` — unique identifier of the user making an order Buy Ts — order date and time
    * `Revenue` — Yandex.Afisha's revenue from the order


  * **The `costs` table (data on marketing expenses):** 
    * `source_id` — ad source identifier
    * `dt` — date
    * `costs` — expenses on this ad source on this day
    
