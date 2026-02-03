Team Name

Shadow Mentor

Reason behind the name:
Shadow Mentor represents an AI that works quietly in the background (“Shadow”) and guides users through understanding rather than answers (“Mentor”). It mentors developers at the right moment without interrupting their workflow.

Problem Statement

Build an AI-powered solution that helps people learn faster, work smarter, or become more productive while building or understanding technology.

Team Leader Name

Sai Swetha

Brief About the Idea

Shadow Mentor is an agentic, context-aware AI learning companion that operates silently within a developer’s existing workflow (CLI/IDE). Instead of acting like a reactive chatbot, it passively observes coding activity to detect “teachable moments” such as repeated errors or inefficient logic. When such moments occur, it intervenes with Socratic hints and conceptual guidance, helping users understand why their code behaves the way it does rather than giving direct solutions.

How Is It Different From Existing Ideas?

Most existing AI tools are reactive answer engines that require users to manually ask questions and often provide direct solutions. Shadow Mentor is proactive and agentic—it decides when to intervene, identifies the missing concept, and guides users through questioning. It integrates directly into the workflow instead of pulling users into a separate chat interface.

How Will It Solve the Problem?

By detecting struggle in real time and providing conceptual nudges at the exact moment of friction, Shadow Mentor reduces frustration and prevents copy-paste dependency. It promotes independent problem-solving, improves conceptual understanding, and helps developers learn faster while staying productive.

USP (Unique Selling Points)

Agentic AI that automatically detects user struggle

Socratic, question-based guidance instead of direct answers

Workflow-native (CLI / IDE based)

Focus on concepts and long-term learning

List of Features

Teachable moment detection from CLI/IDE activity

Socratic hint generation using AI reasoning

Concept-first explanations instead of syntax fixes

Optional multilingual voice explanations

Learning memory for personalized guidance

Process Flow

Write/Run Code → Error Detected → Context Captured → AI Reasoning → Socratic Hint Delivered → Concept Understood → Learning Memory Updated

Architecture of the Proposed Solution

Frontend: CLI tool or IDE extension (VS Code)

AI Reasoning: Amazon Bedrock (LLM-based conceptual reasoning)

Orchestration: AWS Lambda for event-driven agent logic

State Management: Amazon DynamoDB for learning history

Voice Support: Amazon Polly for multilingual explanations

Technologies to Be Used

Amazon Bedrock

AWS Lambda

Amazon DynamoDB

Amazon Polly

Python

Estimated Implementation Cost (Optional)

The prototype can be developed using AWS free tier and hackathon credits with minimal operational cost.