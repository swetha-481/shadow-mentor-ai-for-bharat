# Shadow Mentor – Requirements

## Problem
Developers often get stuck due to repeated errors or inefficient logic but do not know which underlying concept they are missing. Existing AI tools require manual prompts and often provide direct answers, reducing long-term learning.

## Proposed Solution
Shadow Mentor is an agentic AI companion that passively observes a developer’s workflow and detects teachable moments. When struggle is detected, it intervenes with Socratic, concept-first guidance instead of direct fixes.

## Functional Requirements
1. The system should monitor CLI/IDE execution logs.
2. The system should detect repeated errors or inefficient patterns.
3. The system should capture relevant code context.
4. The system should invoke an AI model to reason about missing concepts.
5. The system should generate Socratic hints instead of solutions.
6. The system should optionally provide voice explanations.
7. The system should store learning history for personalization.

## Non-Functional Requirements
1. The system should be lightweight and non-intrusive.
2. The system should not automatically modify user code.
3. The system should prioritize clarity and explainability.
4. The system should support scalability using serverless architecture.

## Constraints
- Limited to prototype-level implementation.
- Works on selected error scenarios for demonstration.
- Uses AWS managed services.
