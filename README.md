# Generative AI on Google Cloud

Welcome to the Generative AI repository on Google Cloud!

This repository is a showcase of cutting-edge Generative AI capabilities on Google Cloud, specifically powered by Vertex AI. Whether you're an AI enthusiast, developer, or data scientist, you'll find a wealth of resources here, including notebooks, code samples, sample apps, and other materials that not only demonstrate but empower you to leverage the full potential of generative AI workflows.

## Why Explore Generative AI on Google Cloud?

- **Innovative Solutions:** Explore and implement innovative solutions using state-of-the-art generative AI models.
- **Efficient Workflows:** Learn how to develop and manage generative AI workflows seamlessly with Google Cloud's powerful Vertex AI platform.
- **Real-World Applications:** Gain insights into practical applications of generative AI across various industries.

## Before You Start
1. Create new project in Google Cloud Platform
2. Enable Generative Language API
2. Create new service account and add 'Vertex AI User' role
3. Download the service account key as json (IAM & Admin > Service Accounts > Actions > Manage Keys > Add Key > Create new key)

### Required Libraries
Make sure your environment has been installed following:
* `pandas`
* `numpy`
* `google-cloud-aiplatform`
* `google-auth`
* `langchain`
* `FAISS`
* `ChromaDB`

## Getting Started

To dive into the world of Generative AI on Google Cloud, check out the following sections:

### 1. Clone the repository:

```bash
git clone https://github.com/ridwanspace/palm-ai-notebook.git
```

### 2. Install dependencies:

```bash
cd palm-ai-notebook
pip install -r requirements.txt
```

### 3. Add credentials:

- create `.env` and insert your Google Cloud `PROJECT_ID`
- move downloaded service account (json) into the root folder

### 4. Notebooks

- [Getting Started](/get-started): Hands-on examples and tutorials to guide you through various generative AI concepts in Vertex AI within Google Cloud Platform.
- [Prompt](/prompt): Learn best practices around prompt engineering -- How to design prompts to improve the quality of your responses
- [Code](/code-generation): Interact with a chatbot for assistance with code-related tasks, including debugging, documentation, and learning new concepts
- [Langchain](/langchain): It will cover what Langchain is and how to integrate it into our code.
-[Gemini](/gemini): Notebook for interacting with Gemini models, Google's latest model.


## Connect with Us

- [LinkedIn](https://www.linkedin.com/in/muhammad-ridwan-0136181a9/)
- [Website](https://www.theridwanspace.com)

Happy coding and exploring the fascinating world of Generative AI!

