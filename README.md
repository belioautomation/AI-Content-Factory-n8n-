# 🚀 AI Content Factory — n8n Automation

![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![Google Gemini](https://img.shields.io/badge/AI-Google%20Gemini-blue)
![Google Drive](https://img.shields.io/badge/Storage-Google%20Drive-green)
![JavaScript](https://img.shields.io/badge/Code-JavaScript-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

An end-to-end AI content automation workflow built using **n8n**, **Google Gemini AI**, **RSS Feeds**, **Google Drive**, and **Telegram Bot API**.

This system automatically discovers trending topics, performs AI-powered research, generates SEO-optimized blog content, creates AI-generated cover images, produces social media content, and organizes generated assets for multi-platform publishing.

**Stack:**  
n8n · Google Gemini AI · RSS Feed · Google Drive · Telegram Bot · JavaScript · AI Automation


---

# 🎯 Project Overview


## Problem

Creating high-quality digital content requires significant time and manual effort.

Common challenges include:

- Finding relevant trending topics
- Researching articles manually
- Writing SEO-friendly blog posts
- Creating visual assets
- Preparing social media content
- Managing content distribution


For content creators and businesses, maintaining a consistent publishing workflow can become difficult.


---

## Solution

This project creates an automated AI content production pipeline by:


1. Discovering trending articles automatically
2. Extracting article information
3. Performing AI-powered research
4. Generating SEO-optimized blog posts
5. Creating AI-generated cover images
6. Uploading assets to Google Drive
7. Generating social media content
8. Preparing content for distribution


The workflow acts as an AI-powered content assistant that transforms a single article into a complete digital content package.


---

# ✨ Features


## Content Discovery

✅ Automated RSS feed monitoring  
✅ Trending article collection  
✅ Article data extraction  
✅ Automated topic discovery  


## Artificial Intelligence

✅ Google Gemini AI research  
✅ AI-generated article analysis  
✅ SEO blog generation  
✅ AI image prompt creation  
✅ Social media content generation  


## Content Management

✅ Google Drive asset storage  
✅ Organized content workflow  
✅ Automated file management  
✅ AI-generated content tracking  


## Distribution

✅ Platform-specific content creation  
✅ Telegram notifications  
✅ Multi-platform publishing preparation  


---

# 🗺️ System Architecture


```mermaid
flowchart TD

A["⏰ Schedule Trigger"]

--> B["📰 RSS Feed Reader"]

--> C["⚙️ Set Article Data"]

--> D["🤖 AI Research Agent"]

--> E["✍️ AI Blog Writer"]

--> F["🎨 AI Image Prompt Generator"]

--> G["🖼️ Gemini Image Generation"]

--> H["☁️ Google Drive Upload"]

--> I["📱 AI Social Media Generator"]

--> J["🚀 Content Distribution"]

````

---

# 🏗️ Workflow Implementation

# Workflow 1: AI Content Generation Pipeline

## Node 1 — Schedule Trigger

### Purpose

Automatically starts the workflow based on a defined schedule.

Example Configuration:

```text
Trigger:

Daily


Execution:

Automatic
```

The workflow runs without manual intervention.

---

# Node 2 — RSS Feed Reader

### Purpose

Collect trending articles from selected sources.

Example Sources:

* TechCrunch
* The Verge
* Hacker News
* Technology blogs

Captured Information:

| Field   | Description         |
| ------- | ------------------- |
| Title   | Article title       |
| Content | Article information |
| URL     | Original source     |

---

# Node 3 — Set Article Data

### Purpose

Standardize article information before AI processing.

Extracted Data:

| Field      | Description           |
| ---------- | --------------------- |
| Title      | Article headline      |
| Content    | Article details       |
| Source URL | Original article link |

Example:

```json
{
"title":
"Latest AI Technology Trends",

"source":
"Tech Blog",

"url":
"https://example.com"
}
```

---

# Node 4 — AI Research Agent

### Purpose

Analyze article information using Google Gemini AI.

The AI performs:

* Key point extraction
* Trend analysis
* Topic understanding
* Blog angle suggestions
* Content research

Example Output:

```json
{
"topic":
"Artificial Intelligence",

"keyPoints":
[
"AI adoption is increasing",
"Automation is becoming mainstream"
],

"blogAngle":
"How AI is changing businesses"
}
```

---

# Node 5 — AI Blog Writer

### Purpose

Generate a complete SEO-optimized article.

Generated Content Includes:

* H1 Title
* Introduction
* H2 Sections
* SEO Keywords
* Main Content
* Conclusion
* Call-To-Action

Example:

```text
Title:

The Future of AI Automation


Sections:

Introduction

AI Trends

Business Impact

Future Predictions

Conclusion
```

---

# Node 6 — AI Image Prompt Generator

### Purpose

Create detailed image prompts based on generated blog content.

The AI generates:

* Visual concept
* Style direction
* Image composition
* Design elements

Example:

```text
A futuristic AI automation workspace,
modern technology environment,
digital interfaces,
professional blog cover style.
```

---

# Node 7 — Gemini Image Generation

### Purpose

Generate AI-powered visual assets for the content.

Generated Assets:

* Blog cover images
* Social media visuals
* Marketing graphics

---

# Node 8 — Google Drive Upload

### Purpose

Store generated images and assets.

Storage Includes:

| Asset              | Purpose         |
| ------------------ | --------------- |
| Cover Image        | Blog article    |
| Social Media Image | Platform posts  |
| Generated Files    | Content archive |

---

# Node 9 — AI Social Media Generator

### Purpose

Create platform-specific promotional content.

Generated Platforms:

* Facebook
* LinkedIn
* X (Twitter)
* Telegram

Example Output:

```text
LinkedIn:

AI automation is transforming
the way businesses create content...


Twitter:

AI-powered workflows are changing
digital content creation.
```

---

# Node 10 — Content Distribution

### Purpose

Prepare or publish generated content across platforms.

Possible Integrations:

* Telegram Bot
* LinkedIn API
* Facebook API
* WordPress API

---

# 🔐 Credentials Required

| Service             | Purpose            |
| ------------------- | ------------------ |
| Google Gemini API   | AI generation      |
| RSS Feed Access     | Article collection |
| Google Drive OAuth2 | Asset storage      |
| Telegram Bot API    | Notifications      |
| n8n Instance        | Workflow execution |

---

# ⚙️ Setup Guide

## 1. Configure RSS Feed

Add RSS sources:

```text
Technology News

Industry Blogs

Trending Topics
```

Test article retrieval.

---

## 2. Configure Google Gemini AI

Create Gemini API credentials.

Required:

```text
Google AI API Key

Gemini Model Access
```

Test AI responses.

---

## 3. Configure Google Drive

Create folders:

```text
AI Content Factory

├── Blog Images

├── Social Media Assets

└── Generated Content
```

Connect Google Drive OAuth2.

---

## 4. Configure Telegram Bot

Steps:

1. Create bot using BotFather
2. Copy bot token
3. Add Telegram credentials in n8n
4. Configure chat ID

---

## 5. Import Workflow

Import:

```text
workflow.json
```

Configure:

* RSS Feed
* Gemini AI
* Google Drive
* Telegram

Activate workflow.

---

# 🧪 Testing Checklist

| Test Case             | Expected Result       |
| --------------------- | --------------------- |
| Schedule Trigger runs | Workflow starts       |
| RSS retrieves article | Data collected        |
| AI Research executes  | Research generated    |
| Blog Writer runs      | Article created       |
| Image generation runs | Cover image created   |
| Google Drive updates  | Asset stored          |
| Social generator runs | Posts created         |
| Workflow completes    | Content package ready |

---

# 📁 Repository Structure

```text
AI-Content-Factory/

│
├── README.md
│
├── workflow.json
│
├── screenshots/
│   │
│   ├── workflow.png
│   ├── rss-feed.png
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

# 📸 Screenshots

Recommended screenshots:

* Complete workflow
* RSS Feed execution
* AI Research output
* AI Blog Writer result
* Generated image
* Google Drive storage
* Social media output
* Workflow execution

---

# 🚀 Future Improvements

| Feature             | Implementation              |
| ------------------- | --------------------------- |
| Auto Publishing     | WordPress integration       |
| AI SEO Optimization | Keyword analysis            |
| Content Calendar    | Automated scheduling        |
| Analytics Tracking  | Performance monitoring      |
| More AI Models      | OpenAI / Claude integration |
| Video Generation    | AI video workflows          |
| Newsletter Creation | Email automation            |

---

# 🎓 Skills Applied

## Automation

* n8n Workflow Automation
* Event-driven workflows
* Multi-step automation pipelines

## Artificial Intelligence

* Google Gemini AI
* Prompt Engineering
* AI Content Generation
* AI Image Generation

## APIs

* RSS Feed Integration
* Google Drive API
* Telegram Bot API
* Social Media APIs

## Programming

* JavaScript
* JSON Processing
* Data Transformation
* Workflow Logic

## Business Automation

* Content marketing automation
* Digital asset management
* AI productivity systems

---

# 📚 Learning Objectives

This project demonstrates:

* Building advanced AI automation workflows
* Integrating multiple APIs with n8n
* Creating automated content pipelines
* Managing AI-generated assets
* Designing scalable business automation systems

---

# 🙌 Acknowledgements

* n8n
* Google Gemini AI
* Google Drive API
* RSS Feed Technology
* Telegram Bot API

---

# 👨‍💻 Author

**Belio C. Sinangote**

BS Information Technology Student
Cebu Technological University (CTU)

GitHub:

[https://github.com/belioautomation](https://github.com/belioautomation)

This project is part of my **30-Day n8n Automation Portfolio**, showcasing practical automation solutions using **n8n, AI integrations, APIs, and business workflow automation**.

---

# 📄 License

MIT License

```
```
