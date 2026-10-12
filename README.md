# 🤖 Digital Replica — Carbon Copy AI Agent

> **My AI Digital Replica & Portfolio Agent built live on stream.**

`Carbon Copy` is a zero-abstraction AI agent that acts as my digital interactive portfolio. It is designed to engage with recruiters, founders, and developers on my behalf, answering questions accurately while capturing real-time lead information.

---

🔴IMPORTANT NOTE: This is actually i am building on the livestream for my youtube, for my deployed version of it you can check my portfolio and obviously it's repo is private.

---

## 🎯 Key Features & Capabilities

### 1. Strict Context Guardrails
* Built with strict system instructions to keep interactions focused purely on my background, tech stack, projects, and professional inquiries.
* Refuses off-topic prompts to maintain a professional standard.

### 2. Automated Lead Generation
* When a visitor wants to connect, hire, or collaborate, the agent collects their name, contact details, and intent.
* Immediately dispatches a mobile notification to me containing the lead details and conversation context.

### 3. Smart Knowledge Gap Handling & Real-time Alerts
* If asked a technical or personal question outside its current context, it politely informs the user and admits its limitation.
* Automatically triggers a real-time notification to my phone with the unanswered query, allowing me to review, verify, and update the agent's knowledge base.

---

## 📺 Build In Public

I am building this project **100% live on YouTube**. Since I am noob in livestreaming so quality obviously will increase as we will go by.

* **Livestream Playlist:** [Watch the Live Build Series Here](https://www.youtube.com/watch?v=GoKOx_kOXu4&list=PLbUvdrQl0b-w)

---

## 🛠️ Tech Stack & Setup

* **Language:** Python
* **Package Manager:** `uv`
* **Interface:** Gradio
* **API / Core Engine:** Raw OpenAI API (No heavy framework abstractions)

```bash
# 1. Clone the repository
git clone [https://github.com/your-username/digital-replica-carbon-copy.git](https://github.com/your-username/digital-replica-carbon-copy.git)
cd "src/digitalai_agent"

# 2. Initialise and sync the project with uv ( make sure you have uv package manager installed in your system , if not then use pip equivalent commands for them"
uv init
uv sync

# 3. Configure environment variables (.env)
API_KEY=your_key_here
# ( visit the .env.local for more clarification)
# (obviously as we go, more env variables will be added.)

# 4. Run the application
uv run
