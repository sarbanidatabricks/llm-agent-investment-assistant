# llm-agent-investment-assistant

%md

This is an auto-generated notebook created by an AI Playground export. We generated three notebooks in the same folder:
- Agent: contains the code to build the agent.
- config.yml: contains the configurations.
  
- Driver: 
- Logs the agent to MLflow
- Evaluate the agent with Agent Evaluation
- Registers the agent to Unity Catalog
- Deploys the agent to a Model Serving endpoint


This notebook uses Mosaic AI Agent Framework ([AWS](https://docs.databricks.com/en/generative-ai/retrieval-augmented-generation.html) | [Azure](https://learn.microsoft.com/en-us/azure/databricks/generative-ai/retrieval-augmented-generation)) to recreate your agent from the AI Playground. It defines a LangChain agent that has access to the tools from the source Playground session.

Use this notebook to iterate on and modify the agent. For example, you could add more tools or change the system prompt.

 **_NOTE:_**  This notebook uses LangChain, however AI Agent Framework is compatible with other agent frameworks like Pyfunc and LlamaIndex.

## Prerequisites

- Address all `TODO`s in this notebook.
- Review the contents of config.yml as it defines the tools available to your agent, the LLM endpoint, and the agent prompt.

## Next steps

After testing and iterating on your agent in this notebook, go to the auto-generated driver notebook in this folder to log, register, and deploy the agent.
