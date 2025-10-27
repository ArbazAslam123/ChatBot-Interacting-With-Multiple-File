Overview 

Multi File AI Assistant is an intelligent chatbot built using LangChain that allows users to interact with multiple types of documents simultaneously. The assistant can understand and extract information from PDF, CSV, and TXT files, enabling users to ask natural language questions about their uploaded files and receive accurate, AI-generated responses. 

This project demonstrates the power of Retrieval-Augmented Generation (RAG), where the chatbot uses embeddings to understand the context of various document types and provides relevant answers based on the uploaded content. 

 

Tools & Technologies Used 

    LangChain – Framework for building context-aware AI applications 

    Python – Core programming language 

    FAISS – For vector-based retrieval and similarity search 

    Hugging Face / Groq API – Language model integration 

    Gradio – For building an interactive web-based user interface 

 

How It Works 

    File Upload: 
    Users can upload files in formats such as PDF, CSV, or TXT. 

    Document Processing: 
    The system extracts text content from the uploaded files and divides it into smaller, meaningful chunks. 

    Embedding Generation: 
    Each chunk is converted into numerical vectors (embeddings) and stored in a  vector database. 

    Question Answering: 
    When users ask a question, the model searches through the stored embeddings to find relevant text and generates an intelligent, context-based answer. 

    User Interaction: 
    The chatbot interface allows users to seamlessly interact with their own documents in real time. 

 

Example Use Case 

A user uploads: 

    A PDF containing a company report, 

    A CSV containing sales data, and 

    A TXT file with meeting notes. 

They can then ask questions like: 

“What were the total sales in 2023?” 
“Summarize the key points from the meeting notes.” 
“Who are the top-performing departments according to the report?” 

The AI assistant will read all uploaded documents and generate accurate responses from them. 

 

Conclusion 

The Multi File AI Assistant showcases how AI and LangChain can work together to simplify information retrieval across different file types. By integrating multiple document formats and a conversational interface, it offers a powerful solution for anyone needing quick insights from diverse data sources. 

 
