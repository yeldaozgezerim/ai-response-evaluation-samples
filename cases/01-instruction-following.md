# Case 01 — Instruction Following

## Task

Rewrite the following customer-service message:

> We can't process your refund because the return arrived 12 days after the 30-day return window.

Requirements:

- Use a neutral but empathetic tone.
- Use no more than two sentences.
- Do not use the words "unfortunately" or "policy".
- Do not promise or suggest that an exception may be available.
- Clearly explain why the refund cannot be processed.

## Response A

I understand this is disappointing. We can’t process the refund because the return arrived 12 days after the 30-day return period had ended.

## Response B

Unfortunately, we can’t process the refund because our policy allows returns only within 30 days. I’m sorry for the inconvenience, but you can contact support to ask whether an exception can be made.

## Decision

**Response A is better.**

## What I looked at

- Did the response follow the explicit instructions?
- Was the reason for refusing the refund clear?
- Did the tone stay neutral and reasonably empathetic?
- Did the response add anything the user specifically asked it not to add?

## Why I chose A

Response A does what the prompt asks without adding extra information. It stays within two sentences, explains the reason for the decision, and avoids both prohibited words.

Response B gives the correct basic explanation, but it breaks several clear instructions. It uses “unfortunately” and “policy,” and it tells the customer to ask about an exception even though the prompt specifically says not to suggest that one may be available.

For this task, those instruction-following problems matter more than the fact that Response B is otherwise understandable.

## Final assessment

**Preferred: Response A**

The main reason is instruction following. Response A covers the necessary information cleanly, while Response B introduces three avoidable violations of the user’s requirements.
