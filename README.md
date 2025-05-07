# Catholic-chatbot
A gpt style chatbot that will answer Catholic questions based on the Catechism &amp; the Bible, that calls OpenAI to complete the requests but with the restriction of only using the Catechism of the Catholic Church and the Bible as references. (Future versions may also reference homilies and other documents from church fathers and doctors of the Church)

# CRUD Implementation
Using a CRUD to make requests and then putting each question asked into DynamoDB and referencing it if the same question is asked to mitigate calls to OpenAI. Future improvements will include adding semantic similarity function to make even less calls to OpenAI.
