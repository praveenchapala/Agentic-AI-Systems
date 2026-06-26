# 🤖 AI Pull Request Reviewer System

An AI-powered multi-agent system that automatically reviews GitHub Pull Requests, analyzes code changes, identifies risks, and generates intelligent review recommendations.

## 📌 Project Overview

Code reviews are one of the most important activities in software development. However, senior engineers often spend significant time reviewing Pull Requests manually for:

* Code Quality
* Security Issues
* Performance Concerns
* Documentation Standards
* Overall Risk Assessment

This project automates the review process by building a team of AI agents that analyze Pull Requests and provide actionable recommendations.

---

# 🚀 Features

✅ GitHub Integration

✅ Pull Request Analysis

✅ Multi-Agent Architecture

✅ Code Quality Review

✅ Security Review

✅ Performance Analysis

✅ Risk Scoring Engine

✅ Final Review Report Generation

✅ Email Notifications

✅ GitHub Comment Generation

---

# 🏗️ System Architecture

```text
GitHub Pull Request
          │
          ▼
Fetch Pull Request Details
          │
          ▼
Fetch Changed Files (Diff/Patch)
          │
          ▼
 ┌──────────────────────────┐
 │      AI Review Agents    │
 └──────────────────────────┘
          │
          ├── PR Summary Agent
          ├── Code Quality Reviewer
          ├── Security Reviewer
          └── Performance Reviewer
          │
          ▼
      Merge Results
          │
          ▼
     Risk Scoring Agent
          │
          ▼
     Final Review Agent
          │
          ▼
 ┌──────────────────────────┐
 │ Notification Services    │
 └──────────────────────────┘
          │
          ├── GitHub Comment
          └── Email Notification
```

---

# 🤖 AI Agents

## 1. PR Summary Agent

Responsibilities:

* Understand the purpose of the PR
* Identify files modified
* Determine change type
* Estimate complexity
* Generate a high-level summary

---

## 2. Code Quality Reviewer

Responsibilities:

* Review naming conventions
* Analyze formatting
* Validate documentation quality
* Check coding best practices
* Provide improvement suggestions

---

## 3. Security Reviewer

Responsibilities:

* Detect hardcoded secrets
* Identify API keys and credentials
* Check authentication issues
* Detect security vulnerabilities
* Generate security recommendations

---

## 4. Performance Reviewer

Responsibilities:

* Analyze performance bottlenecks
* Detect inefficient logic
* Identify scalability concerns
* Review resource utilization
* Generate optimization suggestions

---

## 5. Risk Scoring Agent

Responsibilities:

* Aggregate findings from all agents
* Calculate overall risk score
* Determine risk level
* Make approval recommendations

---

## 6. Final Review Agent

Responsibilities:

* Generate final review report
* Prepare GitHub comment
* Generate email notification
* Provide merge recommendation

---

# 🔄 Workflow

```text
Developer Creates PR
        │
        ▼
AI Pull Request Reviewer Triggered
        │
        ▼
Retrieve PR Details and Code Changes
        │
        ▼
Run AI Review Agents
        │
        ▼
Generate Risk Assessment
        │
        ▼
Create Final Review Report
        │
        ▼
Send Notifications
        │
        ├── GitHub Comment
        └── Email Report
```

---

# 🛠️ Technologies Used

* n8n
* GitHub API
* Groq LLM
* AI Agents
* JSON Structured Outputs
* Prompt Engineering
* Workflow Automation

---

# 📊 Sample Output

```json
{
  "overall_risk_score": 12,
  "risk_level": "Low",
  "decision": "Approve",
  "reasoning": "Documentation-only change with no security or performance concerns.",
  "key_findings": [
    "No security issues found",
    "No performance concerns",
    "Minor formatting recommendations"
  ]
}
```

---

# 📧 Sample Review Comment

```markdown
## 🤖 AI Pull Request Review

### Decision
✅ Approve

### Risk Score
12 / 100

### Risk Level
Low

### Findings
- No security issues found
- No performance concerns
- Minor formatting suggestions

### Recommendation
Approved for merge.
```

---

# 📚 Key Learnings

* GitHub API Integration
* Pull Request Lifecycle
* Multi-Agent System Design
* AI-powered Code Review
* Structured Output Parsing
* Prompt Engineering
* Workflow Automation
* Engineering Productivity Tools
* Event-Driven Architecture

---

# 🎯 Future Enhancements

* Automatic PR Approval
* Review Comments on Specific Lines of Code
* Integration with Jira
* Slack and Microsoft Teams Notifications
* Regression Prediction Agent
* Test Coverage Agent
* Deployment Risk Analysis
* Historical PR Analytics Dashboard
* Learning from Previous Reviews

---

# 🌟 Why This Project?

This project demonstrates how Agentic AI can automate software engineering workflows and improve developer productivity by assisting teams in reviewing Pull Requests more efficiently.

It simulates how enterprise tools such as:

* GitHub Copilot Reviews
* CodeRabbit
* Amazon CodeGuru Reviewer
* SonarQube
* Atlassian Intelligence

use AI to support engineering teams.

---

## 👨‍💻 Built as part of my #100DaysOfAgenticAI journey.

**Day 40 – Building an AI Pull Request Reviewer System**
