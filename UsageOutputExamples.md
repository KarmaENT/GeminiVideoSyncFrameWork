## 📘 Usage Example

**User Input:**

- **YouTube URL**: https://www.youtube.com/watch?v=3KtWfp0UopM  
- **Transcript**: [Pasted transcript of Google’s 25-year anniversary video]  
- **Context**: Audience = students, Purpose = study guide, Tone = instructional

---

## 💬 Gem Prompt

> Summarize the transcript in 150 words for students in an instructional tone, focusing on learning outcomes. Then, generate a study guide framework based on the summary.

---

## ✍️ Output

### ✅ Summary (Markdown)

## Summary: Google’s 25-Year Evolution

The video _"Google Turns 25: A Quarter Century of Search!"_ outlines Google’s journey from a search engine to a global tech leader. It covers key milestones like **PageRank**, **Google Maps**, and **AI advancements** (e.g., **Gemini**). The video emphasizes Google’s mission to organize information and its focus on **user-centric innovation**.

For students, key lessons include:
- Understanding how **search algorithms** work
- The role of **AI in modern tech**
- The importance of **scalability in system design**

_(150 words)_

**Metadata**:
- **Video Title**: Google Turns 25: A Quarter Century of Search!
- **Generated**: 2025-07-02T08:34:00Z

---

### 📚 Framework (Markdown)

## Study Guide: Google’s 25-Year Evolution

### Key Concepts:
- **PageRank**: Algorithm for ranking web pages.
- **AI Integration**: Use of Gemini in search and services.
- **Scalability**: Building systems for global use.

### Questions:
- How does PageRank determine search result relevance?
- What are examples of AI in Google’s services?

### Resources:
- [Google Blog](https://www.google.com/search?q=site:blog.google)
- [Gemini API Docs](https://www.google.com/search?q=site:ai.google.dev+Gemini+API)

### Metadata:
- **Source**: https://www.youtube.com/watch?v=3KtWfp0UopM
- **Generated**: 2025-07-02T08:34:00Z

---

### 🔁 Follow-Up Prompt

> Refine the study guide to include a section on practical applications of AI in search.

---

### 🔧 Refined Output

## Study Guide: Google’s 25-Year Evolution

### Key Concepts:
- **PageRank**: Algorithm for ranking web pages.
- **AI Integration**: Use of Gemini in search and services.
- **Scalability**: Building systems for global use.

### Questions:
- How does PageRank determine search result relevance?
- What are examples of AI in Google’s services?

### Practical Applications:
- **AI in Search**:
  - Personalized search results
  - Natural language processing (NLP)
  - Image and voice recognition

### Resources:
- [Google Blog](https://www.google.com/search?q=site:blog.google)
- [Gemini API Docs](https://www.google.com/search?q=site:ai.google.dev+Gemini+API)

### Metadata:
- **Source**: https://www.youtube.com/watch?v=3KtWfp0UopM
- **Generated**: 2025-07-02T08:34:00Z

---

## ⚙️ Optimizations for Gemini Web App

### Lightweight Design:
- Avoid reliance on external APIs (e.g., YouTube Transcript API) by requiring users to provide transcripts or key points.
- Use text-based knowledge files to minimize processing overhead.

### Prompt Efficiency:
- Use concise, structured prompts to stay within the web app’s token limits.
- Leverage Gemini 2.5 Pro’s reasoning to infer context when user inputs are incomplete.

### User-Friendly Interaction:
- Include clear prompts for users to provide necessary inputs (e.g., transcript, context).
- Offer iterative refinement options to enhance usability.

### Error Handling:
- Handle missing transcripts or unclear inputs by prompting users for clarification.
- Use disclaimers to manage expectations for partial outputs.

### Scalability:
- Support batch processing of multiple videos by allowing users to input multiple transcripts sequentially.
- Cache user inputs within the session to streamline follow-up queries.
