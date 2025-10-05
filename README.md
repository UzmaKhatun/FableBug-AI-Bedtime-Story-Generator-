# 🌙 FableBug AI - Bedtime Story Generator

Turn your imagination into heartwarming bedtime stories for your little ones using AI-powered storytelling! ✨

---

## 📖 About
FableBug AI is an intelligent bedtime story generator that creates unique, engaging, and age-appropriate stories for children. Using advanced AI technology, it crafts personalized narratives complete with beautiful illustrations, making every bedtime special and memorable.

--- 

## 🎥 Video Demo
Check out FableBug AI in action:<br>
📺 [Watch Demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7370693176103235584/)

---

## 🚀 Try It Out
Experience the magic yourself: [Launch FableBug AI](https://fable-bug-ai.netlify.app/)

----

## 🚀 Overview
FableBug AI is a multi-agent AI workflow that automatically:

- Generates creative stories using AI
- Creates scene-by-scene illustrations
- Stores the stories & images securely in the cloud
- Delivers everything as a beautiful downloadable storybook (PDF)
 
It’s built with automation tools, AI models, and integrations that work together seamlessly.

---

## 🧠 Tech Stack
|Technology|	Purpose|
|----------|----------------|
|Front-end Form	| Collects inputs like character name, gender, moral, number of pages, and art style|
|n8n |	Core automation platform to orchestrate all AI tasks and workflows|
|Supabase |	Serves as the cloud database to store story data and user activity logs|
|Perspective API	|Generates creative, structured storylines and dialogues|
|Image Generation | Creates scene-wise illustrations from AI-generated prompts|
|HTTP Nodes |	Used for sending API requests to image generation endpoints|
|Cloud Storage |	Stores generated images|
|Webhook |	Connects frontend form (user input) with backend automation|

--- 

##  How It Works
- User Input Form → Collects story preferences (character, moral, pages, style).
- Webhook Trigger (Frontend → Backend) → Sends input to the n8n workflow.
- Planner Agent → Uses LLM to generate the story blueprint.
- Writer Agent → Use to generate full story.
- Perspective API → To check the toxicity of generated story.
- Illustrator Agent → Create prompts for image generation.
- Http node → For image generation then story it to the cloud.
- Supabase → To store user log.

---

### Made with ❤️ by <strong> Uzma Khatun </strong>

Author: Uzma Khatun <br>
Role: AI/ML Engineer & Automation Developer <br>
### Contact:
📧 Email: [Uzma Khatun](uzmakhatun0205@gmail.com) <br>
💼 LinkedIn: [Uzma Khatun](https://www.linkedin.com/in/uzma-khatun-88b990334/) <br>
🐙 GitHub: [UzmaKhatun](https://github.com/UzmaKhatun)

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub — it helps others discover it!
