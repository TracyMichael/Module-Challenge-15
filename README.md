# Module-Challenge-15

---

## Technologies (AWS Lex and AWS Lambda)


The Application has specific technologies that will be needed to run properly.


**Amazon Web Services:** *AWS Lex & AWS Lambda*

**Languages Required:** *Python*

**Libraries Required:** *Datetime, dateutil, botocore*

Before running the application the following Libraries will need to be imported:

```python
from datetime import datetime
from dateutil.relativedelta import relativedelta
from botocore.vendored import requests
```


---

## Installation Guide

No Installations required as this applicaiton will work in Amazon Web Services using Lambda and Lex.  An account will have to be created to use Amazon Web Services.

To start using AWS, you need to create an account. Although doing this is free, you need to provide a valid credit card that allows Amazon to charge for any service usage beyond the limits of the free tier. The details for each free offer are constantly updated, so it’s a good idea to check the latest terms on the [AWS Free Tier](https://aws.amazon.com/free/free-tier/) site. Subscriptions Details are as follows:


Amazon Lex (12 months free):

   1. 10,000 text requests per month
   2. 5,000 speech requests per month

AWS Lambda (always free):
    
   1. 1 million free requests per month
   2. Up to 3.2 million seconds of compute time per month

---

## Usage


### **For Coders:** 

1. In Amazon Lex, enter in data for Sample Utterances, Slots, and Confirmation Prompts as desired.
2. In Lamda, build code that will read the detail from Lex and create code that will make the chatbot communicative.
3. Activate the Lambda Function for Lambda initialization and validation and Fulfilment.  Choices should be aligned with the folder name and the latest version.
 
4. Deploy the Lambda Function
5. Build the Lex Application
6. Test the chatbot and publish.

### **For Users:** 

The application is built to create a trading bot using Machine Learning

1. Ask the ChatBot one of the following quetions:

    1. I want to save money for my retirement
    2. I'm {age} and I would like to invest for my retirement
    3. I'm ​{age} and I want to invest for my retirement
    4. I want the best option to invest for my retirement
    5. I'm worried about my retirement
    6. I want to invest for my retirement
    7. I would like to invest for my retirement
2. Answer the remaining questions pertaining to age, investment amount, and risk aversion desire.

---

## Contributors

Tracy Davis <TracyMDavis88@gmail.com>

[Tracy Davis LinkedIn](https://www.linkedin.com/in/tracy-davis-mba-ma-2940a232/)

---

## License

MIT License

Copyright (c) [2022] [Tracy Davis]









