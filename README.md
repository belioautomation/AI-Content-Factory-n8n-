# 🚀 AI Content Factory

<p align="center">

![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google-gemini&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google_Drive-34A853?style=for-the-badge&logo=googledrive&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

<p align="center">
An end-to-end AI-powered content automation workflow built with <strong>n8n</strong> that automatically discovers trending topics, performs AI research, generates SEO-optimized blog articles, creates AI image prompts, produces social media content, and stores generated assets for publishing.
</p>

---

# 📖 Overview

## Problem

Creating high-quality content consistently requires significant manual effort. Content creators often spend hours researching topics, writing articles, designing visuals, and preparing social media posts before publishing.

## Solution

AI Content Factory automates the entire content production pipeline using n8n and AI services. From discovering trending topics to generating publish-ready content, the workflow reduces repetitive work while maintaining a structured content creation process.

---

# ✨ Features

### 📰 Content Discovery

- Discover trending articles from RSS feeds
- Collect article metadata automatically
- Extract relevant content for AI analysis

### 🤖 AI Content Generation

- AI-powered topic research
- SEO-optimized blog generation
- AI-generated image prompts
- Social media caption generation

### 📁 Asset Management

- Automatically upload generated assets to Google Drive
- Organize files into structured folders
- Archive generated content

### 📢 Notifications

- Send workflow completion notifications to Telegram
- Monitor automation progress

---

# 🏗 Workflow Architecture

```text
Schedule Trigger
        │
        ▼
RSS Feed Reader
        │
        ▼
Prepare Article Data
        │
        ▼
AI Research Agent
        │
        ▼
SEO Blog Generator
        │
        ▼
Image Prompt Generator
        │
        ▼
AI Image Generation
        │
        ▼
Google Drive Upload
        │
        ▼
Social Media Generator
        │
        ▼
Telegram Notification
```

---

# 📸 Workflow Screenshot

![Workflow](Workflow%20Image)

---

# 🛠 Tech Stack

### Workflow Automation

- n8n

### AI

- Google Gemini AI

### APIs & Integrations

- RSS Feed
- Google Drive API
- Telegram Bot API

### Programming

- JavaScript

---

# 📂 Repository Structure

```text
AI-Content-Factory/

├── README.md
├── workflow.json
├── workflow.png
└── LICENSE
```

---

# ⚙️ Setup Guide

## 1. Clone Repository

```bash
git clone https://github.com/belioautomation/AI-Content-Factory-n8n.git
```

---

## 2. Import Workflow

Import the included workflow JSON into your n8n instance.

```
AI Content Factory.json
```

---

## 3. Configure Credentials

Configure the following credentials inside n8n:

- Google Gemini API
- Google Drive OAuth2
- Telegram Bot
- RSS Feed

---

## 4. Update Configuration

Modify:

- RSS feed sources
- Google Drive destination folders
- Telegram Chat ID
- AI prompts (optional)

---

## 5. Activate Workflow

Once credentials are configured, activate the workflow.

---

# 📊 Example Workflow

```
Trending Article

↓

AI Research

↓

SEO Blog

↓

Image Prompt

↓

AI Cover Image

↓

Google Drive Upload

↓

Social Media Content

↓

Telegram Notification
```

---

# 💡 Skills Demonstrated

- AI Workflow Automation
- Prompt Engineering
- SEO Content Generation
- Google Workspace Automation
- API Integration
- JavaScript Data Transformation
- Digital Asset Management
- Multi-step Business Automation

---

# 🔮 Future Improvements

- WordPress auto publishing
- LinkedIn publishing
- Facebook publishing
- AI SEO scoring
- AI plagiarism detection
- Content performance analytics
- Multi-language support

---

# 👨‍💻 Author

**Belio C. Sinangote**

BS Information Technology Student  
Cebu Technological University

GitHub:
https://github.com/belioautomation

---

# 📄 License

This project is licensed under the **MIT License**.
