# Ch18-Streamlit-Pychain

This project utilizes Streamlit to deploy a blockchain Web app coded in Python, utilizing dataclasses and decorators. Transaction information is hashed with hashlib and recorded to a ledger, and the ledger can be validated.

![streamlit1](https://user-images.githubusercontent.com/85848524/138997051-59c05ac1-9a44-41c4-8e1f-d5f140dd4104.PNG)

The above photo shows the transactions being written to the ledger.

![streamlit2](https://user-images.githubusercontent.com/85848524/138997190-db9669dc-36a2-402a-8264-812fc58dfbc4.PNG)

![image](https://user-images.githubusercontent.com/85848524/139159247-bd52e387-cecf-4bb7-ab12-0bde9bce939d.png)


The above photos show the validation.

There is also a difficulty slider - this increases the nonce at which the block is written (higher nonce = higher difficulty):

![image](https://user-images.githubusercontent.com/85848524/138997553-5286fbf4-53e2-4d65-b3c0-95dab33b8ea0.png)
![image](https://user-images.githubusercontent.com/85848524/138997571-265e5aaf-12d5-45e7-a44d-0721e840fe25.png)
