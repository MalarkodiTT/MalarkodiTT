# 👋 Hey, I'm Malarkodi T T

### `Computer Science Engineer` · `Builder` · `Problem Solver` · `Tech Explorer`

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=Building+real-world+software+solutions;Exploring+AI+%7C+Blockchain+%7C+DevOps;Turning+ideas+into+working+systems;Learning+by+building+%F0%9F%9A%80" />

<br>

<p align="center">
  <a href="https://github.com/MalarkodiTT">
    <img src="https://img.shields.io/github/followers/MalarkodiTT?style=for-the-badge&logo=github&label=FOLLOWERS" />
  </a>
  <a href="https://github.com/MalarkodiTT?tab=repositories">
    <img src="https://img.shields.io/badge/Projects-8+-blue?style=for-the-badge&logo=github" />
  </a>
  <a href="https://github.com/MalarkodiTT/leetcode">
    <img src="https://img.shields.io/badge/DSA-LeetCode-orange?style=for-the-badge&logo=leetcode" />
  </a>
</p>

---

## 🧠 `whoami`

```java
public class Malarkodi {

    String role = "Computer Science Engineering Student";
    
    String[] interests = {
        "Artificial Intelligence",
        "Blockchain",
        "Cryptography",
        "Full-Stack Development",
        "DevOps",
        "Problem Solving"
    };

    String mindset = "Learn → Build → Break → Debug → Improve";

    String goal =
        "Become an engineer who understands not only HOW to build systems,"
      + " but WHY they work.";

}
```

> 🚀 **I learn technology by building with it.**

Instead of learning technologies only through tutorials, I challenge myself to turn concepts into working applications.

From **cryptographic secret reconstruction** to **AI-powered configuration analysis**, from **blockchain-based voting** to **real-time multilingual communication** — each project represents a different engineering problem I wanted to understand.

---

# ⚡ My Tech Universe

<p align="center">

<img src="https://skillicons.dev/icons?i=java,python,js,html,css,nodejs,express,react,mongodb,mysql,git,github,aws" />

</p>

### 🧩 Core Areas

```text
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   🤖 AI / LLM                    ⛓️ Blockchain              │
│   ├── Groq                      ├── SHA-256                 │
│   ├── Llama 3.1                 ├── Hashing                 │
│   ├── AI Analysis               └── Tamper Detection        │
│   └── Speech Processing                                      │
│                                                             │
│   🔐 Security                   ☁️ DevOps                    │
│   ├── Cryptography              ├── Configuration Drift     │
│   ├── 2FA / OTP                ├── Risk Classification      │
│   ├── JWT                      └── Deployment               │
│   └── Bcrypt                                                │
│                                                             │
│   🌐 Full Stack                 🧩 Problem Solving           │
│   ├── React                    ├── Java                     │
│   ├── Node.js                  ├── DSA                      │
│   ├── Express                  ├── LeetCode                 │
│   └── MongoDB                  └── Algorithms                │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

# 🚀 Things I've Built

## 01 · 🤖 CONFIG DRIFT DETECTOR

### `AI × DevOps × Security`

> **What happens when the configuration you intended to deploy is NOT the configuration actually running?**

That's the problem I wanted to solve.

My Config Drift Detector compares a **Golden Configuration** with a **Deployed Configuration**, identifies differences, determines their severity and uses AI to explain the potential impact and remediation.

### 🔥 The Pipeline

```text
                 GOLDEN CONFIG
                       │
                       ▼
              ┌─────────────────┐
              │  Configuration   │
              │    Comparison    │
              └────────┬────────┘
                       │
                       ▼
                 DeepDiff Engine
                       │
                       ▼
          ┌──────────────────────────┐
          │ Missing │ Added │ Changed │
          │ Type Changes │ Paths     │
          └─────────────┬────────────┘
                        │
                        ▼
                 Severity Engine
                        │
             ┌──────────┴──────────┐
             ▼          ▼          ▼
          CRITICAL     HIGH     MEDIUM/LOW
             │          │          │
             └──────────┼──────────┘
                        ▼
                🤖 AI ANALYSIS
                        │
                        ▼
          Impact + Risk + Remediation
                        │
                        ▼
            📊 Dashboard + History
                        │
                        ▼
                  📄 PDF Report
```

### 🧠 What makes it interesting?

* 🔍 Deep configuration comparison
* 🤖 LLM-powered impact analysis
* 🚨 Risk-based severity classification
* 📊 Interactive analytics
* 🗂️ Historical audit tracking
* 📄 Automated PDF reporting
* 🔐 Authentication
* 🗄️ SQLite persistence

**Stack**

`Python` `Streamlit` `DeepDiff` `Groq` `Llama 3.1` `SQLite` `Plotly` `ReportLab`

🔗 **[Explore the Repository →](https://github.com/MalarkodiTT/Config_Drift_Detector)**

---

# 02 · 🔐 SHAMIR'S SECRET SHARING

### `Cryptography × Mathematics × Full Stack`

What if a secret should **never be stored in one place**?

This project explores **Shamir's Secret Sharing**, where a secret can be reconstructed only when a required threshold of shares is available.

### 🧮 The interesting part

The system uses **Lagrange Interpolation** to recover the secret.

```text
                SECRET
                   │
                   ▼
          Polynomial / Shares
                   │
       ┌───────────┼───────────┐
       ▼           ▼           ▼
     Share 1     Share 2     Share 3
       │           │           │
       └───────────┼───────────┘
                   │
              Threshold
                   │
                   ▼
         Lagrange Interpolation
                   │
                   ▼
              f(0) = SECRET
```

### ⚙️ Engineering highlights

* Large integer handling using `BigInt`
* Multiple numerical bases
* JSON share processing
* Threshold reconstruction
* Lagrange interpolation
* MongoDB persistence
* React frontend
* Node.js backend

**Stack**

`React` `Vite` `Node.js` `Express` `MongoDB` `Mongoose` `BigInt`

🔗 **[Explore the Repository →](https://github.com/MalarkodiTT/Shamir-s-secret-share)**

---

# 03 · 🌍 LIVE SESSION TRANSLATOR

### `Real-Time Communication × Speech × Translation`

Imagine joining an online meeting where everyone speaks a different language.

This project explores how technology can make that communication barrier smaller.

```text
             🎙️ SPEAKER
                  │
                  ▼
          Speech Recognition
                  │
                  ▼
              TEXT
                  │
                  ▼
           Translation API
                  │
                  ▼
        Participant's Language
             ┌────┴────┐
             ▼         ▼
        📝 Subtitle   🔊 Voice
             │         │
             └────┬────┘
                  ▼
          👥 PARTICIPANT
```

### ⚡ Features

* 🎙️ Speech recognition
* 🌍 Multilingual translation
* 📝 Live subtitles
* 🔊 Voice dubbing
* ⚡ Socket.IO communication
* 🎥 Jitsi Meet integration
* 👥 Host / participant workflow

**Stack**

`React` `Node.js` `Express` `Socket.IO` `Web Speech API` `gTTS` `Jitsi`

🔗 **[Explore the Repository →](https://github.com/MalarkodiTT/Automated-translation-in-live-sessions)**

---

# 04 · ⛓️ BLOCKCHAIN E-VOTING

### `Blockchain × Security × Authentication`

A voting system where the main question isn't just:

> **"Who voted?"**

but also:

> **"Can we detect if the stored voting record was modified?"**

### 🔗 Block Integrity

```text
┌─────────────┐
│   BLOCK 1   │
│ Data        │
│ Hash        │
└──────┬──────┘
       │ Previous Hash
       ▼
┌─────────────┐
│   BLOCK 2   │
│ Data        │
│ Hash        │
└──────┬──────┘
       │ Previous Hash
       ▼
┌─────────────┐
│   BLOCK 3   │
│ Data        │
│ Hash        │
└─────────────┘
```

Change the data → hash changes → chain integrity breaks → tampering can be detected.

### 🔐 Security Concepts

* SHA-256 hashing
* Previous-hash linking
* Blockchain validation
* Tamper detection
* OTP / 2FA
* Voter authentication
* Candidate management

**Stack**

`Node.js` `Express.js` `MongoDB` `Mongoose` `JavaScript` `SHA-256`

🔗 **[Explore the Repository →](https://github.com/MalarkodiTT/Blockchain-Based-E-Voting-System)**

---

# 05 · 🏥 HOSPITAL MANAGEMENT SYSTEM

### `Full Stack × REST API × Authentication`

A complete healthcare management application designed to connect patients, doctors and administrators through a centralized platform.

```text
                    🏥 SYSTEM
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
      👨‍⚕️ DOCTOR     🧑 PATIENT    👨‍💼 ADMIN
          │            │            │
          └────────────┼────────────┘
                       ▼
                  REST APIs
                       │
                       ▼
              Node.js + Express
                       │
                       ▼
                  MongoDB
```

### 🔥 Modules

**Patient**

* Appointments
* Insurance
* Feedback

**Doctor**

* Appointment management
* Patient queue
* Digital prescriptions

**Admin**

* Doctor management
* Resources
* Analytics

### 🔐 Backend concepts

`REST API` `JWT` `Bcrypt` `Mongoose` `MongoDB Atlas`

🔗 **[Explore the Repository →](https://github.com/MalarkodiTT/Hospital-Management-System)**

---

# 06 · 👁️ FACE ATTENDANCE SYSTEM

### `Computer Vision × Attendance Automation`

A project exploring the use of facial identity for automated attendance workflows.

```text
📷 Camera
   ↓
Face Detection
   ↓
Face Identification
   ↓
👤 Student Match
   ↓
✅ Attendance
```

🔗 **[Explore the Repository →](https://github.com/MalarkodiTT/Face-Attendence-System)**

---

# 07 · 📝 ONLINE EXAMINATION SYSTEM

### `Digital Assessment Platform`

A web application concept designed around the complete examination workflow.

```text
👤 User
  ↓
📝 Exam
  ↓
⏱️ Attempt
  ↓
📊 Evaluation
  ↓
🏆 Result
```

🔗 **[Explore the Repository →](https://github.com/MalarkodiTT/Online-Exam-System)**

---

# 08 · 🧩 LEETCODE

### `The Daily Battle With Algorithms`

I don't consider DSA something that is "completed".

It's a skill that improves through repetition.

```text
Problem
   ↓
Understand
   ↓
Brute Force
   ↓
Find Bottleneck
   ↓
Optimize
   ↓
Code
   ↓
Test
   ↓
Learn
```

🔗 **[Explore My Solutions →](https://github.com/MalarkodiTT/leetcode)**

---

# 📊 MY PROJECT MAP

```text
                         MALARKODI
                             │
       ┌─────────────────────┼─────────────────────┐
       │                     │                     │
       ▼                     ▼                     ▼
     🤖 AI                 🔐 SECURITY           🌐 FULL STACK
       │                     │                     │
       │                     ├── Shamir             ├── Hospital
       ├── Config Drift     ├── Blockchain         ├── Translation
       └── Translation      └── Authentication      └── Online Exam
                             │
                             ▼
                       ⛓️ BLOCKCHAIN
                             │
                             ▼
                     E-Voting System
                             │
                             ▼
                       🧩 DSA / LEETCODE
```

---

# 🧪 HOW I LEARN

I don't want to be someone who can only answer:

> **"What is this technology?"**

I want to become someone who can answer:

> **"Why is it needed?"**

> **"How does it work internally?"**

> **"Where can it fail?"**

> **"How would I improve it?"**

That's why my projects cover different engineering problems rather than repeating the same CRUD application.

---

# 🎯 CURRENT MISSION

```text
                 ┌──────────────────┐
                 │  BECOME A STRONG │
                 │   SOFTWARE       │
                 │    ENGINEER      │
                 └────────┬─────────┘
                          │
          ┌───────────────┼────────────────┐
          ▼               ▼                ▼
       ☕ JAVA          🧩 DSA          🗄️ DBMS
          │               │                │
          └───────────────┼────────────────┘
                          ▼
                  🌐 SOFTWARE DEVELOPMENT
                          │
              ┌───────────┼───────────┐
              ▼           ▼           ▼
             🤖 AI     ⛓️ Blockchain  ☁️ Cloud
```

---

# 📈 WHAT I'M WORKING ON

* ☕ Strengthening Java & OOP
* 🧩 Improving DSA & problem solving
* 🗄️ Deepening DBMS & SQL fundamentals
* 🌐 Building stronger backend systems
* 🤖 Exploring practical AI applications
* ⛓️ Understanding blockchain beyond the basics
* 🔐 Learning security & cryptography concepts
* ☁️ Improving cloud & DevOps knowledge

---

# 🏆 MY ENGINEERING PHILOSOPHY

### `Don't just use the technology. Understand the problem it solves.`

```text
          IDEA
           ↓
       EXPERIMENT
           ↓
         BUILD
           ↓
         BREAK
           ↓
        DEBUG
           ↓
        IMPROVE
           ↓
         DEPLOY
           ↓
          LEARN
           ↺
```

---

# 🌱 Beyond the Code

🏆 **State-Level Silambam Player**

🎓 **B.E. Computer Science Engineering**

👩‍💻 **Full-Stack Development Experience**

💡 **AI / Blockchain Project Builder**

🧩 **Competitive Problem Solver**

---

# 🤝 LET'S CONNECT

<p align="center">

<a href="https://github.com/MalarkodiTT">
<img src="https://img.shields.io/badge/GitHub-MalarkodiTT-181717?style=for-the-badge&logo=github" />
</a>

</p>

---

<p align="center">

### 💻 BUILDING TODAY.

### 🧠 LEARNING EVERY DAY.

### 🚀 ENGINEERING FOR TOMORROW.

<br>

**⭐ If you find something interesting in my repositories, feel free to explore!**

</p>

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</p>
