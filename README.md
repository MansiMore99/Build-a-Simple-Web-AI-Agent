## 🤖 Learning Recommender AI Agent

A beginner-friendly project where we build a simple **AI agent** to recommend learning resources using **web scraping** 🌐 and **OpenAI** 🧠.

This agent collects data about Deep Learning courses (title, description, company, image, link), and uses OpenAI's LLM to filter and present them based on a given topic, like `"Retrieval Augmented Generation (RAG)"`.

---

## 🚀 Features

- 🕸️ Scrape course information from websites  
- 🧠 Use OpenAI to generate structured and relevant results  
- 🎯 Filter courses by custom topic using prompts  
- 📸 Capture screenshots of each course page  
- 🗂️ Organize data with titles, descriptions, companies, images, and URLs  

---

## 🧠 Use Case Examples

### ✅ Example 1: Scrape All Courses  
- Extracts all Deep Learning courses from the website  
- Captures:  
  - 📌 Title  
  - 📝 Description  
  - 🏢 Company  
  - 🖼️ Image URL  
  - 🔗 Course Link  
  - 🖼️ Full-page Screenshot

### ✅ Example 2: Filter by Subject (e.g. "RAG")  
- Uses OpenAI to **filter out only the courses related to a specific topic**
- Custom prompt controls the number and relevance of results

```
subject = "Retrieval Augmented Generation (RAG)"

instructions = f"""
Read the description of the courses and only 
provide the three courses that are about {subject}. 
Make sure that we don't have any other
courses in the output.
"""
```


<p align="center">
  <img src="https://yourdomain.com/banner.png" alt="Learning Recommender AI Agent" width="100%">
</p>

<h1 align="center">🤖 Learning Recommender AI Agent</h1>

<p align="center">
  A beginner-friendly AI agent that scrapes course content and uses OpenAI to recommend topics like "RAG" 💡
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.8+-blue" />
  <img src="https://img.shields.io/badge/openai-powered-brightgreen" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  <img src="https://img.shields.io/badge/made%20with-jupyter-orange" />
</p>

---

## 🧠 Overview

This project builds a simple AI agent that:
- Scrapes Deep Learning course details from websites
- Captures screenshots of the pages
- Uses OpenAI to filter and recommend courses based on a given topic (e.g., **RAG**)

Perfect for learning how to use:
- Web scraping with Python
- Prompting OpenAI models
- Organizing structured outputs

---

## 🚀 Quick Start



### 🧰 Local Installation

```bash
git clone https://github.com/your-username/AI Agent.git

cd learning-recommender-agent

pip install -r requirements.txt

AI Agent.ipynb
```
