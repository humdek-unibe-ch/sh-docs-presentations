# SelfHelp Faculty Meeting 2026 - PowerPoint Ready

This file is for building the slides directly in PowerPoint.

Use it in this order:
1. Copy the slide title
2. Copy the subtitle if there is one
3. Copy the bullet text exactly as written
4. Use the screenshot plan at the end to collect visuals

---

## Slide 1

### Title
SelfHelp

### Subtitle
From digital pages to digital programs

### Slide Text
- Presented here before in 2021
- Evolved into a broader platform
- Content, data, mobile, workflows, AI

---

## Slide 2

### Title
What SelfHelp Is

### Slide Text
- A modular platform for digital programs
- One system for content, data, workflows, and mobile
- Configurable through the CMS
- Extendable through plugins
- Hostable under institutional control

---

## Slide 3

### Title
From 2021 to Today

### Slide Text
- 2021: self-help and research websites
- 2023: more modular, more operational, more mobile
- 2024-2026: stronger data, workflows, security, and live updates
- Today: a serious platform layer for surveys, mobile, and AI

---

## Slide 4

### Title
What Teams Can Build

### Slide Text
- Digital programs with onboarding, content, and follow-up
- Structured data collection over time
- Personalized journeys by role, group, language, or state
- Automated reminders, notifications, and actions
- Web and mobile delivery from one platform logic

---

## Slide 5

### Title
Why It Works as a Platform

### Slide Text
- Strong core: pages, sections, dataTables, workflows, ACL
- API and mobile layer connect web, app, and external systems
- Research extensions for surveys, experiments, and analytics
- Supporting plugins for auth, R, sensing, and video workflows
- The three main focus plugins build on this foundation

---

## Slide 6

### Title
Focus Plugin 1: SurveyJS

### Slide Text
- Versioned survey creation and publishing
- Scheduling, autosave, metadata, and dashboards
- Edit mode and access control
- Files, PDF export, and voice-record responses
- Strong fit for repeated and structured assessment

---

## Slide 7

### Title
Focus Plugin 2: LLM

### Slide Text
- Configurable AI assistants inside SelfHelp pages
- Text, file, image, and speech-to-text input
- Free conversation or structured JSON output
- Reusable scripts and async processing
- Prompt Lab for testing and evaluation

---

## Slide 8

### Title
Focus Plugin 3: LLM Therapy Chat

### Slide Text
- Supervised communication model
- AI-supported or human-only operation
- Therapist dashboard with alerts, notes, and drafts
- Escalation from AI to direct human handling
- Useful for service delivery and research comparison designs

---

## Slide 9

### Title
Mobile App

### Slide Text
- Same platform logic on mobile
- Surveys, AI chat, therapy chat, notifications
- Camera and microphone support
- Better fit for repeated real-world interaction
- SelfHelp becomes a daily-use service

---

## Slide 10

### Title
How SelfHelp Compares

### Slide Text
- LimeSurvey: strong surveys
- JATOS / formr: strong online studies
- Moodle: strong learning delivery
- SelfHelp: content + data + workflows + mobile + AI
- Best fit when one locally controlled platform is needed

---

## Slide 11

### Title
SelfHelp 2

### Slide Text
- Cleaner API-first backend and modern frontend
- More explicit page and section structure
- Easier to extend and maintain
- Prepared for structured page JSON
- Foundation for future LLM-assisted content building

---

## Slide 12

### Title
Why SelfHelp Matters Now

### Slide Text
- One platform for digital programs
- One structure across web, mobile, workflows, and AI
- One locally controlled foundation for future growth
- Moving from digital tools to digital program infrastructure

---

# Screenshot Capture Plan

General rule:
- Prefer real product screenshots over stock images
- Hide browser bookmarks and personal tabs
- Use the same zoom level and crop style across all admin screenshots
- Blur names, emails, patient identifiers, API keys, and test data where needed
- For admin pages, capture only the relevant panel, not the entire screen if the rest is distracting

---

## Slide 1 - Title Slide

### Best Visual
Use a 3-image collage, not one single screenshot.

### Capture Exactly
1. A clean public SelfHelp page from your current instance
   - capture the header plus one strong content block
   - avoid admin UI
2. A mobile app screen showing either `surveyJS` or `llmChat`
3. An LLM or therapy chat screen from the current platform

### Layout
- Put the public page on the left
- Put the mobile and AI screenshots stacked on the right
- Add the title over the collage

### Fallback
If you do not have a polished public page ready, use:
- `therapyChatSubject` page
- mobile `llmChat`
- `moduleSurveyJS` creator screen

---

## Slide 2 - What SelfHelp Is

### Best Visual
Side-by-side screenshot pair.

### Capture Exactly
1. Admin page editor in the current SelfHelp instance
   - open `Admin > Pages`
   - open any well-built content page
   - show the section list or section tree
2. The matching public page output
   - same page rendered for users

### What Must Be Visible
- In the admin screenshot: sections/components structure
- In the public screenshot: clean rendered result

### Why
This visually explains "configured in CMS, delivered as a program."

---

## Slide 3 - From 2021 to Today

### Best Visual
Timeline made from three cropped screenshots.

### Capture Exactly
1. A crop from the 2021 presentation material
   - use the earliest usable title or content slide from the old material
2. A crop from the 2023 presentation material
   - use the title slide or a slide with modular/mobile messaging
3. A current 2026 platform screenshot
   - preferably `moduleLlmAdminConsole`, `moduleSurveyJS`, or `therapyChatTherapist`

### Layout
- Place them left to right under the year labels
- Add thin arrows between them

### Note
If the 2021 material does not produce a good screenshot, replace it with a simple text badge:
- "2021: Self-help and research websites"

---

## Slide 4 - What Teams Can Build

### Best Visual
Do not use a product screenshot here.

### Build Instead
Create a simple workflow graphic with 5 boxes:
- onboard
- assess
- support or teach
- follow up
- review

### Optional Screenshot Add-On
If you want one real screenshot, place a small public SelfHelp page screenshot in the center and let the workflow boxes point toward it.

---

## Slide 5 - Why It Works as a Platform

### Best Visual
Four small supporting screenshots around one central label: `SelfHelp`.

### Capture Exactly
1. API / integration proof
   - use a clean screenshot of an API page or response from the `sh-shp-api` environment if available
   - if not, use the mobile app plus web page combination instead
2. Lab.js proof
   - open a page that uses `labJS`
   - capture either the experiment running page or its module/admin page
3. R / analytics proof
   - capture an analytics result screen or a data-driven dashboard if one exists in your current instance
4. Mobile sensing proof
   - capture the Mobisense-related page or admin screen
   - if you have imported wearable data visible anywhere in SelfHelp, use that screen

### What To Avoid
- Do not use Qualtrics here unless you explicitly want a legacy integration example

### If You Need a Cleaner Version
Replace screenshots 1-4 with a custom icon diagram:
- API
- experiments
- analytics
- sensing

---

## Slide 6 - SurveyJS

### Best Visual
Use a 3-part collage.

### Capture Exactly
1. Survey builder
   - open `moduleSurveyJS`
   - capture the SurveyJS creator/editor area
2. Versioning
   - open `moduleSurveyJSVersions`
   - capture the versions list
3. Dashboard
   - open `moduleSurveyJSDashboard`
   - capture the responses/dashboard area

### Optional Fourth Screenshot
Capture a live public `surveyJS` page that includes:
- a voice-record question if available
- or a file upload question

### Crop Guidance
- Keep the creator UI readable
- Make sure the words `Survey JS Dashboard` or version list are visible

---

## Slide 7 - LLM

### Best Visual
Use a 3-part collage.

### Capture Exactly
1. Live AI chat
   - open a page with style `llmChat`
   - capture the conversation list, message area, and input bar
2. Admin monitoring
   - open `Admin > Modules > LLM Admin Console`
   - page keyword: `moduleLlmAdminConsole`
   - capture conversation filters plus one conversation view
3. Prompt / scripts management
   - open `moduleLlmScript`
   - capture the scripts manager or prompt lab area

### Best Detail To Show
- file upload button
- microphone button
- structured response or prompt evaluation table

### If You Can Only Capture Two
Use:
1. `llmChat`
2. `moduleLlmAdminConsole`

---

## Slide 8 - LLM Therapy Chat

### Best Visual
Use a 3-part collage.

### Capture Exactly
1. Subject chat
   - open page `therapyChatSubject`
   - capture the message view with either:
     - AI hybrid mode
     - or a visible `@therapist` / tagged interaction
2. Therapist dashboard
   - open page `therapyChatTherapist`
   - capture:
     - patient list
     - unread count
     - alerts or stats area
3. Configuration proof
   - open `sh_module_llm_therapy_chat`
   - capture the settings area showing:
     - subject page
     - therapist page
     - floating button
     - chat mode

### Optional Alternate Shot
If the dashboard looks strong enough, replace the config screenshot with:
- a conversation where AI is disabled or human-only mode is visible

### Important
Use data that makes the dual-mode story visible:
- AI-supported
- human-only

---

## Slide 9 - Mobile App

### Best Visual
Use 3 phone screenshots inside device frames.

### Capture Exactly
1. Mobile `surveyJS`
   - show a real survey page
2. Mobile `llmChat`
   - show conversation plus input area
3. Mobile therapy or notification state
   - show either:
     - therapy chat screen
     - floating therapy button with unread badge
     - or a push notification opening the app

### Nice Extra Detail
If possible, make one screen show:
- camera attachment option
- or microphone recording UI

### Crop Guidance
- keep the phone status bar if it looks clean
- crop tightly enough that text is readable on a slide

---

## Slide 10 - How SelfHelp Compares

### Best Visual
Do not use screenshots.

### Build Instead
Create a clean comparison table with columns:
- LimeSurvey
- JATOS / formr
- Moodle
- SelfHelp

### Rows
- content programs
- surveys
- workflows
- mobile continuity
- AI integration
- local control

### Visual Tip
Use checkmarks, partial checkmarks, and short labels instead of long text.

---

## Slide 11 - SelfHelp 2

### Best Visual
Use a concept slide with one real screenshot plus one diagram element.

### Capture Exactly
1. If you have the new frontend running:
   - capture the section tree / editor UI from the new frontend
2. If you have the new backend running:
   - capture a clean API JSON response from a page endpoint in Postman or browser devtools

### Layout
- left: new frontend screenshot
- right: simplified page JSON block
- top or bottom: arrow labeled `structured page model`

### If V2 Is Not Ready for Screenshots
Do not force screenshots.
Use a custom architecture diagram instead:
- frontend
- backend API
- structured page JSON
- future LLM content generation

---

## Slide 12 - Closing

### Best Visual
Use a final 3-image summary collage.

### Capture Exactly
1. `moduleSurveyJS` or `moduleSurveyJSDashboard`
2. `llmChat` or `moduleLlmAdminConsole`
3. Mobile app screen or `therapyChatTherapist`

### Layout
- three equal vertical panels
- one label over each:
  - Assess
  - Support
  - Scale

### Why
This ends the talk on real product capability, not abstract wording.
