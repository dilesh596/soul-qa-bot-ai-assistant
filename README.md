# Soul QA Bot: Smarter AI That Works Offline

#devchallenge  
#weekendchallenge  
#hf26challenge

# Hacktoberfest Weekend Challenge: Build for a Friend Submission 🤝

This project is a submission for the Hacktoberfest Weekend Challenge: Build for a Friend.

## What I Built

Soul QA Bot is a smart AI assistant that works both with and without an internet connection. It is designed to help students and learners solve problems, write simple code, summarize tasks, and answer questions even when connectivity is limited.

It can provide helpful responses in offline mode, and when the internet is available, it can route requests to online services for broader research and up-to-date information. The core idea is simple: students should not be blocked by expensive subscriptions, poor connectivity, or lack of hardware.

This project was built for my sister and for students like her who need AI support for learning but cannot afford expensive AI plans or premium subscriptions.

## Demo

- YouTube Demo: https://youtu.be/Ngq9Llm6L7E?si=4-5bmeA5ESNwQ54y

## Code

- GitHub Repository: https://github.com/dilesh596/soul-qa-bot-ai-assistant

## Why This Project Matters

Many students want access to AI tools for writing, learning, coding, and research, but premium AI subscriptions are often too expensive. In some areas, internet access is also unreliable. Soul QA Bot addresses both problems by combining a lightweight offline AI model with optional online support when connectivity is available.

This means the assistant remains useful in real-world student scenarios:

- studying in low-connectivity areas
- working on assignments without paying for subscriptions
- running on affordable laptops or low-end devices
- getting instant help without depending on a constant internet connection

## How I Built It

Soul QA Bot is designed to balance low hardware requirements with practical AI functionality. The project uses a hybrid approach to keep the system accessible and useful.

### Core Technology

- Open-weight model: Google's Gemma 3:1B
- Local inference: Ollama
- Routing logic: custom app logic that checks internet connectivity
- Runtime behavior:
  - online: use connected AI/web research capabilities
  - offline: switch to a local model and continue answering without interruption

### Why This Matters

The offline mode is powered by Ollama, which allows lightweight local LLMs to run directly on a machine without requiring a cloud API. The model used here, Gemma 3:1B, is small enough to make practical local inference possible on student laptops and older hardware.

This keeps the experience fast, affordable, and useful even in low-resource environments.

## Open Innovation and Accessibility

Open innovation is the foundation of this project. Without open-source tools, local models, and community-driven AI development, this kind of accessible assistant would not be feasible for students on a budget.

### Benefits of Open Innovation

- No monthly paywall for AI access
- Works without depending on expensive subscriptions
- Enables AI usage even in offline or low-connectivity conditions
- Encourages community learning and building
- Makes advanced AI more accessible to students and creators

### Why Open-Source Matters Here

Closed-source AI tools often require recurring subscriptions, internet dependency, and platform access restrictions. Soul QA Bot aims to bring AI closer to the community by using open-weight models, local inference, and a hybrid architecture that can work even when online services are unavailable.

## Project Flow

Here is how a typical session works:

1. The app checks whether the device has an internet connection.
2. It prepares the system context and user prompt.
3. If online, it can use external services for deeper research and broader answers.
4. If offline, it automatically routes the request to the local model powered by Ollama.
5. The result is returned to the user without breaking the workflow.

This hybrid flow makes the app resilient and practical for daily student use.

## Prize Categories

I am entering Soul QA Bot into the following official Hacktoberfest challenge categories:

### Best Use of Gemma
This project is built around Google's open-weight Gemma 3:1B model and uses it for local AI inference via Ollama. The result is a low-cost, student-friendly AI assistant that can run on consumer hardware.

### Overall Best Open-Source AI Project
Soul QA Bot focuses on open-source accessibility, affordable AI, and student empowerment. It is designed to lower barriers and make AI more useful in everyday learning scenarios.

## The Team

- Dilesh Zingare
- DEV Profile: https://dev.to/dilesh596

This project is being submitted as a solo developer contribution with a focus on accessibility, education, and open-source impact.

## Future Goals

- improve offline response quality
- add better context memory for student workflows
- support code explanations and debugging
- improve hybrid online/offline routing
- make the assistant more beginner-friendly for learning

## Final Note

Soul QA Bot is my effort to build a smarter and more accessible AI companion for students. It combines the power of open-source models with practical offline usability so people can learn and work without depending on expensive subscriptions or constant internet access.

---

Built with the goal of making AI more accessible, affordable, and useful for students everywhere.
