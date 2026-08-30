# AI Response Evaluation Samples

This repository is a small portfolio of independently created AI response evaluation cases.

I use these examples to document how I compare model outputs, identify the main quality issue, and write a concise justification for a preference decision. The focus is on practical human evaluation rather than automated benchmark scoring.

## What I evaluate

Depending on the task, I look at factors such as:

- instruction following
- factual accuracy and groundedness
- relevance to the user’s request
- completeness
- clarity and organization
- tone and language quality
- unnecessary or unsupported claims
- safety, when it is relevant to the task

Not every case uses every criterion. I try to focus on the issues that actually affect the quality of the response instead of applying a long checklist mechanically.

## Evaluation approach

Most examples use a pairwise format:

1. Read the task and identify the user’s main requirements.
2. Review Response A and Response B independently.
3. Check whether either response misses an instruction or introduces a factual or reasoning error.
4. Compare the responses on the criteria that matter for that specific task.
5. Select the stronger response, or a tie when the difference is not meaningful.
6. Write a short justification based on observable evidence in the responses.

I do not treat a longer answer as automatically better. A concise response can be stronger if it follows the request more closely and avoids unsupported detail.

## Case set

The examples in this repository cover several recurring evaluation problems:

- Instruction following
- Factuality and unsupported claims
- Relevance and unnecessary information
- Completeness
- Style and clarity
- Close-call or tie decisions

Each case includes the original task, two candidate responses, the evaluation decision, and a brief explanation of the reasoning behind that decision.

## Notes on the examples

All prompts and responses in this repository are independently created for portfolio and practice purposes.

They do not contain client data, proprietary prompts, internal project guidelines, confidential task content, or material copied from paid evaluation work.

The aim is to show the evaluation process clearly without exposing restricted work.

## About

I work with AI evaluation, data annotation, language quality review, and prompt engineering, with a particular focus on Turkish-language tasks.

Portfolio: https://yeldaozgezerim.github.io/

GitHub: https://github.com/yeldaozgezerim
