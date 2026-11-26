# Day 1 – AI Agents Workshop

## Project Title
AI Assistant for a Grocery Store

## Objective
The objective of this task is to understand the fundamentals of Large Language Models (LLMs) and perform practical experiments using the Groq API.

## Tasks Completed

### Task 1: Temperature Experiment
- Tested AI responses using temperature values 0.2 and 1.2.
- Generated three grocery store taglines for each temperature.
- Observed differences in creativity and response variation.

### Task 2: Hallucination
- Tested how AI responds when business facts are not provided.
- Asked: "Do you deliver to Kakinada?"
- Observed how AI generated an unsupported delivery confirmation.

### Task 3: No Memory
- Tested two separate API calls.
- Tested multiple messages in a single API request.
- Understood how conversation context is passed to an AI model.

### Task 4: Token Comparison
Compared prompt token usage for English and Telugu questions.

**Results:**
- English: 80 prompt tokens
- Telugu: 92 prompt tokens

### Task 5: Grocery Store AI Assistant
Created a grocery store assistant using:

**5 Business Facts**
1. The store sells groceries and daily household essentials.
2. The store provides food items and packaged products.
3. Customers can ask about available grocery products.
4. Product prices depend on the selected items.
5. Customers can contact the store to confirm product availability.

**3 Business Rules**
1. Never invent product prices or stock availability.
2. Never promise delivery unless it is confirmed.
3. If information is unknown, politely ask the customer to contact the store.

Tested the assistant with three customer questions about product availability, rice prices, and home delivery.

## Technologies Used
- Python
- Google Colab
- Groq API
- OpenAI Python Library

## AI Model
`openai/gpt-oss-20b`

## Learning Outcomes
- Understanding temperature and creativity.
- Identifying AI hallucinations.
- Understanding conversation memory.
- Comparing token usage across languages.
- Creating a business-specific AI assistant.

## Author
Kavitha Chandrika

B.Tech – Computer Science and Engineering (AI & ML)
