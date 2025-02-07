## # RAG & LangChain Mastery Course forked from whyashthakker

Transform your development skills with this comprehensive course on **Retrieval-Augmented Generation (RAG)** and **LangChain**. Whether you're a developer looking to break into AI or an experienced programmer aiming to master RAG, this course offers the perfect blend of theory and hands-on practice to help you build production-ready AI applications.

## About This Repository

This repository is a fork of the original project created by **[Whyash Thakker](https://github.com/whyashthakker)**. All credit for the initial work goes to them. You can find the original repository here: [RAG by Whyash Thakker](https://github.com/whyashthakker/RAG).

### Changes in This Fork
- [Briefly describe any changes or additions you've made, if applicable.]
- For example: "Added support for AWS deployment and updated the dependencies."

---

## What You'll Learn
- Build **three professional-grade chatbots**: Website, SQL, and Multimedia PDF.
- Master **RAG architecture** and implementation from fundamentals to advanced techniques.
- Run and optimize both **open-source** and **commercial LLMs**.
- Implement **vector databases** and **embeddings** for efficient information retrieval.
- Create sophisticated AI applications using the **LangChain framework**.
- Deploy advanced techniques like **prompt caching** and **query expansion**.

## Course Content
1. **RAG Fundamentals**: Architecture, components, and best practices.
2. **Large Language Models (LLMs)**: Hands-on practice with open-source LLMs and optimization.
3. **Vector Databases & Embeddings**: FAISS, ANNOY, HNSW, and Pinecone integration.
4. **LangChain Framework**: Text chunking, chain composition, and integration with vector stores.
5. **Advanced RAG Techniques**: Query expansion, re-ranking, prompt caching, and performance optimization.
6. **Building Production-Ready Chatbots**: Website, SQL, and Multimedia PDF chatbots.

## Who This Course is For
- Software developers looking to specialize in AI applications.
- AI engineers wanting to master RAG implementation.
- Backend developers interested in building intelligent chatbots.
- Technical professionals seeking hands-on LLM experience.

## Prerequisites
- Basic Python programming knowledge.
- Familiarity with REST APIs.
- Understanding of basic database concepts.
- Basic understanding of machine learning concepts (helpful but not required).

## Why Take This Course?
- Gain **industry-relevant skills** in high demand.
- Hands-on experience with **real-world examples**.
- Practical implementation using **Tesla Motors database**.
- Learn **production-ready code** and best practices.

## What You'll Build
By the end of this course, you'll have built:
- Three professional-grade chatbots.
- Practical experience with RAG systems, vector databases, LLM optimization, and advanced retrieval techniques.

### Getting Started
To get started with the course, clone this repository and follow the instructions below.

#### Running the Project Locally

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to the project directory
cd your-repo-name

# Create a virtual environment
python3.11 -m venv myenv

# Activate the virtual environment
source myenv/bin/activate

# Install required packages
pip install requests beautifulsoup4 langchain langchain-openai faiss-cpu numpy lxml openai

# Upgrade pip
pip install --upgrade pip

# Install dependencies from requirements.txt
pip install -r requirements.txt

# Deploying on AWS EC2

    Launch EC2 Instance:

        Go to the Amazon AWS console and search for "EC2".

        Click on "Launch Instance".

        Provide a name for your instance.

        Select the instance type that suits your needs.

    Configure Network Settings:

        Click on "Edit" in the Network Settings section.

        Add a security group rule with port range 8501 and set the source type to "Anywhere".

        Click on "Launch Instance".

    Connect to Your Instance:

        Once the instance is launched, click on the instance ID.

        Click on "Connect".

    Set Up the Environment on EC2:
    
    # Switch to superuser
sudo su

# Install git
yum install git

# Install Python3 and pip
yum install python3-pip

# Clone your repository
git clone <your_repo_link>

# Navigate to the project directory
cd <directory_name>

# Create a Python virtual environment
python3 -m venv myenv

# Activate the virtual environment
source myenv/bin/activate

# Install necessary libraries
pip install --no-cache-dir streamlit sentence-transformers pinecone-client openai==0.28 pdfplumber

    Configure and Run Your Application:
# Edit your Python file to add your API key
nano <Your_pythonfile.py>

# Run your script
streamlit run <Your_pythonfile.py>

# For continuous running of the instance even after closing the tab
nohup python3 -m streamlit run <Your_pythonfile.py> &
```