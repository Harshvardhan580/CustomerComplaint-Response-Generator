**Objective** : This Repository aims to Help understand Knowledge base Embedding in LLMs.

*Explanation* : 1)Finetuning a LLM allows the LLM to behave in a certain way , Knowledge base Embedding allows LLM to gain Domain Knowledge for a specific use case. 
                2)The concept of Retrieval Augmented Generation is used 
                3)We have used a Customer response dataset
                  a)This dataset acts as the knowledgebase 
                  b)For a new Customer complaint(querry) , querry would be turn to an embedding
                  c)This embedding would be sent to the knowledge base and do a Similarity Search in the existing knowledgebase
                  d)This retrieved data along with the querry is then sent to the LLM
                  e)LLM generates the most accurate response 
                4)The response generated takes reference from the previous responses to similar complaints and gives output.

**RAG Architecture :** 

![image](https://github.com/user-attachments/assets/8121018a-c956-41a0-b93f-2e237c40d2fd)

**Embedding Model:**

![image](https://github.com/user-attachments/assets/839b922a-b0c3-44f0-aade-1b2796582f31)


**Vector Databases:**

![image](https://github.com/user-attachments/assets/b54336bc-4afd-4ca2-bd35-1a6f493a1415)

