
# Shadow Mentor

Shadow Mentor is an AI-powered learning assistant designed to support developers while they work, without interrupting their workflow.

Instead of acting like a chatbot that waits for questions, Shadow Mentor quietly observes coding activity and identifies “teachable moments” such as repeated errors or inefficient logic. At the right time, it provides guidance that helps developers understand concepts instead of simply giving answers.

---

## Problem

Developers often rely on AI tools that provide instant solutions without improving understanding. This can lead to copy-paste dependency and reduced problem-solving ability.

There is a need for a system that helps developers:

* Learn faster
* Understand concepts better
* Stay productive

while continuing their normal workflow.

---

## Solution

Shadow Mentor is designed as a workflow-integrated AI assistant that:

* Detects moments where a developer may be struggling
* Understands the coding context
* Provides hints instead of direct answers
* Encourages concept-based learning

The system focuses on guidance rather than solution delivery.

---

## Key Features

* Detects teachable moments during coding
* Provides Socratic-style hints
* Encourages conceptual understanding
* Works within CLI or IDE environment
* Maintains learning memory for personalization
* Supports multilingual voice guidance (optional)

---

## How It Works

Code Execution → Error Detection → Context Capture → AI Reasoning → Hint Generation → Concept Understanding → Learning Memory Update

---

## Architecture Overview

* Frontend: CLI Tool / IDE Extension
* AI Reasoning: Amazon Bedrock
* Orchestration: AWS Lambda
* State Management: Amazon DynamoDB
* Voice Support: Amazon Polly

---

## Technologies Used

* Python
* Amazon Bedrock
* AWS Lambda
* Amazon DynamoDB
* Amazon Polly

---

## Future Scope

* Integration with more IDEs
* Improved learning personalization
* Document-based concept support
* Advanced struggle detection

---

## Conclusion

Shadow Mentor aims to improve how developers learn while working by providing timely guidance instead of direct solutions.

It promotes independent thinking and supports long-term skill development without disrupting workflow.

---

