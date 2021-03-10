<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI based probability of defaul

Final project for the Building AI course


## Summary

My AI idea focuses on estimating the probability of default of a bank's customer based on the customer characteristics, lending and payment behaviour. The model would continously update itself as more data is gathered on current customers (payment behaviour data such as payment delays etc.) new customers come in (customer characteristics such as age, sex, zip code, occupation, etc.).


## Background

My idea would solve the problem of having to manually update certain IFRS9-related risk models. In the banking world this problem is rather frequent and requires quite a bit of human resources to follow up and update the probability of default models.


## How is it used?

The model would have to be implemented in the bank's system. The solution would be used all the time as the data keeps evolving. The users would be the risk and finance departments of the bank.


## Data sources and AI methods

The data would come from the bank's database and from a credit bureau (Asiakastieto etc.). The data is collected at the time of the application from the credit bureau and the internal payment behaviour data is collected continuously as long as the customer has a credit with the bank.


## Challenges

As the model would continously keep developing itself it might be somewhat difficult to clarify the way the probability of default was calculated at each point in time to the financial authorities. It would be important to make sure that no discriminatory variables such as race, religion etc. would be used in the model.


## What next?

To actually implement such a model in the real world I would need to significantly increase my knowledge about implementing AI solutions and improve my coding skills.


## Acknowledgments

The Building AI course.
