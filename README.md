# 🚀 AI Content Factory with n8n

An end-to-end AI-powered content automation workflow built in **n8n** that automatically discovers trending content, performs research, writes SEO-optimized blog articles, generates cover images, creates social media posts, and distributes content across multiple platforms.

---

# 📌 Overview

This workflow transforms a single trending article into a complete content package:

✅ Research Summary
✅ SEO Blog Article
✅ AI-Generated Cover Image
✅ Facebook Post
✅ LinkedIn Post
✅ X (Twitter) Post
✅ Telegram Post
✅ Google Drive Storage

The entire process runs automatically with minimal human intervention.

---

# 🏗️ Workflow Architecture

```text
Schedule Trigger
        ↓
RSS Feed Reader
        ↓
Set Article Data
        ↓
AI Research Agent
        ↓
AI Blog Writer
        ↓
AI Image Prompt Generator
        ↓
Gemini Image Generation
        ↓
Google Drive Upload
        ↓
AI Social Media Generator
        ↓
Content Distribution
```

---

# ⚙️ Technologies Used

* n8n
* Google Gemini AI
* Google Drive
* RSS Feeds
* Telegram Bot API
* Facebook API (Optional)
* LinkedIn API (Optional)
* WordPress API (Optional)

---

# 🔄 Workflow Breakdown

## 1. Schedule Trigger

Automatically starts the workflow at a predefined time.

### Purpose

* Daily automation
* Fully hands-off execution

### Example Schedule

```text
Every day at 08:00 AM
```

---

## 2. RSS Feed Reader

Retrieves trending articles from selected news sources.

### Example Sources

* TechCrunch
* The Verge
* Hacker News
* Industry-specific blogs

### Output

```json
{
  "title": "AI is Transforming Content Creation",
  "content": "...",
  "url": "https://..."
}
```

---

## 3. Set Data

Extracts and standardizes article information.

### Fields

```json
{
  "title": "",
  "content": "",
  "url": ""
}
```

---

## 4. AI Research Agent

Uses Google Gemini to analyze the article.

### Responsibilities

* Extract key points
* Identify trends
* Summarize content
* Generate blog angles

### Output Example

```text
Summary:
...

Key Points:
- Point 1
- Point 2

Facts:
- Fact 1
- Fact 2
```

---

## 5. AI Blog Writer

Generates a long-form SEO-optimized blog article.

### Features

* H1 Title
* H2 Sections
* SEO-Friendly Structure
* Introduction
* Conclusion
* Call-to-Action

### Output

```markdown
# Blog Title

## Introduction

...

## Main Content

...

## Conclusion

...
```

---

## 6. AI Image Prompt Generator

Converts the blog article into a visual concept.

### Purpose

Generate a high-quality prompt for AI image creation.

### Example Output

```text
A futuristic AI-powered newsroom with holographic displays,
cinematic lighting, ultra realistic, technology magazine cover,
4k quality
```

---

## 7. Gemini Image Generation

Creates a professional cover image using Google Gemini.

### Features

* AI-generated artwork
* Blog cover image
* Social media compatible
* High-resolution output

### Output

```text
Generated PNG Image
```

---

## 8. Google Drive Upload

Stores generated images in Google Drive.

### Benefits

* Centralized storage
* Easy sharing
* WordPress-ready assets

### Output

```text
Public Image URL
```

---

## 9. AI Social Media Generator

Creates platform-specific social media content.

### Platforms

#### Facebook

* Conversational
* Engagement-focused

#### LinkedIn

* Professional
* Business-oriented

#### X (Twitter)

* Concise
* Maximum 280 characters

#### Telegram

* Informative
* Action-oriented

### Example Output

```json
{
  "facebook": "...",
  "linkedin": "...",
  "twitter": "...",
  "telegram": "..."
}
```

---

# 📤 Distribution Options

## Telegram

Send generated content directly to a Telegram channel or group.

## Facebook

Automatically publish generated posts.

## LinkedIn

Share professional summaries and insights.

## WordPress

Publish complete blog articles automatically.

---

# 🔐 Required Credentials

### Google Gemini

* API Key
* Google AI Studio Access

### Google Drive

* OAuth2 Credentials

### Telegram

* Bot Token
* Chat ID

### WordPress (Optional)

* Username
* Application Password

### Facebook (Optional)

* Access Token

### LinkedIn (Optional)

* OAuth Credentials

---

# 📊 Business Value

This workflow enables:

* Automated content marketing
* Faster content production
* Consistent publishing schedules
* Reduced manual workload
* Multi-platform distribution
* SEO-focused content generation

---

# 🚀 Future Improvements

### SEO Optimization Agent

Automatically improve:

* Keyword density
* Meta descriptions
* Internal linking

### Trend Discovery

Integrate:

* Google Trends
* Reddit
* Hacker News

### Video Generation

Convert blog posts into:

* TikTok videos
* YouTube Shorts
* Instagram Reels

### Content Approval Workflow

Add:

* Human review
* Telegram approval buttons
* Scheduled publishing

---

# 📄 License

MIT License

---

## Author

**Belio C. Sinangote**

Built with **n8n + Google Gemini AI** to demonstrate a complete AI-driven content creation and distribution pipeline.
