# Day 3 – Your First AI Agent

## Project: Grocery Store Assistant

### Overview
In Day 3 of the DriveReady – AI Agents | One Person Company workshop, I built a Grocery Store Assistant using LangChain and Groq. The assistant answers customer questions about grocery products, prices, and delivery-related queries.

### Technologies Used
- Python
- Google Colab
- LangChain
- LangChain-Groq
- Groq API
- CSV

### Tasks Completed

#### Task 1 – Business Customization
- Created a custom SYSTEM prompt for a Grocery Store Assistant.
- Added grocery product details and prices.
- Connected the prompt to an LLM using LangChain.
- Implemented a conversation history.

#### Task 2 – Testing the Assistant
- Created `tests.csv` with 10 customer questions.
- Added expected keywords (`must_include`) for each test.
- Executed automated tests to evaluate the assistant.

**Baseline Results:**
- Total tests: 10
- Passed: 8
- Failed: 2
- Pass rate: 80%

#### Task 3 – Prompt Improvement
- Improved the SYSTEM prompt by adding a clear rule for unconfirmed delivery coverage and delivery times.
- Executed the tests again.

**Improved Results:**
- Total tests: 10
- Passed: 10
- Failed: 0
- Pass rate: 100%

#### Task 4 – Temperature Experiment
Changed the LLM temperature from `0.3` to `1.0` and executed the tests twice.

| Metric | Run 1 | Run 2 |
|---|---:|---:|
| Temperature | 1.0 | 1.0 |
| Passed | 10/10 | 10/10 |
| Pass Rate | 100% | 100% |

**Observation:** Both runs achieved a 100% pass rate. The PASS/FAIL results remained the same, although response wording may vary.

#### Task 5 – Agent or Not?
Classified three grocery business activities:

1. **Calculate grocery bill** – Plain Code
2. **Answer customer questions about grocery prices** – One LLM Call
3. **Handle complete customer orders** – Agent

### Key Learnings
- Understanding the difference between a chatbot and an AI agent.
- Creating custom SYSTEM prompts.
- Building an LLM chain using LangChain.
- Using conversation history.
- Creating CSV-based automated tests.
- Improving prompt quality through testing.
- Understanding the effect of temperature on LLM responses.
- Identifying tasks that require an AI agent.

### Final Outcome
Successfully completed all five Day 3 activities and improved the Grocery Store Assistant's test pass rate from **80% to 100%**.

**Status:** Completed ✅
