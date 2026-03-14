# ECOTWIN-AI
EcoTwin AI is an AI-powered sustainability platform that analyzes purchases, estimates carbon footprints, and provides personalized recommendations via an interactive dashboard and AI chat assistant. Includes Advanced Hydroponics and BioPod simulations for environmental impact modeling.
EcoTwin AI 🌍🤖
AI-Powered Carbon Footprint Tracking and Sustainability Assistant
EcoTwin AI analyzes purchase data to estimate carbon footprints and provide personalized sustainability recommendations. Features include an AI chat assistant, interactive dashboards, Advanced Hydroponics modeling, and BioPod environmental simulations.
Features
AI Receipt Analysis – extract and categorize items from receipts
Carbon Impact Dashboard – visualizes emissions by category and over time
AI Sustainability Chatbox – interactive recommendations in natural language
Impact Simulator – models how lifestyle changes affect emissions
Advanced Hydroponics System – links dietary choices to sustainability
BioPod Environmental Simulation – models community-level ecological impact
Antigravity Optimization – balances cost, convenience, and environmental benefit
Built With
Languages: Python, JavaScript, React.js
Frameworks & Libraries: Railtracks, Flask / FastAPI, Pandas, NumPy, Plotly, D3.js
AI & APIs: OpenAI API, Google Gemini API, Generative Media Tools
Databases: PostgreSQL / Firebase
Cloud & Platforms: Google Cloud Platform (GCP)
Setup Instructions
Clone the repo:

git clone <GITHUB_LINK>
cd EcoTwin-AI

Install dependencies:

pip install -r requirements.txt

Add API keys to .env:

OPENAI_API_KEY=<YOUR_OPENAI_KEY>
GEMINI_API_KEY=<YOUR_GEMINI_KEY>

Run the backend:

python app.py

Start the frontend:

cd frontend
npm install
npm start

Open http://localhost:3000
 to access the platform.

Project Architecture
User Input (Receipts / Data)
          |
          v
  ┌───────────────────┐
  │   Data Analysis    │
  │      Agent         │
  └───────────────────┘
          |
          v
  ┌───────────────────┐
  │ Carbon Impact Agent│
  └───────────────────┘
          |
          v
  ┌───────────────────┐
  │ Recommendation    │
  │ Agent / Chatbox   │
  └───────────────────┘
          |
Dashboard / Advanced Hydroponics / BioPod Simulation
How We Used AI
OpenAI API: Interprets purchase data, generates insights
Google Gemini API: Reasoning and recommendations
Generative Media Tools: Interactive charts and dashboards
Antigravity Optimization Models: Balances trade-offs for sustainability
Challenges
Mapping real-world purchase data to carbon emissions
Simplifying technical environmental data for users
Coordinating multiple AI agents with Railtracks framework
Accomplishments
Built a modular AI system combining multiple AI APIs
Developed interactive sustainability dashboards
Created AI chatbox assistant for personalized advice
Integrated Advanced Hydroponics and BioPod simulations
Explored Antigravity optimization for practical recommendations
Future Improvements
Real-time purchase tracking through financial integrations
More precise carbon footprint datasets
Mobile app for daily tracking
Expanded environmental simulations
AI-powered sustainability planning for individuals and communities

License
MIT License © 2026 EcoTwin AI Team

Contact

Email: <YOUR_EMAIL>
GitHub: <GITHUB_LINK>
