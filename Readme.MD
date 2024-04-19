Create prompt templates for LLM

Parse the LLM outputs

Maintain memory of history in a chat through Langchain

Inject additional/external context into the Chat (memory) not encountered so far in the chat

Remember just 'LAST K converstaions' instead of entire chat history to avoid sending entire conversation to LLM

Limit the number of tokens to send to LLM instead of entire chat history

Instead of limiting fixed # of token, use LLM to write the summary of conversation so far and remember the summary

Do Q/A or chat using history/memory

