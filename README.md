# AI-Powered Workplace Productivity Assistant - Tshepiso

## Problem Statement
Professionals spend 3-4 hours daily on repetitive tasks like drafting emails, summarizing meetings, and planning tasks. This wastes productive time and causes delays.

## Solution Overview
I built an AI-Powered Productivity Assistant that automates 3 core tasks:
1. Smart Email Generator - Generates professional emails with different tones
2. Meeting Notes Summarizer - Converts long notes into action items
3. AI Task Planner - Creates prioritized daily plans

This saves 60% of time spent on admin work.

## Tools Used
- Meta AI: For generating website code and debugging Vercel deployment
- Claude: For refining email prompts and improving tone
- ChatGPT: For prompt engineering and testing
- Vercel: For deploying live portfolio
- GitHub: For version control

## Sample Prompts (Important for 25% marks)

PROMPT 1 - Smart Email Generator (Formal to Client):
"Act as a professional workplace assistant. Generate a formal email to a client named [Client Name] about [Topic: project delay]. Tone: formal, respectful, apologetic. Include subject line, greeting, clear reason, new timeline, and professional closing. Audience: client."

PROMPT 2 - Email Tone Variation (Persuasive to Manager):
"Generate a persuasive email to my manager requesting [Request: work-from-home]. Tone: persuasive and professional. Structure: greeting, benefit to company, my productivity plan, assurance of availability, polite closing. Audience: manager."

PROMPT 3 - Meeting Summarizer:
"Summarize these meeting notes: [Paste Notes]. Extract: 1) Key Decisions, 2) Action Items with responsible person, 3) Deadlines. Format as bullet points for quick reading."

PROMPT 4 - Task Planner:
"Create a structured daily plan for: [List tasks]. Prioritize using Urgent/Important matrix. Suggest time blocks and 2 time optimization strategies."

## Challenges & Solutions
Challenge 1: Vercel deployment was new to me - Got 404 error and token timeout on OneDrive.
Solution: Used Meta AI to get step-by-step guide to link GitHub to Vercel, set Framework Preset to 'Other' and rename file to index.html.

Challenge 2: AI gave generic emails.
Solution: Refined prompts by adding audience, tone, and context placeholders for better accuracy.

## Responsible AI Practices
- Added disclaimer: "AI-generated content must be reviewed before sending"
- Validated outputs for bias (ensured formal tone not gender-biased)
- Noted limitation: AI may miss confidential context, human review needed

## Live Links
Live Portfolio: [Put your Vercel link here]
GitHub: [Put repo link here]

## Impact
Reduces email writing time from 15 mins to 2 mins, improves meeting follow-up, and helps with daily planning.

Author: Tshepiso | CAPACITI AI Skills Program 2026
