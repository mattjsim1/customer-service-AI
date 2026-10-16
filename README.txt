# AI Customer Service Agent

An intelligent, context-aware customer service chatbot powered by the Anthropic Claude Sonnet API. This project demonstrates the integration of LLMs into business ops using agentic workflows to help automate support, handle user queries, and intelligently route complex issues.

## Tech Stack
* **Core:** Python
* **AI & Orchestration:** Anthropic Claude Sonnet, LangChain, LangGraph
* **Cloud Infrastructure:** AWS

## Key Features
* **Stateful Agentic Workflows:** Utilizes LangGraph to manage complex, multi-turn conversation states and dynamic routing.
* **Contextual Responses:** Maintains memory and conversation history via LangChain to provide accurate, continuous support.
* **Cloud Deployment:** Hosted and executed within AWS, demonstrating scalable cloud architecture.

## Getting Started

### Prerequisites
* Python 3.10+
* An active Anthropic API Key
* AWS CLI configured (if running cloud deployments locally)

### Installation
1. Clone the repository:
   `git clone https://github.com/mattjsim1/customer-service-AI.git`
2. Install dependencies:
   `pip install -r requirements.txt` 
3. Set up your environment variables:
   Create a `.env` file and add your API key: `ANTHROPIC_API_KEY=your_api_key_here`
4. Run the application:
   `python main.py`
