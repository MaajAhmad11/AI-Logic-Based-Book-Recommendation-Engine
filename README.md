# AI Logic-Based Book Recommendation Engine

A logic-based personalization engine built in Python that pairs readers with books based on categorical preference vectors: Genre, Reading Length, and Narrative Tone. This system features dynamic constraint scaling to handle edge cases where strict filtering criteria yield zero exact matches.

## 🚀 Key Features
- **Weighted Attribute Accumulator:** Prioritizes vital parameters by scoring matching categories dynamically (Genre: `+3`, Tone: `+2`, Length: `+1`) to sort outcomes by statistical relevance.
- **Dynamic Constraint Scaling (Fallback Mechanic):** Instead of returning an empty list when strict matches fail, the engine automatically degrades constraints to seek partial matches on secondary attributes, ensuring zero dead-ends for the user.
- **Data Sanitization:** Built-in tolerance for casing discrepancies and miscellaneous spacing to protect against silent comparison failures.

## 💻 Tech Stack & Core Concepts
- **Language:** Python 3.x
- **Core Concepts:** Rule-based AI, Content matching logic, Constraint satisfaction, Data normalization.

## 🛠️ How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/AI-Book-Recommendation-Engine.git](https://github.com/YOUR_GITHUB_USERNAME/AI-Book-Recommendation-Engine.git)
