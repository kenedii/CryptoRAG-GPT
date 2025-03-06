# CryptoGPT: Your Crypto Knowledge Companion 🚀

Welcome to **CryptoGPT**, a cryptocurrency-focused chatbot powered by a Retrieval Augmented Generation (RAG) model. Forked from the [Azure OpenAI and AI Search demo](https://github.com/Azure-Samples/azure-search-openai-demo), this project has been transformed to deliver insightful answers about cryptocurrencies!

## What Does It Do? 🤔

CryptoGPT uses Azure OpenAI and AI Search to help you explore the crypto world. Ask about blockchain basics, coin details, or historical prices—it’s designed to inform and educate, whether you’re a newbie or a pro.

## Key Features 🌟

- **Crypto Q&A**: From "What’s Bitcoin?" to "How do smart contracts work?"
- **Price History**: Insights into past crypto prices (with some limitations).
- **Simple or Technical**: Answers tailored to your expertise level.
- **Unbiased**: Objective info from a wide range of sources.

## The Data 📚

Trained on 165 PDF files (~474 MB), including:
- Crypto white papers
- Case studies & research papers
- Websites with crypto info
- Historical price data from Yahoo Finance

## How It’s Built 🛠️

- **Training**: Powered by Microsoft Azure’s Search Service and Document Intelligence to process PDFs.
- **Deployment**: Super easy with the `azd up` command.

## How Well Does It Work? 📊

CryptoGPT shines at explaining concepts and stays mostly unbiased. It handles simple and technical questions well.

## Try It Out 💻

Visit the [deployed app]([https://app-backend-ittvceuzgph3y.azurewebsites.net/) to start asking questions!  
Want to run it locally?  
1. Clone this repo.  
2. Set up Azure credentials.  
3. Run `azd up` and follow the prompts.
