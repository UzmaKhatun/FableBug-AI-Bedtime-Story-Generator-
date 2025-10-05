# 🌙 FableBug AI - Bedtime Story Generator

Turn your imagination into heartwarming bedtime stories for your little ones using AI-powered storytelling! ✨

## 📖 About
FableBug AI is an intelligent bedtime story generator that creates unique, engaging, and age-appropriate stories for children. Using advanced AI technology, it crafts personalized narratives complete with beautiful illustrations, making every bedtime special and memorable.

## 🎥 Video Demo

Check out FableBug AI in action:<br>
📺 [Watch Demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7370693176103235584/)


Stay tuned for a complete walkthrough of how FableBug AI brings your ideas to life 💫

🚀 Overview

FableBug AI is a multi-agent AI workflow that automatically:

Generates creative stories using AI

Creates scene-by-scene illustrations

Stores the stories & images securely in the cloud

Delivers everything as a beautiful downloadable storybook (PDF)

It’s built with automation tools, AI models, and integrations that work together seamlessly.

🧠 Tech Stack
Technology	Purpose
n8n	Core automation platform to orchestrate all AI tasks and workflows
Perspective AI API	Generates creative, structured storylines and dialogues
Supabase	Serves as the cloud database to store story data and user activity logs
HTTP API Nodes	Used for sending API requests to AI text/image generation endpoints
Image Generation API	Creates scene-wise illustrations from AI-generated prompts
Cloud Storage (Supabase Bucket / Google Drive)	Stores generated images and final story PDFs
Google Docs API	Compiles story text and illustrations into formatted storybooks
Webhook	Connects frontend form (user input) with backend automation
Front-end Form	Collects inputs like character name, gender, moral, number of pages, and art style
n8n Agents	Handle specialized tasks like:
🧙‍♂️ StoryCrafter Agent (text generation)
🎨 Illustrator Agent (prompt crafting + image generation)
📘 Compiler Agent (story PDF creation and upload)
💡 Workflow Summary

User Input Form → Collects story preferences (character, moral, pages, style).

Webhook Trigger (Frontend → Backend) → Sends input to the n8n workflow.

StoryCrafter Agent → Uses AI (Perspective AI) to generate the story text.

Illustrator Agent → Creates image prompts and calls the image generation API via HTTP.

Compiler Agent → Uploads images to Supabase, generates a Google Doc, and exports a story PDF.

Storage + Delivery → PDF stored in the cloud and link returned to user.

📂 Repository Structure
FableBug-AI-Bedtime-Story-Generator/
│
├── Story PDF/                # Final generated story PDFs
├── Story Screenshots/        # Screenshots for documentation and demo
├── README.md                 # Project documentation (this file)
└── (You can also add)
    ├── .env.example          # Example for environment variables
    ├── requirements.txt      # If using Python in some automation
    └── n8n_workflow.json     # Export of your n8n workflow (recommended!)

🔧 Recommended Files to Add

✅ .env.example — with placeholders for your environment variables, e.g.:

SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
PERSPECTIVE_AI_API_KEY=your_api_key
IMAGE_GEN_API_KEY=your_image_gen_api
WEBHOOK_URL=your_webhook_url


✅ n8n_workflow.json — export your workflow to help others replicate your automation.
✅ requirements.txt — if any scripts or supporting code are used.
✅ LICENSE — optional, but recommended if you want others to use your code.

🪄 Future Enhancements

🌐 Add a Streamlit-based frontend for interactive story generation

🗣️ Add voice narration using text-to-speech

🎞️ Generate animated story previews

📤 Publish stories directly to social media or cloud drives

❤️ Made with Love by Uzma Khatun

Author: Uzma Khatun
Role: AI/ML Enthusiast & Automation Developer
Contact:

📧 Email: uzmakhatun.ai@gmail.com
 (example — replace with yours)

💼 LinkedIn: Uzma Khatun

🐙 GitHub: UzmaKhatun

⭐ Support

If you like this project, give it a ⭐ on GitHub — it helps others discover it!
And feel free to fork and experiment with your own ideas 💡
