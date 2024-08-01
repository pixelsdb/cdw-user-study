# Cloud Data Warehouse Charging Model Research

Cloud data warehouses (including cloud data lakes and cloud lakehouses) provide users with fully managed data analysis services. Users can analyze large datasets simply by submitting SQL queries without the burden of system and infrastructure operations. There are several possible pricing models for cloud data warehouses, and we would like to know users' preferences through a questionnaire. The questionnaire consists of 7 - 8 questions that may take about 1-2 minutes. Valid answers will be rewarded with a bonus of 5 RMB (approx. 0.7 USD).

**Q1: Which of the following best fits your current situation?**

* **1**. Database developers or researchers (including graduate students)
* **2**. Practitioners who have used databases or data warehouses in their work
* **3**. Students who have taken a database course in their studies
* **4**. Other

**Q2: Which statement best reflects your knowledge of cloud data warehouses?**

* **1**. I know nothing about cloud data warehouses
* **2**. I know what cloud data warehouses are but have not used them
* **3**. I once used cloud data warehouses
* **4**. I am familiar with cloud data warehouses, even understanding some basic design principles or related technologies

**Q3: Which of the following products are cloud data warehouse? (select all that apply)**

* **1**. MySQL
* **2**. Redis
* **3**. Snowflake
* **4**. MongoDB
* **5**. Redshift

**Q4: If you were a user of a cloud data warehouse and needed to submit a set of queries to complete a data analysis task, which of the following pricing models do you think is best?**

* **1**. **Provisoned Pricing:** Users estimate the required computing resources (such as memory capacity, number of CPUs, or number of processing slots) for queries, and pay in advance for the estimated amount of resources, for example at a cost of \$1,000.
* **2**. **On-demand Pricing:** Users submit queries directly, and the system bills based on the amount of data scanned by each query. If the total amount of data scanned by the queries is small, the total cost may be less than \$1000; Otherwise, the total cost may exceed \$1000.

**Q5:** [displayed when option 2 of Q4 is selected] **For on-demand pricing, if the system further provides several performance and price levels that you can choose for each query, the highest level is as performant and expensive as the original on-demand pricing in option 2 of Q4, and the lower levels may be significantly slower but much cheaper. Compared to the original on-demand pricing, do you prefer this flexible pricing model?**

* **1**. Yes
* **2**. No

**Q6: If a cloud data warehouse could estimate the cost of each query under different performance levels before execution, and display it visually to the user, how useful would this feature be?**

* **1**. Not useful
* **2**. Somewhat useful, I might try it
* **3**. Very useful, I will definitely use it

**Q7: If a cloud data warehouse allows users to visualize and analyze the execution time and costs of previously executed queries, how useful would this feature be?**

* **1**. Not useful
* **2**. Somewhat useful, I might try it
* **3**. Very useful, I will definitely use it

**Q8: If the Cloud Data Warehouse provides a natural-language query interface, you can describe questions in text or voice, and the system can automatically generate candidate SQL queries for the questions. The correct rate is close to 100% for simple questions and around 80% for complex questions,  how useful would this feature be?**

* **1**. Not useful
* **2**. Somewhat useful, I might try it
* **3**. Very useful, I will definitely use it