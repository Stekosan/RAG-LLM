## # RAG & LangChain Mastery Course

Transform your development skills with this comprehensive course on **Retrieval-Augmented Generation (RAG)** and **LangChain**. Whether you're a developer looking to break into AI or an experienced programmer aiming to master RAG, this course offers the perfect blend of theory and hands-on practice to help you build production-ready AI applications.

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
To get started with the course, clone this repository and follow the instructions in the course materials.

```bash
git clone https://github.com/your-username/your-repo-name.git


# Running the project

python3.11 -m venv myenv

source myenv/bin/activate

pip install requests beautifulsoup4 langchain langchain-openai faiss-cpu numpy lxml openai

pip install --upgrade pip

pip install -r requirements.txt

# AWS Deployment Guide

This guide walks you through the process of deploying your application on an AWS EC2 instance.

## 1. Launch EC2 Instance

1. Go to the Amazon AWS console and search for "EC2".
2. Click on "Launch Instance".
3. Provide a name for your instance.

<details>
<summary>View Screenshot</summary>

![Step 1](STEPS/1.jpg)

</details>

4. Select the instance type that suits your needs.

<details>
<summary>View Screenshot</summary>

![Step 2](STEPS/2.jpg)

</details>

## 2. Configure Network Settings

1. Click on "Edit" in the Network Settings section.

<details>
<summary>View Screenshot</summary>

![Step 3](STEPS/3.jpg)

</details>

2. Click on "Add security group rule".

<details>
<summary>View Screenshot</summary>

![Step 4](STEPS/4.jpg)

</details>

3. Add port range 8501 and set the source type to "Anywhere".
4. Click on "Launch Instance".

<details>
<summary>View Screenshot</summary>

![Step 5](STEPS/5.jpg)

</details>

## 3. Connect to Your Instance

1. Once the instance is launched, click on the instance ID.

<details>
<summary>View Screenshot</summary>

![Step 6](STEPS/6.jpg)

</details>

2. Click on "Connect".

<details>
<summary>View Screenshot</summary>

![Step 7](STEPS/7.jpg)

</details>

## 4. Set Up the Environment

1. In the CLI, change to superuser:
   ```
   sudo su
   ```

2. Install git:
   ```
   yum install git
   ```

<details>
<summary>View Screenshot</summary>

![Step 8](STEPS/8.jpg)

</details>

3. Install Python3-pip:
   ```
   yum install python3-pip
   ```

<details>
<summary>View Screenshot</summary>

![Step 9](STEPS/9.jpg)

</details>

4. Clone your repository:
   ```
   git clone <your_repo_link>
   ```

5. Create a Python virtual environment:
   ```
   python3 -m venv myenv
   ```

<details>
<summary>View Screenshot</summary>

![Step 10](STEPS/10.jpg)

</details>

6. Install necessary libraries:
   ```
   pip install --no-cache-dir streamlit sentence-transformers pinecone-client openai==0.28 pdfplumber
   ```

<details>
<summary>View Screenshot</summary>

![Step 11](STEPS/11.jpg)

</details>

## 5. Configure and Run Your Application

1. Change directory to your repo:
   ```
   cd <directory_name>
   ```

2. Edit your Python file to add your API key:
   ```
   nano <Your_pythonfile.py>
   ```

<details>
<summary>View Screenshot</summary>

![Step 12](STEPS/12.jpg)

</details>

3. Run your script:
   ```
   streamlit run <Your_pythonfile.py>
   ```

4. For continuous running of the instance even after closing the tab:
   ```
   nohup python3 -m streamlit run <Your_pythonfile.py> &
   ```

<details>
<summary>View Screenshot</summary>

![Step 13](STEPS/13.jpg)

</details>

Congratulations! Your application should now be deployed and running on AWS EC2.

