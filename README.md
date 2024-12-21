![friendly-chatbot](https://github.com/user-attachments/assets/e334e9dd-31bc-4cc7-bb59-0ad53f2740ab)

Bot Description :-
Lite version with efficient and fast response to provided CSV files. User can query about any data that is present in the CSV file (eg:- row-column information, aggregate data, complex calculations). The bot is built using Langchain agent along with OpenAI LLM model. Feel free to experiment with this model and scope for tuning available.


Tools required :-
tabulate - 0.9.0
langchain - 0.3.12
langchain_experimental - csv_agent
langchain-openai - ChatOpenAI
langchain_experimental.agents.agent_toolkits - pandas_dataframe_agent


NOTE : Th langchain_experimental is a temporary dependency as langchain community is working on building new updates on the same. Future releases may render the toolkit unavailable. Check https://python.langchain.com/v0.2/api_reference/experimental/index.html for more information.
