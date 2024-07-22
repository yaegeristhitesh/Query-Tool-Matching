
# Query-Tool Matching

This project tackles the challenge of aligning a query with a set of tools. The problem at hand can be further divided into two sub-problems. Given a user query, which is a natural language text, the first task is to extract all the possible tools that will be required to answer that query, and the second one is that for each tool, its arguments need to be populated, i.e., argument’s value extraction. Both these tasks have their own challenges. For instance, with the second task, given an argument for a tool, its value may not be present in the current query, i.e., it may come from the execution of a previous tool. Another problem can occur in the tool extraction step itself, like how to associate one query with multiple tools that may be required to resolve it. All these problems and more are explored and resolved in our proposed solution strategy. We have created a robust query-tool matching system.


## Authors

- [Hitesh Choudhary](https://github.com/yaegeristhitesh)


## Deployment

To deploy this project, simply run the ```main.ipynb``` notebook keeping ```tool_description.json``` in correct path as mentioned in the notebook.

## Note
- To read in detail about the project please read, ```Report.pdf``` and ```Presentation.pptx```
