# Governing-AI-Agents-

We can define a set of tools for the agent that allow it to ingest data such as customer demographics, transactions, website engagement, and survey responses.

If you give the agent broad permissions to all this data, you risk it leaking private customer information, such as credit card details, addresses, or personal purchasing behavior—data that should not be visible to all company employees.

However, if you build the agent with data governance in mind, you can ensure it handles this data properly. For example, in the deployment environment, you can specify which tables or columns the agent can access, encrypt customer IDs, and mask credit card information.

You can also implement data-quality checkpoints for the agent’s inputs and outputs, add evaluations to measure output quality, and enable observability to log the agent’s processing steps. These practices allow you to continuously monitor the agent’s behavior and debug failure scenarios.

In this course, you will learn how to apply these governance practices to an agent that you will build and deploy on Databricks.

To ensure the agent follows the principle of least-privilege access, you will give it specific, intentional access through **views**. These views—which are SQL queries that function like tables—will contain only the data required for the agent’s task.

For the agent to access these views, you will learn how to define its permissions. You will then build tools that allow the agent to access the data and register those tools as functions in **Unity Catalog**. Unity Catalog is an open-source data catalog that ensures only authorized agents or users can access those tools.

Next, you will implement the agent’s logic using the OpenAI SDK, evaluate it, and enable tracing with MLflow. Finally, you will deploy the agent.
