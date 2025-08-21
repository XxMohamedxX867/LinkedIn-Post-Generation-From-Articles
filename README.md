Automated LinkedIn Content Workflow with n8n
📌 Project Overview

This project is my third n8n automation workflow, designed to streamline content creation and publishing for LinkedIn. Its main purpose is to help busy professionals stay active on LinkedIn by automatically generating posts from articles they read.

🚀 How It Works

Article Scraping

The workflow scrapes articles and extracts key ideas.

These ideas are stored in a Google Sheet as potential post drafts.

Scheduled Posting

On a defined schedule, the workflow checks the Google Sheet.

It selects the next available post context and prepares it for publishing.

Post Generation with Gemini

Using Google’s Gemini model, the workflow expands the context into a full LinkedIn post.

Image Generation with Pollinations.ai

The workflow generates three images for each post using pollinations.ai.

Since AI images may contain errors, generating multiple options allows the user to choose the most suitable one.

Google Docs Review Option

Before posting, the workflow can send an email containing the draft post in a Google Doc.

The user can review, edit, or adjust the content directly in the document.

The same email also includes the three generated images so the user can pick one for the final post.

🎯 Use Case

This workflow was built for a Business Development professional who:

Regularly reads articles in their field.

Wants to stay active and build their personal brand on LinkedIn.

Doesn’t have enough time to manually write posts and design visuals.

With this automation, the user only needs to read articles and approve/edit posts when necessary. The workflow handles the rest.

⚙️ Tech Stack

n8n for automation workflow.

Google Sheets for storing extracted post ideas.

Gemini for generating post content.

Pollinations.ai for image generation.

Google Docs & Gmail for review and collaboration.

✅ Benefits

Saves time by automating content creation.

Ensures consistent LinkedIn activity.

Provides flexibility with review and editing.

Offers multiple AI-generated image choices to improve visual quality.
