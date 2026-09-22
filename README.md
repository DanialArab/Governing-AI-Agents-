# Governing-AI-Agents-

## Intro

We can define a set of tools for the agent that allow it to ingest data such as customer demographics, transactions, website engagement, and survey responses.

If you give the agent broad permissions to all this data, you risk it leaking private customer information, such as credit card details, addresses, or personal purchasing behavior—data that should not be visible to all company employees.

However, if you build the agent with data governance in mind, you can ensure it handles this data properly. For example, in the deployment environment, you can specify which tables or columns the agent can access, encrypt customer IDs, and mask credit card information.

You can also implement data-quality checkpoints for the agent’s inputs and outputs, add evaluations to measure output quality, and enable observability to log the agent’s processing steps. These practices allow you to continuously monitor the agent’s behavior and debug failure scenarios.

In this course, you will learn how to apply these governance practices to an agent that you will build and deploy on Databricks.

To ensure the agent follows the principle of least-privilege access, you will give it specific, intentional access through **views**. These views—which are SQL queries that function like tables—will contain only the data required for the agent’s task.

For the agent to access these views, you will learn how to define its permissions. You will then build tools that allow the agent to access the data and register those tools as functions in **Unity Catalog**. Unity Catalog is an open-source data catalog that ensures only authorized agents or users can access those tools.

Next, you will implement the agent’s logic using the OpenAI SDK, evaluate it, and enable tracing with MLflow. Finally, you will deploy the agent.

![]()<img width="1612" height="802" alt="image" src="https://github.com/user-attachments/assets/46746f5f-da52-45a3-8a3b-678966af4410" />

![]()<img width="1659" height="778" alt="image" src="https://github.com/user-attachments/assets/e5519e3d-db6c-4c64-ada1-dbb34ba04877" />

![]()<img width="1483" height="751" alt="image" src="https://github.com/user-attachments/assets/fa1bb52d-dc78-4e45-82a9-8ea1ee5bbecc" />

![]()<img width="1552" height="738" alt="image" src="https://github.com/user-attachments/assets/9db1ae88-f7ad-49b8-91b3-8f8f51392608" />

![]()<img width="1589" height="700" alt="image" src="https://github.com/user-attachments/assets/19e84607-bfa9-4941-ba5f-6b52773356aa" />

![]()<img width="1553" height="643" alt="image" src="https://github.com/user-attachments/assets/0ee75354-a497-4396-b5be-0ddc2432844c" />


![]()<img width="1539" height="639" alt="image" src="https://github.com/user-attachments/assets/dd08d595-1e66-48fb-a9c1-b4a2240f44be" />

![]()<img width="1567" height="639" alt="image" src="https://github.com/user-attachments/assets/87a9edf2-9c32-4148-a65a-b066ba8f5fd0" />
