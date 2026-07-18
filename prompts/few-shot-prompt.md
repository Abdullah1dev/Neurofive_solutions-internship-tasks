# Few-Shot Prompt

## Objective

Classify customer support messages into one of the following categories:

- Complaint
- Question
- Praise

### Instructions

You are given a list of customer support messages.

Classify each message into exactly **one** of the following categories:

- Complaint
- Question
- Praise

### Category Definitions

- **Complaint**: The customer expresses dissatisfaction, reports a problem, or mentions a negative experience.
- **Question**: The customer is asking for information or requesting clarification.
- **Praise**: The customer expresses appreciation, satisfaction, or positive feedback.

---

## Examples

### Example 1

**Message:**

> My order arrived with a broken screen and I want a replacement.

**Category:**

> Complaint

---

### Example 2

**Message:**

> Can I change my delivery address after placing an order?

**Category:**

> Question

---

### Example 3

**Message:**

> Your support team was incredibly helpful. Thank you!

**Category:**

> Praise

---

## Task

Now classify the following customer support messages.

### Output Requirements

Return the results in a Markdown table with the following columns:

| ID | Customer Message | Predicted Category |

Do not provide explanations or additional comments.

---

## Customer Messages

1. My order arrived two days late and the package was damaged.

2. How can I reset my account password?

3. Thank you for resolving my issue so quickly.

4. I was charged twice for the same purchase.

5. Is international shipping available for all products?

6. Your mobile application crashes every time I try to log in.

7. I really appreciate how friendly and helpful your support team was.

8. Where can I download my purchase invoice?

9. The quality of the product is much worse than I expected.

10. I absolutely love the new design of your application.