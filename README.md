# 🚀 AI Content Factory with n8n

## 📌 Project Overview

AI Content Factory is an end-to-end content automation workflow built with **n8n**, **Google Gemini AI**, **Google Drive**, **RSS Feeds**, and **Telegram**. It automatically discovers trending articles, performs AI-powered research, generates SEO-optimized blog posts, creates AI-generated cover images, produces platform-specific social media content, and distributes assets across multiple platforms.

Built as part of my **30-Day n8n Automation Portfolio**, this project demonstrates advanced AI workflow automation, content generation, multi-platform publishing, and digital content management.

---

## 🎯 Objectives

* Automate content research and creation
* Generate SEO-optimized blog articles with AI
* Create AI-generated cover images
* Produce platform-specific social media content
* Automate content distribution and storage

---

## 🏗️ Workflow Architecture

```text
Schedule Trigger
        │
        ▼
RSS Feed Reader
        │
        ▼
Set Article Data
        │
        ▼
AI Research Agent
        │
        ▼
AI Blog Writer
        │
        ▼
AI Image Prompt Generator
        │
        ▼
Gemini Image Generation
        │
        ▼
Google Drive Upload
        │
        ▼
AI Social Media Generator
        │
        ▼
Content Distribution
```

---

## ⚙️ Workflow Implementation

### 1. Schedule Trigger

Runs the workflow automatically at a scheduled time.

---

### 2. RSS Feed Reader

Retrieves trending articles from selected news sources.

Example sources:

* TechCrunch
* The Verge
* Hacker News
* Industry-specific blogs

---

### 3. Set Article Data

Extracts and standardizes article information, including:

* Title
* Content
* Source URL

---

### 4. AI Research Agent

Uses Google Gemini AI to analyze the article by:

* Extracting key points
* Identifying trends
* Summarizing content
* Suggesting blog angles

---

### 5. AI Blog Writer

Generates a complete SEO-friendly blog article featuring:

* H1 Title
* Introduction
* H2 Sections
* SEO-Optimized Structure
* Conclusion
* Call-to-Action

---

### 6. AI Image Prompt Generator

Creates a detailed prompt for AI image generation based on the blog content.

---

### 7. Gemini Image Generation

Generates a high-resolution cover image suitable for blog posts and social media.

---

### 8. Google Drive Upload

Uploads generated images to Google Drive for centralized storage and easy sharing.

---

### 9. AI Social Media Generator

Creates platform-specific posts for:

* Facebook
* LinkedIn
* X (Twitter)
* Telegram

---

### 10. Content Distribution

Publishes or prepares content for multiple platforms using the generated assets.

---

## 🛠️ Technologies Used

* n8n
* Google Gemini AI
* RSS Feeds
* Google Drive
* Telegram Bot API
* Facebook API (Optional)
* LinkedIn API (Optional)
* WordPress API (Optional)

---

## 📁 Repository Structure

```text
AI-Content-Factory/
│
├── README.md
├── workflow.json
│
├── screenshots/
│   ├── workflow.png
│   ├── ai-research-agent.png
│   ├── ai-blog-writer.png
│   ├── image-generation.png
│   ├── google-drive.png
│   ├── social-media-output.png
│   └── workflow-execution.png
│
└── assets/
```

---

## 📸 Screenshots

Include the following screenshots:

* Complete Workflow
* AI Research Agent
* AI Blog Writer
* AI Image Generation
* Google Drive Upload
* Social Media Output
* Workflow Execution

---

## 🚀 Key Features

* ✅ Automated Content Discovery
* ✅ AI-Powered Research
* ✅ SEO Blog Generation
* ✅ AI Image Generation
* ✅ Multi-Platform Social Media Content
* ✅ Google Drive Integration
* ✅ Automated Content Distribution
* ✅ End-to-End Workflow Automation

---

## 🎓 Lessons Learned

Through this project, I gained experience in:

* Building end-to-end AI automation workflows
* Integrating multiple AI services with n8n
* Automating SEO-focused content creation
* Designing multi-step workflow pipelines
* Managing AI-generated assets
* Automating multi-platform content distribution

---

## 📈 Impact

This workflow transforms a single trending article into a complete content package, dramatically reducing manual effort while maintaining a consistent content publishing process. It demonstrates how AI and workflow automation can streamline modern content marketing operations.

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Belio C. Sinangote**

BS Information Technology Student
Cebu Technological University (CTU)

GitHub: [https://github.com/belioautomation](https://github.com/belioautomation)

This project is part of my **30-Day n8n Automation Portfolio**, showcasing practical workflow automation using n8n, AI, APIs, and automation best practices.
