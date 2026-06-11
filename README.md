# AI Social Media Content Automation

Generates, schedules, and posts content across platforms automatically using Gemini AI.

## How It Works

Topic -> Gemini generates posts -> Returns Instagram, Twitter, LinkedIn posts

## Tech Stack

n8n | Gemini 2.0 Flash | Buffer API | REST APIs

## Setup

1. Import workflow into n8n
2. Add Gemini API key in HTTP Request node
3. Activate workflow
4. Send POST to webhook with topic

## Example

POST /webhook/social-content
{ "topic": "AI trends in 2025" }

Returns Instagram, Twitter, and LinkedIn posts.

## Author

Abdulgeni - github.com/Abdulgeni
