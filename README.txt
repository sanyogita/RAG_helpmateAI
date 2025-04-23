This folder contains a Jupyter notebook containing our helpmate project.
Here I have collected two documents regarding GDP.
2011-12 to 2022-23 financial year taken from [data.gov](https://www.data.gov.in/high-value-datasets?sortby=resource_node_rating) 
and press note from [mospi.gov](https://www.mospi.gov.in/sites/default/files/press_release/PressNoteQ4_FY2022-23_31may23.pdf).

We have used llamaIndex to execute our RAG system. Because it'92s ease of implementation and variable document readers easily available.
In data directory we have both the documents one of them is civ while other is pdf. Index is filled with both the documents and embedding are stored in .storage directory. 
This chatbot asks user to provide relevant questions suitable for nature of data.
Some example questions are provided in notebook.
1. What industry is showing most growth in last decade?
2. What is the region which requires most attention in point of financial growth?
3. What are different indicators of GDP?
This project is explained further with report in docs format with helpmate_ai.docx