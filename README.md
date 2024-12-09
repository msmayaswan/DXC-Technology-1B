1. Project Title and Description - Break Through Tech AI Fall Studio - DXC Technology 1B

Purpose: 
  Navigate the EU AI Act by developing a chatbot that understands the EU AI Act, and specifcally focuses on Natural Language Processing (NLP) and Retrieval-Augmented Generation (RAG). 
  Implement a multi-agent approach for effective prompt engineering and risk assessment, ensuring the chatbot aligns with EU AI regulations.

  To accomplish this task, used pdfplumber to load and extract text and tables from the PDF. Retrieved structured (tables) and unstructured (text) data.
  Tokenization converted text to lowercase and removed special characters and stopword removal filtered out common stopwords for meaningful word frequency analysis.

  We used spaCy to clean and preprocess the text by removing stop words and punctuation. The documents were then chunked into smaller, manageable pieces and converted
  into high-dimensional vectors using Cohere's API. These vectors were indexed with hnswlib for efficient retrieval. Finally, a retrieval-augmented generation (RAG)
  approach combined vector search with AI-generated responses to provide context-aware answers.

  The model was evaluated by comparing our outputs to other AI models like ChatGpt. While our model excels in accuracy, it lacks detail, structure, and contextual clarity,
  whereas ChatGPT provides clear, detailed, and easy-to-understand answers that cover all important points and add thoughtful insights for deeper understanding.

  To improve our model's accuracy in the future, we plan to use the F1 score, which balances precision and recall, while also considering the subjectivity involved in observational studies.


2. License - Apache License 2.0

3. Credits and Acknowledgments
   Team Members: Maya Swan, Nandini Shah, Gianelli Lagos, Pa Yang
   TA: Aditya Ballaki
   Challenge Advisor: Tahereh Mazaheri Kouhani
