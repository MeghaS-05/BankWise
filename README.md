# BankWise

 The **Banking Knowledge Assistant** is an AI-powered application that allows users to ask questions about banking policies, procedures, and other banking-related information. It uses uploaded documents as its knowledge base and provides relevant, context-aware answers through a conversational interface.

 ### Working

 1. Users log in and access features based on their roles.
2. Authorized users can upload banking-related documents.
3. Documents are processed and converted into embeddings, which are stored in a vector database.
4. When a user asks a question, the system retrieves the most relevant information from the stored documents.
5. The retrieved information is provided to the LLM to generate an accurate, context-aware response.
6. Conversations are stored so users can view their previous interactions.

 ### Tech Stack

 - **Frontend:** React
- **Backend:** Spring Boot
- **Database:** PostgreSQL
- **Vector Database:** Vector DB
- **AI/LLM:** LLM with RAG
- **APIs:** REST APIs
- **Deployment:** Docker
- **Testing:** Unit & Integration Testing
- **Additional:** Authentication, Role-Based Access Control, Logging & Error Handling
