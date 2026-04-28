# CaptionAI (APEX Product)

**CaptionAI** is a straightforward web tool designed to generate engaging Instagram captions using AI based on user-provided keywords and desired tone. Perfect for small businesses, influencers, and social media managers looking to save time and enhance their social media presence.

## Features:
- Input keywords/themes.
- Select a caption tone.
- AI-powered caption generation.
- Optimized for trending hashtags and emojis (via backend AI).
- Simple, clean user interface.
- Integrated Stripe Checkout for one-time payments.

## Setup (Developer Instructions):
1.  **Clone Repository:** `git clone https://github.com/apex-slug/apex-caption-generator.git`
2.  **Install Dependencies:** `npm install` (assuming you have a `package.json` for backend functions)
3.  **Vercel Deployment:** Link your GitHub repo to Vercel. Vercel will automatically deploy the frontend (`index.html`) and any serverless functions.
4.  **Backend Functions:** Create Vercel API routes (e.g., `/api/generate-caption.js`) to integrate with a text generation AI API (e.g., Hugging Face Inference API).
5.  **Stripe Integration:** Configure Stripe webhooks and create an API endpoint (e.g., `/api/create-checkout-session.js`) to handle payment processing.
6.  **Environment Variables:** Set API keys for your AI service and Stripe in Vercel environment variables.

## Usage:
1.  Visit the deployed application.
2.  Enter your desired keywords/themes and select a tone.
3.  Click "Generate Caption" to get an instant Instagram caption.
4.  Optionally, purchase full access via Stripe for unlimited generations.