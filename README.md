# 🚀 n8n AI Automation Portfolio

This repository contains advanced AI automation workflows built with n8n. These projects demonstrate my ability to build autonomous agents that handle complex tasks like video generation and customer support.

---

## 📁 Project 1: Autonomous AI YouTube Content Creator
**File:** `project1_youtube_creator.json`

**What it does:** 
An autonomous AI agent that researches selected content, generates a script, creates a voiceover, assembles a video, and automatically uploads it to YouTube on a schedule. 

**Key Features:**
- **Scheduled Trigger:** Runs automatically without human intervention.
- **AI Scripting:** Uses AI to generate engaging video scripts based on the selected topic.
- **Text-to-Speech Integration:** Converts the script into natural-sounding audio.
- **Video Assembly:** Combines visuals and audio into a final video format.
- **YouTube API:** Directly uploads the finished video to YouTube with proper metadata.

**Tech Stack:** n8n, HTTP Requests, JavaScript, AI APIs, YouTube API.

---

## 📁 Project 2: AI E-Commerce Customer Support Agent
**File:** `project2_ecommerce_support.json`

**What it does:**
An intelligent AI chatbot designed for online stores. It acts as a virtual sales assistant and support agent, handling customer queries 24/7.

**Key Features:**
- **Product Knowledge:** Understands the store's inventory and product details.
- **Order Assistance:** Explains how customers can place orders and guides them through the process.
- **Customer Chat:** Provides real-time, conversational answers to customer questions.
- **Memory:** Remembers the context of the conversation for a natural experience.

**Tech Stack:** n8n, AI Agent Node, OpenRouter (LLM), Google Sheets (Product Database), Memory Node.

---

## 🛠️ How to Import These Workflows
1. Download the `.json` file of the project you want to use.
2. Open your n8n instance.
3. Go to **Workflows** -> **Import from File**.
4. Select the JSON file.
5. Add your own credentials (API keys, Google Sheets tokens, YouTube OAuth) and activate the workflow.