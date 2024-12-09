# Trends Marketplace Project
In this project, we leveraged the Retrieval-Augmented Generation (RAG) approach to build a chatbot for the Carlson School's website, using Gemini, a large language model developed by Google. This project showcases the benefits of RAG compared to traditional generative AI systems and explores its business applications.
 
# What is RAG?
RAG combines the power of retrieval-based methods with generative AI to provide more accurate, real-time responses by grounding outputs in external, validated data sources.

## RAG vs. Traditional Generative AI

| **Feature**            | **Traditional AI**                | **RAG**                                      |
|-------------------------|------------------------------------|---------------------------------------------|
| **Data Source**         | Static, pre-trained knowledge     | Dynamic, real-time retrieval                |
| **Accuracy**            | Prone to hallucinations           | Grounded and factually accurate             |
| **Update Frequency**    | Requires retraining for updates   | Instantly retrieves the latest information  |
| **Scalability**         | Limited without costly retraining | Easily scales with external data            |

## Benefits of RAG

| **Benefit**            | **Description**                                                                 |
|-------------------------|---------------------------------------------------------------------------------|
| **Improved Accuracy**   | Reduces hallucinations by grounding responses in real-time, validated data.    |
| **Access to Real-Time Data** | Retrieves the latest information instead of relying on static datasets.        |
| **Cost-Efficient**      | Avoids the need to retrain large models for new datasets.                      |
| **Scalability**         | Seamlessly integrates with extensive external knowledge bases.                 |

## Business Applications
Customer Support Automation: Deliver accurate, dynamic responses based on company manuals and FAQs.
Research and Analysis: Retrieve insights from large repositories for data-driven decision-making.
Content Creation: Build fact-based reports, articles, and summaries from validated sources.
Compliance and Legal Research: Ensure adherence to regulations by referencing up-to-date legal documents.
Enterprise Knowledge Management: Provide employees with quick, accurate answers from internal company documents.

## Why RAG Matters for Your Business
Competitive Edge: Enables real-time, reliable outputs, keeping businesses ahead in innovation.
Enhanced Customer Trust: Provides fact-based answers, improving credibility and confidence.
Operational Efficiency: Reduces manual effort with automated content generation and retrieval.

## How RAG Works
1. User Query: A user submits a question or request for information.
2. Retrieval Step: Relevant documents or text snippets are retrieved from a vector database.
3. Generation Step: The generative model uses the retrieved data to produce a response.
4. Output: The final response is accurate, contextually grounded, and factually reliable.

## How We Built This

We followed the **RAG (Retrieval-Augmented Generation)** approach to build a chatbot for the Carlson School’s website. Here’s the process:

1. **Data Preparation**:  
   - Collected relevant information from the website. 
   - Processed the data and embedded it into numerical vectors using an embedding model.

2. **Vector Database Setup**:  
   - Indexed the embedded vectors into a vector database for efficient retrieval.  
   - Configured the database to handle real-time search queries.

3. **Model Integration**:  
   - Connected **Gemini**, a large language model, to the vector database.  
   - Set up the system to retrieve relevant documents based on user queries dynamically.

4. **Response Generation**:  
   - Provided the retrieved data as context to the generative model.  
   - Generated accurate, contextually grounded responses tailored to the query.

5. **Demonstration**:  
   - Used **Voila** to create a user interface for showcasing the chatbot.  
   - Conducted thorough testing to ensure reliability, accuracy, and responsiveness during the demo.


**Note**: Due to the complex structure of Carlson’s website, we manually fetched data instead of using real-time methods. While this limits dynamic updates, future enhancements can incorporate API integration, automated web scraping for real-time data retrieval.


# Code & files
To run the code, upload the data files from a folder named "data" in the Colab environment and set up the necessary key.
📌[Colab](https://colab.research.google.com/drive/1_TYG8saveyjD1yY4RKJRxZfFySosIW6Q#scrollTo=sP_iDUhPOd2k)
