AI Financial Coach – Multi-Agent Personal Finance Advisor
An AI-powered personal finance advisor that analyzes income, expenses, and debts to provide actionable recommendations for budgeting, savings, and debt reduction using a multi-agent architecture powered by Google Agent Development Kit (ADK) and Gemini.
Project Overview
Managing personal finances requires analyzing multiple factors such as spending behavior, savings discipline, and debt obligations. This project simulates a team of financial advisors using specialized AI agents, each responsible for a specific financial task.
Instead of relying on a single large language model, this system uses sequential agent orchestration where each agent:
Solves a focused problem
Produces structured outputs
Passes insights to the next agent via shared state

The application features an interactive Streamlit UI, supports CSV-based transaction uploads, and generates visual financial insights.
AI Agent Architecture
1️⃣ Budget Analysis Agent
Categorizes expenses
Identifies spending patterns
Detects overspending
Recommends cost-reduction opportunities
2️⃣ Savings Strategy Agent
Calculates emergency fund requirements
Suggests monthly savings allocations
Recommends automated saving techniques
3️⃣ Debt Reduction Agent
Analyzes debts by balance and interest rate
Compares Avalanche vs Snowball payoff strategies
Estimates time to debt freedom and interest paid

✨ Key Features
📊 Expense Analysis & Visualization
📁 CSV Transaction Upload with Validation
✍️ Manual Expense Entry Option
🤖 Multi-Agent AI Reasoning
📈 Savings & Emergency Fund Planning
💳 Debt Payoff Optimization
🧾 Structured LLM Outputs using Pydantic
🔐 Privacy-First (No Data Storage)
Tech Stack

Language: Python
Frontend: Streamlit
AI Framework: Google Agent Development Kit
LLM: Gemini
Data Processing: Pandas
Visualization: Plotly
Validation: Pydantic
Async Orchestration: AsyncIO
