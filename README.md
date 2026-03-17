# AI Shopping Assistant

This project is an AI-powered shopping assistant that processes natural language queries and retrieves relevant products from a structured dataset.

Instead of focusing only on the model, the goal of this project was to explore how AI can be integrated into a backend system to support real-world user queries and decision-making.

---

## What it does

- Takes user input in natural language (e.g. "I want something sporty under £100")
- Extracts key information such as category, price range, and style
- Converts the query into structured filters
- Retrieves matching products from a database
- Returns results in a simple and relevant way

---

## Key Features

- **Natural language processing**  
  Basic intent recognition trained on custom data using scikit-learn

- **Retrieval-based pipeline**  
  Transforms user queries into structured search parameters

- **Dynamic filtering**  
  Supports filtering by category, price, and style

- **Fuzzy matching**  
  Handles vague inputs like "classic" or "a bit sporty"

- **Context-aware interaction**  
  Can ask follow-up questions if key information is missing

- **Modular backend design**  
  Code is structured to allow easy extension and experimentation

---

## How it works

The system is designed as a simple pipeline:

1. User input  
2. Intent recognition + keyword extraction  
3. Convert to structured filters  
4. Query database  
5. Return results  

The focus was not just getting output, but making sure the flow is clear and extendable.

---

## Tech Stack

- Python  
- scikit-learn (intent classification)  
- MySQL (product data)  
- Custom filtering and matching logic  

---

## Why I built this

I wanted to move beyond just learning individual concepts and actually build something end-to-end.

One thing I found interesting was how much of the challenge is not the model itself, but everything around it — how queries are interpreted, how results are filtered, and how the system behaves when information is incomplete.

This project helped me understand how AI fits into a larger system rather than existing in isolation.

---

## What I learned

- Structuring a system is harder than writing individual functions  
- AI is only one part of the solution — logic and flow matter just as much  
- Handling edge cases (unclear input, missing info) is where most complexity comes from  
- Building something that “feels natural” requires iteration and testing  

---

## Possible Improvements

- Replace rule-based logic with LLM-based query understanding  
- Add ranking/scoring for better recommendations  
- Improve dialogue handling for more natural conversations  
- Deploy as an API or web service  

---

## Notes

This project is fully implemented in Python with a focus on clarity and modularity, so it can be extended into a more production-ready system in the future.
