# Agency Lead Qualification & Appointment Chatbot

## Overview
A powerful no-code chatbot system designed for digital agencies managing 50+ clients. This chatbot captures leads from website contact forms and live chat widgets, qualifies them intelligently, books/reschedules appointments directly in Go High Level (GHL), routes conversations based on user preferences, assigns custom tags for targeted follow-ups, and triggers advanced GHL automations (e.g., internal notifications, workflow enrollments, SMS/email sequences).

Built for scalability, it enables agencies to automate lead handling across multiple client websites while maintaining personalized, context-aware interactions.

## Features
- **Lead Capture & Multi-Channel Interaction**: Triggers from web forms or live chat widgets; supports SMS-to-SMS and web-based conversations.
- **Intelligent Qualification**: Asks dynamic questions based on service interest, location, budget, timeline, and user responses.
- **Appointment Management**: Full booking, rescheduling, and canceling of appointments in GHL calendars (with real-time availability checks).
- **Smart Routing & Personalization**: Routes conversations and responses based on user preferences (e.g., service type, location, urgency).
- **Dynamic Tagging System**: Automatically assigns custom tags in GHL (e.g., "High-Intent", "External-Wall-Insulation", "London-Lead", "Needs-Follow-Up") for segmented follow-ups.
- **Advanced GHL Automations**: Triggers workflows on key events — internal Slack/email notifications, opportunity creation, pipeline movement, personalized SMS/email sequences, and task assignment to team members.
- **Multi-Client Support**: Single chatbot deployment handles routing and branding for dozens of agency clients.

## Tech Stack
- **Chatbot Platform**: Close.com bot (or similar no-code conversational platform)
- **CRM & Automations**: Go High Level (GHL)
- **Backend Workflows**: n8n (for complex routing, tagging, and automation triggers)
- **Triggers**: Website forms, live chat widgets, SMS inbound

## Setup Instructions
1. Embed the chatbot widget/script on client websites.
2. Connect form submissions to trigger the initial outbound message.
3. Build qualification flows in the chatbot platform with conditional branching.
4. Use n8n webhooks to handle GHL interactions:
   - Calendar availability checks
   - Appointment booking/rescheduling/canceling
   - Contact creation/updates with dynamic tags
   - Triggering internal workflows and notifications
5. Configure GHL pipelines, tags, and automations to respond to assigned tags.

## Usage
- Visitor submits form or starts chat → Chatbot greets and qualifies → Routes based on answers → Books/reschedules appointment → Applies relevant tags → Triggers GHL automations (e.g., notify sales team, send confirmation + nurture sequence).

This results in higher conversion rates, reduced manual work, and precise lead segmentation for follow-ups.

## Demo
Refer to the attached `project_demo.pdf` for:
- Live chat widget screenshots
- Full conversation flows (qualification + booking examples)
- n8n workflow diagrams
- GHL contact records showing applied tags
- Triggered automations and notifications
- Calendar booking confirmations

## License
MIT
