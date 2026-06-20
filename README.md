# Corporate_Communications_Manager-
Corporate Communications Manager .json persona for an artificial intelligence
# Corporate Communications Manager AI Persona

## Overview
This repository contains a JSON persona designed to transform a standard Large Language Model (LLM) into a strategic Corporate Communications Manager. This AI is not just a "writer"; it is a **strategic advisor** focused on reputation management, stakeholder trust, and message clarity.

## Why this Persona?
Corporate communication is high-stakes. Generic AI often generates generic, "fluffy" text that lacks strategic depth. This persona solves that by encoding the rules of crisis communication, media dynamics, and executive presence into the AI's response logic.

## Key Features
- **Strategic Framing:** Refuses to "spin" lies; focuses on "strategic framing."
- **Human-Centric:** Prioritizes employee and customer sentiment over corporate jargon.
- **Versatile Output:** Capable of drafting everything from a high-level CEO memo to a 280-character social post.
- **Risk Management:** Automatically flags high-risk statements (e.g., financial projections, legal admissions) for human review.

## How to Install/Use

### Step 1: Load the Persona
Copy the contents of `corporate_communications_manager.json` into the system prompt or "Instructions" field of your preferred AI interface (e.g., ChatGPT, Claude, or custom API).

### Step 2: Configure Context
Before asking for a draft, provide the following context to the AI:
1.  **Company Name:** [Your Company]
2.  **Industry:** [Tech/Healthcare/Finance/etc.]
3.  **Situation:** (Proactive announcement, Reactive to a crisis, or Internal update)

### Step 3: Prompt Examples
Here are examples of how to interact with the persona:

- **Crisis Mode:** *"We are experiencing a minor data breach. No customer data has been compromised, but 5,000 passwords were encrypted. Draft a holding statement for the press."*
- **Executive Comms:** *"We just acquired a competitor. Write an internal Slack message from the CEO to boost morale and address layoff fears."*
- **Media Relations:** *"Our CEO is going on CNBC. Give me 3 questions they might ask about our declining stock, and how to pivot to our new product line."*

## Persona Logic
- **The "Trusted Advisor" Vibe:** The AI will ask *you* questions before generating text. This ensures accuracy and alignment with your actual strategy.
- **Tone Adjustment:** The AI automatically adjusts its tone based on the channel:
    - *Internal:* Uses emojis (sparingly), inclusive language ("we"), and transparency.
    - *External:* Uses quotes, third-person perspective, and legally sound phrasing.

## Customization Tips
Feel free to modify the JSON file to match your specific industry legal requirements or preferred vocabulary. For example, you can add `"legal_blacklist": ["guarantee", "promise", "risk-free"]` to the rules section if you operate in a regulated sector.

## License
[Specify your license, e.g., MIT or Proprietary]
