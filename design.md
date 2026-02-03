# Shadow Mentor – System Design

## Architecture Overview
Shadow Mentor follows an event-driven, agentic architecture designed to integrate seamlessly into a developer’s workflow.

## Components

### 1. CLI / IDE Extension
- Captures execution logs and error patterns.
- Sends context to backend services.

### 2. AWS Lambda (Agent Orchestration)
- Receives context from CLI/IDE.
- Determines whether a teachable moment exists.
- Orchestrates AI reasoning and response generation.

### 3. Amazon Bedrock
- Performs reasoning on captured context.
- Identifies missing conceptual understanding.
- Generates Socratic, question-based hints.

### 4. Amazon DynamoDB
- Stores learning history and past struggles.
- Prevents repeated guidance on the same concept.

### 5. Amazon Polly
- Converts hints into multilingual voice output.
- Improves accessibility for diverse learners.

## Data Flow
1. Developer runs code.
2. Error or inefficiency detected.
3. Context sent to AWS Lambda.
4. Lambda invokes Amazon Bedrock.
5. Socratic hint generated.
6. Hint delivered to user.
7. Learning context stored in DynamoDB.

## Design Principles
- Agentic decision-making
- Minimal user interruption
- Concept-first learning
- Responsible AI usage
