# E-Commerce Chat Bot using Langchain    

The LLM-based e-commerce chatbot is a sophisticated tool designed to provide valuable information by intelligently responding to user queries. It leverages advanced language models like Google PaLM, integrated with LangChain and other essential components, to deliver efficient and relevant answers.

## Installation

1. Clone this repository to your local machine.

    bash
    git clone https://github.com/shiv-abhi77/E-Commerce-Chatbot

2. Obtain the necessary language models and data by following the guidelines provided in the Langchain documentation. Additionally, configure the paths and settings within your project, including the 'DATABASE_FAISS_PATH' variable, to suit your requirements.

## Getting Started

Follow the Steps to run the project:

1. Make sure your install required necessities according to [Langchain documentation](https://python.langchain.com/docs/integrations/vectorstores/faiss/).

2. Customize your project by adjusting the DATABASE_FAISS_PATH variable and any other specific configurations within the code.

3. Prepare the Langchain model according to documentation. 

4. You can train the bot using the injest.py file provided and changed the feeded PDF according.

5. Now to run the project
    bash
    streamlit run model.py
    
## Usage

1. Personalized Product Recommendations: Implemented a chatbot that analyzes user preferences and browsing behavior to suggest tailored product recommendations, enhancing user experience and increasing conversion rates.

2. Customer Support and FAQs: Integrated a chatbot capable of addressing common customer inquiries such as return policies, payment issues, and troubleshooting, reducing response times and lowering the volume of customer service requests.

## Technology Used

Langchain

Streamlit

Python

*LLM Model* : Google Palm
