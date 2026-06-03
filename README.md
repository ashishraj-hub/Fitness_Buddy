# 🏃‍♂️‍➡️Fitness Buddy

---

<div align="center">

<!-- BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=🏋️%20Fitness%20Buddy&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Your%20AI-Powered%20Personal%20Health%20%26%20Fitness%20Coach&descAlignY=60&descSize=18" width="100%"/>

<br/>

<!-- BADGES ROW 1 -->
[![IBM watsonx](https://img.shields.io/badge/IBM-watsonx.ai-0530AD?style=for-the-badge&logo=ibm&logoColor=white)](https://www.ibm.com/watsonx)
[![watsonx Orchestrate](https://img.shields.io/badge/IBM-watsonx%20Orchestrate-0062FF?style=for-the-badge&logo=ibm&logoColor=white)](https://www.ibm.com/products/watsonx-orchestrate)
[![IBM Cloud](https://img.shields.io/badge/IBM-Cloud%20Lite-1261FE?style=for-the-badge&logo=ibmcloud&logoColor=white)](https://cloud.ibm.com)

<!-- BADGES ROW 2 -->
[![Agentic AI](https://img.shields.io/badge/Agentic-AI-00C6A2?style=for-the-badge&logo=openai&logoColor=white)](#)
[![Granite LLM](https://img.shields.io/badge/Model-IBM%20Granite%203.8B-FF6B35?style=for-the-badge&logo=ibm&logoColor=white)](#)
[![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%2F%20CSS3%20%2F%20JS-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](#license)

<br/>

> **🤖 An intelligent, conversational AI fitness coach built on IBM Cloud Lite — providing personalized workouts, nutrition guidance, motivation, and habit tracking — available 24/7, completely free.**

<br/>

<!-- DEMO GIF PLACEHOLDER -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00C6A2&center=true&vCenter=true&width=600&lines=💪+Personalized+Home+Workout+Plans;🥗+Smart+Nutrition+Suggestions;⚡+Daily+Motivation+%26+Habit+Coaching;🤖+Powered+by+IBM+Granite+LLM;🌐+Deployed+on+IBM+Cloud+Lite+(Free+Tier)" alt="Typing SVG"/>

<br/><br/>

<!-- QUICK LINKS -->
[🚀 Live Demo](#-live-demo) • [📖 Documentation](#-table-of-contents) • [🏗️ Architecture](#️-system-architecture) • [⚡ Quick Start](#-quick-start) • [🤝 Contributing](#-contributing)

</div>

---

## 📋 Table of Contents

- [🌟 Project Overview](#-project-overview)
- [😤 The Problem](#-the-problem)
- [✅ Our Solution](#-our-solution)
- [🎯 Key Features](#-key-features)
- [🏗️ System Architecture](#️-system-architecture)
- [🛠️ Tech Stack](#️-tech-stack)
- [📂 Project Structure](#-project-structure)
- [⚡ Quick Start](#-quick-start)
- [🔧 Configuration](#-configuration)
- [🤖 AI Agent Design](#-ai-agent-design)
- [💬 Prompt Engineering](#-prompt-engineering)
- [🧪 Testing](#-testing)
- [🚀 Deployment](#-deployment)
- [📸 Screenshots](#-screenshots)
- [🗺️ Roadmap](#️-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👨‍💻 Author](#-author)
- [🙏 Acknowledgements](#-acknowledgements)

---

## 🌟 Project Overview

**Fitness Buddy** is a full-stack **Agentic AI** project built entirely on **IBM Cloud Lite (free tier)** services. It leverages the power of **IBM watsonx.ai Studio** for foundation model inference and **IBM watsonx Orchestrate** for intelligent agent orchestration — delivering a conversational, personalized fitness coaching experience to anyone, anywhere, at no cost.

This project was developed as part of an **Agentic AI challenge** to demonstrate how enterprise-grade AI capabilities can be made accessible and practical for everyday health and wellness use cases.

```
"Your personal trainer, nutritionist, and motivational coach —
 all in one AI-powered chat, available 24/7."
```

---

## 😤 The Problem

In today's fast-paced world, maintaining a healthy lifestyle is harder than ever:

| Challenge | Reality |
|-----------|---------|
| 💸 **Cost** | Personal trainers cost $50–$150/session |
| ⏰ **Time** | Gym schedules don't adapt to busy routines |
| 🧭 **Guidance** | Generic apps ignore individual needs |
| 🔋 **Motivation** | No accountability partner available 24/7 |
| 🥗 **Nutrition** | Confusing, often expensive meal planning |

> **Over 80% of people who start a fitness routine quit within the first 5 weeks** — largely due to lack of personalized guidance and inconsistent motivation.

---

## ✅ Our Solution

**Fitness Buddy** solves this by being a **free, always-available, personalized AI coach** that:

- 🎯 Tailors every plan to the **individual user's age, goals, and fitness level**
- 🏠 Focuses on **home workouts** — no gym, no equipment needed
- 🥗 Provides **simple, budget-friendly** meal suggestions
- ⚡ Delivers **real-time motivation** and habit nudges
- 🤖 Uses **IBM Granite LLM** for safe, grounded, evidence-based responses
- ☁️ Runs entirely on **IBM Cloud Lite** — zero infrastructure cost

---

## 🎯 Key Features

<table>
<tr>
<td width="50%">

### 🏋️ Personalized Workout Plans
- Home-based exercises, zero equipment needed
- Adjusts to beginner / intermediate / advanced
- Covers cardio, strength, flexibility & HIIT
- Time-flexible: 10 min to 1 hour sessions

</td>
<td width="50%">

### 🥗 Smart Nutrition Guidance
- Simple, budget-friendly meal ideas
- Calorie-aware suggestions
- Dietary preference support
- Hydration and supplement basics

</td>
</tr>
<tr>
<td width="50%">

### ⚡ Daily Motivation Engine
- Personalized motivational messages
- Progress celebration responses
- Streak acknowledgement
- Goal-oriented encouragement

</td>
<td width="50%">

### 📅 Habit Building Coach
- Daily check-in conversations
- Streak tracking awareness
- Micro-habit recommendations
- Relapse recovery guidance

</td>
</tr>
</table>

### 🔒 Safety First
- ✅ Never provides medical diagnoses
- ✅ Always recommends professional consultation for injuries
- ✅ Safe exercise modifications for all fitness levels
- ✅ IBM Granite model's built-in safety guardrails

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                        USER INTERFACE                           │
│              Web Chat (HTML/CSS/JS) or Embed Widget             │
└──────────────────────────┬──────────────────────────────────────┘
                           │ HTTPS
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│               IBM watsonx ORCHESTRATE                           │
│  ┌──────────────┐ ┌──────────────┐ ┌──────────────┐            │
│  │   Workout    │ │  Nutrition   │ │  Motivation  │  Skills     │
│  │   Planner   │ │   Advisor    │ │    Coach     │  (Agents)   │
│  └──────────────┘ └──────────────┘ └──────────────┘            │
│         ↑ Intent Routing · Session Memory · Skill Dispatch      │
└──────────────────────────┬──────────────────────────────────────┘
                           │ REST API
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                   IBM watsonx.ai STUDIO                         │
│  ┌─────────────────┐  ┌──────────────┐  ┌───────────────────┐  │
│  │  Granite 3-8B   │  │  Prompt Lab  │  │   RAG Pipeline    │  │
│  │  Instruct LLM   │  │  (Tuned)     │  │ (Knowledge Base)  │  │
│  └─────────────────┘  └──────────────┘  └───────────────────┘  │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                  IBM CLOUD LITE INFRASTRUCTURE                  │
│   Cloudant DB │ Cloud Object Storage │ IAM │ Cloud Functions   │
└─────────────────────────────────────────────────────────────────┘
```

### 🔄 Conversation Flow

```
User Input → Intent Detection → Skill Selection → LLM Inference
    ↓                                                    ↓
Session Storage  ←──── Response Formatting ←──── Granite Output
    ↓
Personalized Response delivered to User
```

---

## 🛠️ Tech Stack

### ☁️ IBM Cloud Services (All Lite/Free Tier)

| Service | Purpose | Tier |
|---------|---------|------|
| **IBM watsonx.ai Studio** | Foundation model inference, Prompt Lab, RAG | Lite ✅ |
| **IBM watsonx Orchestrate** | Agent orchestration, skill management, web chat | Trial ✅ |
| **IBM Cloudant** | NoSQL database for user profiles & logs | Lite ✅ |
| **IBM Cloud Object Storage** | Knowledge base document storage | Lite ✅ |
| **IBM Cloud Functions** | Serverless middleware / API layer | Lite ✅ |
| **IBM Cloud IAM** | Identity & access management | Free ✅ |

### 🤖 AI & Models

| Component | Technology |
|-----------|-----------|
| **Foundation Model** | IBM Granite 3-8B Instruct |
| **Agent Framework** | watsonx Orchestrate Skill Engine |
| **Prompt Strategy** | System-role prompting + few-shot examples |
| **Retrieval** | watsonx.ai Vector Index (RAG) |

### 🖥️ Frontend

| Technology | Usage |
|-----------|-------|
| **HTML5 / CSS3** | UI structure and styling |
| **Vanilla JavaScript** | API calls, chat logic, session management |
| **IBM watsonx Embed Widget** | Orchestrate web chat integration |
| **IBM watsonx.ai REST API** | Direct LLM inference fallback |

---

## 📂 Project Structure

```
fitness-buddy/
│
├── 📄 README.md                    # This file
│
├── 🌐 frontend/
│   ├── fitness-buddy.html          # Main web app (Orchestrate embed)
│   ├── fitness-buddy-standalone.html  # Standalone (direct watsonx.ai API)
│   └── assets/
│       ├── style.css               # Styles (embedded in HTML)
│       └── favicon.ico
│
├── 🤖 agent/
│   ├── system-prompt.txt           # Fitness Buddy behavior prompt
│   ├── skills/
│   │   ├── workout-planner.yaml    # OpenAPI spec for workout skill
│   │   ├── nutrition-advisor.yaml  # OpenAPI spec for nutrition skill
│   │   ├── motivation-coach.yaml   # OpenAPI spec for motivation skill
│   │   └── habit-tracker.yaml      # OpenAPI spec for habit skill
│   └── orchestrate-config.json     # Orchestrate deployment config
│
├── ☁️ cloud-functions/
│   ├── getUserProfile.js           # Fetch user profile from Cloudant
│   ├── saveActivityLog.js          # Save workout/nutrition logs
│   ├── createUserProfile.js        # Create new user
│   └── getWeeklyProgress.js        # Aggregate weekly stats
│
├── 📊 watsonx-studio/
│   ├── prompts/
│   │   ├── workout-prompt.txt      # Tuned workout planner prompt
│   │   ├── nutrition-prompt.txt    # Tuned nutrition advisor prompt
│   │   ├── motivation-prompt.txt   # Tuned motivation coach prompt
│   │   └── habit-prompt.txt        # Tuned habit tracker prompt
│   └── knowledge-base/
│       ├── exercise-glossary.pdf   # RAG document
│       ├── nutrition-basics.pdf    # RAG document
│       └── habit-science.pdf       # RAG document
│
└── 📝 docs/
    ├── architecture.md             # Detailed architecture notes
    ├── setup-guide.md              # Step-by-step IBM Cloud setup
    └── api-reference.md            # API endpoints reference
```

---

## ⚡ Quick Start

### Prerequisites

Before you begin, ensure you have:

- [ ] An **IBM Cloud account** (free at [cloud.ibm.com](https://cloud.ibm.com))
- [ ] **Python 3.x** installed (for local server)
- [ ] A modern browser (Chrome, Edge, Firefox)
- [ ] **VS Code** (recommended) with Live Server extension

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/fitness-buddy.git
cd fitness-buddy
```

### 2️⃣ Set Up IBM Cloud Services

```bash
# Log in to IBM Cloud CLI (optional)
ibmcloud login

# Or use the IBM Cloud web dashboard at:
# https://cloud.ibm.com/catalog
```

Provision these free services in order:
1. **watsonx.ai Studio** → [Provision here](https://cloud.ibm.com/catalog/services/watson-studio)
2. **watsonx Orchestrate** → [Provision here](https://cloud.ibm.com/catalog/services/watsonx-orchestrate)
3. **IBM Cloudant** → [Provision here](https://cloud.ibm.com/catalog/services/cloudant)
4. **Cloud Object Storage** → [Provision here](https://cloud.ibm.com/catalog/services/cloud-object-storage)

### 3️⃣ Configure Credentials

Open `frontend/fitness-buddy-standalone.html` and update:

```javascript
const WX_API_KEY    = "YOUR_IBM_CLOUD_API_KEY";   // IBM Cloud → Manage → API Keys
const WX_PROJECT_ID = "YOUR_WATSONX_PROJECT_ID";  // watsonx.ai → Project → Manage
const WX_REGION     = "au-syd";                   // Your IBM Cloud region
```

> 🔑 **Get your API Key:** IBM Cloud Dashboard → `Manage` → `Access (IAM)` → `API keys` → `Create`
>
> 📁 **Get your Project ID:** watsonx.ai Studio → Your Project → `Manage` tab → copy Project ID

### 4️⃣ Run Locally

```bash
# Option A: Python (recommended)
cd frontend
python -m http.server 8080

# Option B: Node.js
npx serve frontend -p 8080
```

### 5️⃣ Open in Browser

```
http://localhost:8080/fitness-buddy-standalone.html
```

🎉 **Fitness Buddy is now running!**

---

## 🔧 Configuration

### Agent Behavior (System Prompt)

The core AI behavior is defined in `agent/system-prompt.txt`:

```
You are Fitness Buddy, a friendly and energetic AI health and fitness coach.

Your role:
1. Provide safe fitness guidance.
2. Recommend home workouts based on user fitness level, age, and goals.
3. Suggest beginner-friendly, nutritious meal ideas.
4. Encourage healthy habits and consistency.
5. Motivate users positively and celebrate their progress.

Always ask for:
- Age
- Fitness goal (lose weight / build muscle / stay active)
- Activity level (beginner / intermediate / advanced)
...before creating a personalized plan.

Never provide medical diagnosis or replace professional medical advice.
```

### Model Parameters

```json
{
  "model_id": "ibm/granite-3-8b-instruct",
  "parameters": {
    "max_new_tokens": 600,
    "temperature": 0.7,
    "top_p": 0.9,
    "repetition_penalty": 1.1
  }
}
```

### Supported IBM Regions

| Region | Code | URL |
|--------|------|-----|
| US South | `us-south` | `us-south.ml.cloud.ibm.com` |
| EU Germany | `eu-de` | `eu-de.ml.cloud.ibm.com` |
| Australia Sydney | `au-syd` | `au-syd.ml.cloud.ibm.com` |
| UK South | `eu-gb` | `eu-gb.ml.cloud.ibm.com` |

---

## 🤖 AI Agent Design

### Skills Architecture

Fitness Buddy uses a **multi-skill agentic design** in watsonx Orchestrate:

```
┌─────────────────────────────────────────────────┐
│              Fitness Buddy Agent                │
│                                                 │
│  ┌──────────────────────────────────────────┐  │
│  │          Intent Classification           │  │
│  │  "workout" | "nutrition" | "motivation"  │  │
│  │         "habit" | "general"              │  │
│  └──────────────┬───────────────────────────┘  │
│                 │ routes to                     │
│    ┌────────────┴────────────────────┐          │
│    ▼            ▼           ▼        ▼          │
│  Workout    Nutrition   Motivation  Habit       │
│  Planner    Advisor      Coach     Tracker      │
│  Skill      Skill        Skill     Skill        │
└─────────────────────────────────────────────────┘
```

### Session Memory

The agent maintains conversation context including:
- User's **age and fitness level**
- **Current goals** and progress
- **Previous workout** recommendations (avoids repetition)
- **Dietary preferences** and restrictions

---

## 💬 Prompt Engineering

### Few-Shot Example — Workout Planner

```
System: You are a certified fitness coach. Create safe, home-based workout plans.

User: I'm 25, want to lose weight, beginner level, have 20 minutes.
Assistant: Here is a **20-minute beginner fat-loss workout** you can do at home:

**Warm-up (3 min):** March in place, arm circles, neck rolls

**Circuit (repeat 2x):**
- 30s Jumping Jacks → 15s rest
- 30s Bodyweight Squats → 15s rest  
- 30s Push-ups (knee modified) → 15s rest
- 30s High Knees → 15s rest
- 30s Plank Hold → 30s rest

**Cool-down (3 min):** Standing quad stretch, hamstring stretch, deep breathing

Burn estimate: ~150-180 calories. Stay hydrated! 💪
```

---

## 🧪 Testing

### Manual Test Scenarios

Run these conversations to validate all agent skills:

| Test Case | Input | Expected Behavior |
|-----------|-------|-------------------|
| Onboarding | `"Hello"` | Asks for age, goal, activity level |
| Workout | `"Give me a workout, I'm 22, beginner, 30 mins"` | Returns structured workout plan |
| Nutrition | `"What should I eat to lose weight?"` | Returns meal suggestions with context |
| Motivation | `"I feel like giving up"` | Empathetic, encouraging response |
| Habit | `"I completed my workout today!"` | Celebrates and encourages streak |
| Safety | `"Do I have diabetes?"` | Declines diagnosis, suggests doctor |
| Off-topic | `"What's the weather today?"` | Redirects to fitness topics politely |

### API Testing with cURL

```bash
# Test IAM token generation
curl -X POST https://iam.cloud.ibm.com/identity/token   -H "Content-Type: application/x-www-form-urlencoded"   -d "grant_type=urn:ibm:params:oauth:grant-type:apikey&apikey=YOUR_API_KEY"

# Test watsonx.ai inference
curl -X POST https://au-syd.ml.cloud.ibm.com/ml/v1/text/chat?version=2024-05-31   -H "Authorization: Bearer YOUR_IAM_TOKEN"   -H "Content-Type: application/json"   -d '{
    "model_id": "ibm/granite-3-8b-instruct",
    "project_id": "YOUR_PROJECT_ID",
    "messages": [
      {"role": "user", "content": "Give me a 10-minute beginner workout"}
    ],
    "parameters": {"max_new_tokens": 400}
  }'
```

---

## 🚀 Deployment

### Option A — IBM Cloud Object Storage (Recommended for sharing)

```bash
# 1. Upload HTML to your COS bucket
# IBM Cloud Dashboard → Object Storage → your bucket → Upload

# 2. Enable public access on the object
# Set ACL to "public-read"

# 3. Your live URL will be:
# https://s3.au-syd.cloud-object-storage.appdomain.cloud/YOUR-BUCKET/fitness-buddy.html
```

### Option B — GitHub Pages (Free, permanent URL)

```bash
# 1. Push to GitHub
git init
git add .
git commit -m "🚀 Initial release: Fitness Buddy AI"
git remote add origin https://github.com/YOUR_USERNAME/fitness-buddy.git
git push -u origin main

# 2. Enable GitHub Pages
# Repo → Settings → Pages → Source: main branch → /docs folder
# Move HTML to /docs/index.html

# 3. Live at: https://YOUR_USERNAME.github.io/fitness-buddy
```

### Option C — IBM Code Engine (Production-grade)

```bash
# Build and deploy a containerized version
ibmcloud ce project create --name fitness-buddy
ibmcloud ce app create   --name fitness-buddy-app   --image icr.io/YOUR_NAMESPACE/fitness-buddy:latest   --port 8080
```

### ⚠️ Important: Never expose API keys in frontend code for production!

For production deployment, use a backend proxy:

```
Browser → Your Backend (Node/Python) → IBM watsonx.ai API
              ↑
         API key stored safely
         in environment variables
```

---

## 📸 Screenshots

<div align="center">

| Feature | Preview |
|---------|---------|
| **Landing Page** | Clean, modern UI with IBM watsonx branding |
| **Chat Interface** | Real-time streaming responses with typing indicator |
| **Workout Plan** | Structured, timed workout with exercise details |
| **Nutrition Tips** | Personalized meal suggestions based on user goals |
| **Motivation Mode** | Empathetic, goal-aware encouragement messages |

> 📌 *Add your actual screenshots in a `/docs/screenshots/` folder and update the table with `![screenshot](docs/screenshots/name.png)`*

</div>

---

## 🗺️ Roadmap

### ✅ Phase 1 — MVP (Completed)
- [x] IBM watsonx.ai Studio project setup
- [x] IBM Granite LLM integration
- [x] Agent behavior prompt engineering
- [x] watsonx Orchestrate agent deployment
- [x] Web chat embed integration
- [x] Standalone HTML with direct API

### 🔄 Phase 2 — In Progress
- [ ] Cloudant database for user profiles
- [ ] IBM Cloud Functions middleware
- [ ] Session memory across conversations
- [ ] Weekly progress reports

### 🔮 Phase 3 — Planned
- [ ] Voice input/output via IBM Watson Speech-to-Text
- [ ] WhatsApp / Slack channel integration
- [ ] Workout video recommendations via YouTube API
- [ ] Meal photo analysis using watsonx vision models
- [ ] Mobile app (Progressive Web App)
- [ ] Multi-language support

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

```bash
# 1. Fork the repository
# Click the Fork button on GitHub

# 2. Create a feature branch
git checkout -b feature/amazing-feature

# 3. Make your changes and commit
git add .
git commit -m "✨ Add amazing feature"

# 4. Push to your fork
git push origin feature/amazing-feature

# 5. Open a Pull Request
# Go to GitHub → New Pull Request
```

### Contribution Guidelines
- Follow the existing code style
- Add comments for complex logic
- Update documentation for new features
- Test all changes before submitting PR
- Be respectful and constructive in reviews

---

## 📄 License

This project is licensed under the **Apache License** — see the [LICENSE](LICENSE) file for details.

```
Apache License — Free to use, modify, and distribute with attribution.
```

---

## 👨‍💻 Author

<div align="center">

**Ashish Raj** — Agentic AI Developer

[![GitHub](https://img.shields.io/badge/GitHub-YOURUSERNAME-181717?style=for-the-badge&logo=github)](https://github.com/ashishraj-hub)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/YOUR_PROFILE)

*Built with ❤️ as part of the IBM Agentic AI Challenge*

</div>

---

## 🙏 Acknowledgements

- **IBM watsonx Team** — For making enterprise AI accessible on the free tier
- **IBM Granite Model** — Open, safe, and powerful foundation model
- **IBM watsonx Orchestrate** — For the seamless agent orchestration platform
- **IBM Cloud** — For free Lite tier services that power this project end-to-end

---

<div align="center">

**⭐ If this project helped you, please give it a star! It motivates continued development.**

[![Star History](https://img.shields.io/github/stars/YOUR_USERNAME/fitness-buddy?style=social)](https://github.com/ashishraj-hub/fitness-buddy)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
