This Project uses Chainlit, and GPT to perform question answering on a selected document. The model also returns the section of input document which was the most similar to the input query. 
This is how the application looks, where there is an option to upload a document. When a document is uploaded, it is partitioned into various sections and stored in a database.

![Input Image](Input%20Template.png)

This is an example of how the Chainlit application works. When a question is asked, the model queries the document and uses the sections of the document that are close to the input query. These sections can also be seen in the application.
![Result Image](Result%20Template.png)

Start the application by installing the requirements and run the command: chainlit run document_qa.py -w
This will start the application on [port 8000 ](http://localhost:8000)http://localhost:8000
