📬 Gmail Email Sender using Gemini (Vertex AI)
This project allows you to send intelligent, automated emails using Google's Gemini via Vertex AI and Gmail. It runs entirely on Google Colab and is designed for marketing, follow-ups, or personalized communications powered by AI.

🚀 Getting Started
✅ Prerequisites
Google Cloud Project with Vertex AI API enabled.

Access to Gemini models through Vertex AI.

A Gmail account with App Passwords enabled.

Google Colab (no local setup required).

🧾 Setup Instructions
1. Clone or Open the Notebook
Run the .ipynb notebook directly in Google Colab.

2. Enable Vertex AI Access
Ensure you have the correct permissions and API access:

Enable Vertex AI API in your GCP Console.
Authenticate with your Google Cloud project from Colab.
!gcloud auth login
!gcloud config set project YOUR_PROJECT_ID

3.Add Secret Keys
In your Colab notebook, securely add your Gmail credentials:
EMAIL : your.email@example.com
PASSWORD : application password(usually 16 digit password)

App passwords only work with Gmail accounts that have 2FA enabled
They bypass 2FA but are restricted to the app you specify.
