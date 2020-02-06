# Define the Requirement Exercise

* What services should the public cloud deployment offer to the customers?  
Answer: A front-end website provide Internet banking service for bank clients. It requires to communicate with the Core banking application hosted on on-prem data centers.

* How will the users consume those services? Will they use Internet access or will you have to provide a more dedicated connectivity solution?  
Answer: The users will access the website via Internet

* Identify the data needed by the solution you're deploying. What data is shared with other applications? Where will the data reside?  
Answer: The website code will be stored on public cloud. It requires to reach on-prem database for user authentication and banking transactions. 

* What are the security requirements of your application?  
Answer: Authentication and Data in-motion encryption

* What are the high availability requirements?  
Answer: As this is a bank, we aim for always-on availability. Target RTO < 1/2 hour , RPO = 1/2 hour

* Do you have to provide connectivity to your on-premises data center? If so, how will you implement it?  
Answer: Yes. There will be 2 connections: 1. via Internet and 2. via dedicate connection 

* Do you have to implement connectivity to other (customer) sites? If so, how will you implement it?  
Answer: No