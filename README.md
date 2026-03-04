# Solutions Engineer Code Challenge & Technical Interview
**Updated: March 2026**

---

## Welcome

Welcome to the FusionAuth SE Code Challenge! This process is designed to help us see how you think, build, and communicate, not just whether you can follow a tutorial.

You'll complete a coding challenge on your own, then join a 1-hour technical interview structured in three parts. Someone from our People team will reach out to schedule within 6 business days of your technical interview.

---

## Part One: Code Challenge

Complete the following before your technical interview.

### 1. Quickstart & Local Setup

Work through a FusionAuth quickstart in the language of your choice. Pick from one of the **web application** options (not the 5-minute, mobile, SPA, or API quickstarts). Get a local FusionAuth instance running on port 9011 with a basic working application.

### 2. Enhancements

Once your base app is running, add the following:

**Custom User Data**
Add a page that lets a user store additional profile data, like a nickname, favorite snack, or hobby. Store those values in FusionAuth's `user.data` object using custom data fields with proper validation.

**Two-Factor Authentication**
Implement TOTP-based 2FA. Users should be able to enable or disable it from their profile, and if enabled, they're prompted for a second factor at login.

**Role-Based Access Control**
Create at least three roles (e.g., Admin, Editor, Viewer) and restrict access to different parts of the app accordingly using FusionAuth's role management and authorization features.

---

## Part Two: Technical Interview (1 hour)

The interview is split into three segments with a few minutes of buffer between each and time at the end for your questions.

---

### Segment 1: Code Walkthrough (~15 minutes)

Walk us through what you built. We want to understand your decisions, not just the output.

Come ready to cover:
- How your app is structured and why
- Any interesting choices you made or tradeoffs you navigated
- What you'd do differently or improve with more time
- Live code is preferred, so plan to screenshare your local environment

We're not looking for perfection. We're looking for how you think and communicate technical work.

---

### Segment 2: FusionAuth Demo (~15 minutes)

Give us a 15-minute demo of FusionAuth as if we're a technical audience evaluating the product. You're the SE and we're the prospect.

Structure it however makes sense to you, but cover:
- What FusionAuth is and why it matters
- A live walkthrough of at least two key features (authentication flow, user/role management, etc.)
- How it would integrate into a real application

**Evaluation criteria:**
- Clarity and confidence: can you explain technical concepts without over-engineering the explanation?
- Demo quality: is it smooth, logical, and well-scoped for the time?
- Technical depth: do you understand what's happening under the hood?
- Audience awareness: are you reading the room and adjusting?

---

### Segment 3: Prospect Architecture Review (~15 minutes)

We'll share a diagram from a fictional prospect, a real-world-style architecture or authentication flow. Your job is to ask us questions as if we're the customer and you're trying to understand their environment before recommending a solution.

This isn't a quiz and there are no trick questions. We want to see how you:
- Dig into ambiguity and ask the right clarifying questions
- Identify what's missing or unclear in a diagram
- Listen actively and adapt based on what we tell you
- Think out loud about how FusionAuth might (or might not) fit

You won't be expected to have all the answers. You'll be expected to ask good questions.

---

### Closing Q&A (~10 minutes)

We'll wrap up with time for you to ask us anything. Come with questions about the role, the team, how we work, or whatever's on your mind. This part of the conversation matters to us too.

---

## Scoring Rubric

| Area | Points | What We're Looking For |
|---|---|---|
| Code quality & completeness | 25 | Does it work? Is it reasonably clean? Are the right features implemented? |
| Technical communication | 25 | Can you explain what you built clearly and confidently? |
| Demo execution | 25 | Smooth, well-scoped, shows real product understanding |
| Discovery & curiosity | 25 | Quality of questions in the architecture review, do you dig in the right places? |
