# Tailor Gemini: Building an Intelligent Customer Support Chatbot

This project demonstrates how to create a custom AI-driven support system using Google's Gemini API. Instead of training a model from scratch, we use Gemini's pre-trained capabilities to match customer queries with historical tickets and generate context-aware, helpful responses.

All development was done in a **Jupyter Notebook running on Anaconda**.

---

##  Why Use Gemini API Instead of Training a Model?

- **Hardware Limitations**: Training LLMs requires powerful machines; Gemini runs smoothly on a standard Windows laptop.  
- **Cost Efficiency**: Gemini's API has a free tier, making it ideal for students and small-scale developers.  
- **Pre-trained Intelligence**: The model understands queries out-of-the-box.  
- **Text Embedding**: Supports vectorization for semantic similarity matching.  
- **Scalability**: Easy to prototype and deploy.

This approach balances **cost**, **simplicity**, and **powerful NLP capabilities**, even without heavy machine learning expertise.

---

##  Dataset Used

Dataset: Customer Support Ticket Dataset  
Source: https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset

The dataset contains:
- Ticket Descriptions  
- Resolutions  
- Metadata (e.g., category, priority, customer info)

Format: CSV file

---

## API Source

Gemini API provided by **Google AI Studio**  
Free to use with a Google account.  
URL: https://aistudio.google.com/apikey

---

## Required Libraries & Installation (Anaconda PowerShell)

```bash
conda install -c conda-forge pandas
conda install -c conda-forge numpy
conda install -c conda-forge scikit-learn
conda install -c conda-forge matplotlib
conda install google-generativeai
```

---

## Environment

- **Platform**: Windows  
- **Environment**: Anaconda  
- **IDE**: Jupyter Notebook

---

## Conclusion

This notebook provides a practical guide to using a Large Language Model API (Gemini) for business-specific tone adaptation. It showcases how to fine-tune responses using historical support data, creating a helpful and professional customer experience.

The same strategy can be applied to **other datasets and industries** where tone and accuracy are important.

---

Feel free to fork, customize, and reuse this project!
