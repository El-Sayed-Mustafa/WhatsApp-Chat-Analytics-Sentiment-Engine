
# 📊 The Pulse of Connection: WhatsApp Chat Analytics & Sentiment Engine

## 📝 Project Overview

This project is a comprehensive **End-to-End Business Intelligence solution** that transforms unstructured WhatsApp chat data into actionable insights. By analyzing over **64,000 messages**, this dashboard explores communication patterns, response dynamics, and emotional trends between two individuals (Alice & Bob).

The core challenge was to convert raw, messy text files into a structured **Star Schema** and apply **Natural Language Processing (NLP)** to quantify human emotions.

---

## 📸 Dashboard Preview

### 1. Executive Summary: The Big Picture

<img width="1402" height="800" alt="image" src="https://github.com/user-attachments/assets/72aa9f31-1926-4d9a-91ed-beea02869ea1" />


**Insights & Features:**

* **Key Performance Indicators (KPIs):** Displays total message volume (64K) and distribution per user to evaluate engagement levels.
* **Radar Chart Comparison:** A specialized radar chart used to compare "Communication Skills," highlighting **Bob’s** dominance in initiation and **Alice’s** superior response speed.
* **Initiation Share:** Deep dive into who drives the conversation; data reveals Bob as the primary "Engine" with an **81.6%** initiation rate.

---

### 2. Conversation Behavior: Psychological Patterns
<img width="1405" height="806" alt="image" src="https://github.com/user-attachments/assets/490da171-ff24-43db-8cd8-464e62f3bdaf" />


**Insights & Features:**

* **Gap Analysis:** Investigates the impact of "Silence" on chat quality; the visual demonstrates how long time gaps often lead to shorter, fragmented conversations.
* **Conversation Categorization:** Segmented chats into three categories (**Marathon, Check-in, Normal**) based on duration and volume using advanced **DAX Logic**.
* **Flow Analysis:** Tracking message sequences to determine how conversations start and end across different periods of the day.

---

### 3. Sentiment & Emoji Insights: The Emotional Pulse

<img width="1402" height="799" alt="image" src="https://github.com/user-attachments/assets/a1ba3b1e-4a86-4998-b324-6ac5764491ce" />

<img width="1400" height="800" alt="image" src="https://github.com/user-attachments/assets/414b8b12-53d1-41a2-8b88-3ee3b9421c78" />

**Insights & Features:**

* **Sentiment Trends:** Monitoring daily and monthly emotional fluctuations; analysis identified **Saturday** as the most emotionally positive day.
* **Emoji Cloud & Categorization:** Analyzed over 3,500 emojis categorized into (Love, Laugh, Sad) to decode the non-verbal cues between participants.
* **Heatmap Correlation:** Correlated message density with mood states to identify specific "Tension Periods" throughout the month.

---

### 4. Time Dynamics: The Interaction Engine

<img width="1399" height="798" alt="image" src="https://github.com/user-attachments/assets/eac71fa2-0d8f-4d27-8390-b5b9f20fe606" />

**Insights & Features:**

* **The "Lag" Impact (Combo Chart):** The project's most critical visual, correlating **Avg. Response Time** with **Sentiment**. It mathematically proves that delayed responses lead to an immediate drop in the emotional curve.
* **Dynamic Toggle System:** Utilized **Power BI Bookmarks** for seamless switching between "Response Speed" and "Sentiment" views, optimizing UI space.
* **AI-Powered Smart Narratives:** Real-time dynamic summaries (e.g., "Bob is 3.73 mins slower in the morning") that translate complex data into plain English.

---

## 🛠️ Technical Pipeline (The Architecture)

### 1. Data Cleaning & Transformation (ETL)

* **Raw Extraction:** Handled unstructured `.txt` exports from WhatsApp.
* **Regex Processing:** Used **Python (Regular Expressions)** to parse dates, timestamps, sender names, and message content.
* **Power Query (M):** Performed **Data Scrubbing** to remove system messages, media links, and null entries, ensuring a clean dataset for modeling.

### 2. Natural Language Processing (NLP)

* **Sentiment Scoring:** Applied **Sentiment Analysis** to assign a quantitative score to each message.
* **Trend Analysis:** Aggregated scores to visualize emotional shifts over months, days, and even hours.

### 3. Data Modeling & DAX

* **Schema:** Implemented a **Star Schema** architecture.
* **Fact Tables:** `Fact_Messages`, `Fact_Emoji_Usage`.
* **Dimension Tables:** `Dim_Time`, `Dim_Calendar`, `Dim_Users`.


* **Advanced DAX:** Authored complex measures for:
* **Initiation Share:** Identifying the conversation starter.
* **Response Velocity:** Calculating average reply time in minutes.
* **The "Lag" Correlation:** Measuring the impact of delay on sentiment.



---

## 🔍 Key Business Insights

### 📊 Alice vs. Bob: Behavior Analysis

| Metric | Alice | Bob |
| --- | --- | --- |
| **Initiation Share** | 18.4% | **81.6% (The Starter)** |
| **Avg. Response Time** | **4.65 Min (The Sprinter)** | 6.04 Min |
| **Sentiment Polarity** | Steady | **High Positive (The Emotional Engine)** |

### 💡 Core Discoveries

* **Activity Peaks:** Found a significant surge in activity every Thursday at **6:00 AM**.
* **The Silence Impact:** Data proves that conversations following a 5+ hour gap tend to start with a lower sentiment score.
* **Emoji Intelligence:** Bob uses emojis defensively to mitigate conflict, while Alice uses them primarily to reinforce positive moments.

---

## 🎨 UI/UX Features

* **Dark Theme:** A high-contrast "Fire & Night" theme for better readability and aesthetic appeal.
* **Toggle Interactivity:** Integrated **Bookmarks & Selection Panes** to switch between views dynamically.
* **Smart Narratives:** AI-powered text summaries that update in real-time based on user filters.

---

## 🤝 Contact & Collaboration

If you have a project involving complex unstructured data or need advanced Power BI storytelling, let's connect!

* **LinkedIn:** [Eng. Elsayed Mustafa](https://www.linkedin.com/in/eng-elsayed-mustafa/)
* **Portfolio:** [Live Portfolio](https://adorable-kashata-14e227.netlify.app/)
