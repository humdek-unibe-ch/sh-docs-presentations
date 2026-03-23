# SelfHelp Presentation for Faculty Meeting

Audience: University faculty and academic stakeholders  
Presentation length: 10 minutes  
Prepared from a full platform review dated March 23, 2026  
Historical reference points reviewed: 2021 and 2023 presentation materials

## Slide 1 - SelfHelp: A Platform for Digital Programs, Research, and Support

- SelfHelp began as a self-help and research website platform
- It has grown into a modular system for content, data, workflows, mobile, and AI
- It is designed for real programs, not just isolated pages or forms
- The value is practical: build, run, adapt, and monitor digital interventions in one place

### Speaker Notes

Some of you may remember that we already presented SelfHelp here in 2021. For others, this may be the first introduction. In both cases, the interesting part today is to see how far the platform has evolved since then.

SelfHelp is no longer just a website tool. It has become a platform for building and running digital programs.

What makes it interesting is the combination. In one system, we can publish content, collect data, automate steps, support mobile use, and now add AI-supported interactions. That means we are not only creating pages. We are creating complete digital journeys.

The point of this talk is to show that SelfHelp has matured in a very practical direction. It now supports the full path from onboarding and content delivery to assessment, follow-up, and intelligent interaction.

### Image Placeholder

Use a clean title slide with:
- SelfHelp name and subtitle
- one polished platform screenshot in the background
- a small three-part visual hint for web, mobile, and AI

---

## Slide 2 - What SelfHelp Is

- A modular platform for building digital programs with reusable components
- The same system handles content, data collection, automation, permissions, and mobile output
- It supports institutional hosting and strong control over sensitive data
- Many use cases can be configured through the CMS rather than custom-coded from scratch
- A plugin architecture allows the platform to grow without breaking the core

### Speaker Notes

If someone asks what SelfHelp is in plain language, I would say this: it is a configurable platform for building digital services.

Instead of treating a website, a survey, a reminder workflow, and a mobile app as separate projects, SelfHelp brings them together. Pages are assembled from reusable sections. Data is stored in a structured way. Workflows can react to what users do. The same content model can also be rendered for mobile.

That is important in a university environment because many projects do not fail on ideas. They fail because too many tools have to be stitched together. SelfHelp reduces that fragmentation.

And because it can be hosted under institutional control, it is suited to settings where governance and data protection matter.

### Image Placeholder

Add a simple diagram:
- left: editor / researcher / practitioner
- center: SelfHelp platform
- right: website, survey, workflow, mobile app, AI assistant

---

## Slide 3 - How SelfHelp Evolved

- 2021: positioned as a platform for self-help and research websites
- 2023: expanded toward modular pages, scheduling, and mobile integration
- 2024 to 2026: stronger data model, workflows, permissions, 2FA, and live refresh mechanisms
- The newest step is AI: general LLM support and supervised therapy-style chat
- The direction is clear: from content publishing toward structured digital program delivery

### Speaker Notes

I would connect this slide back to the audience first. We already showed SelfHelp in this faculty setting in 2021, so this is not a completely new story. It is more a continuation. Some people in the room may remember the earlier version, and this slide helps show what changed since then.

At the beginning, the message was quite simple: SelfHelp helped us build self-help and research-oriented websites, host them ourselves, and adapt them without too much custom development.

After that, the platform became much more operational. The page system became more modular, automation became more reliable, and mobile support became much more usable in practice.

And in the current stage, a lot of the progress is in the foundation: better data structures, more systematic workflows, stronger permissions, two-factor authentication, and infrastructure for background processes and live updates. On top of that, we now have a real AI layer.

So the main point of this slide is: the idea stayed the same, but the platform became much more mature and much more capable.

### Image Placeholder

Create a horizontal timeline with 4 milestones:
- 2021 foundation
- 2023 expansion
- 2024-2025 operational maturity
- 2026 AI and next-generation architecture

---

## Slide 4 - What Teams Can Achieve with It

- Launch digital programs that combine information, interaction, and follow-up
- Collect structured data, repeated measures, files, voice, and media
- Personalize journeys by role, group, language, condition, or user state
- Automate reminders, notifications, tasks, and triggered actions
- Reach users on web and mobile through one platform logic

### Speaker Notes

This is the outcome slide. Here I would avoid technical detail and focus on what a team can actually build.

A team can create a complete digital program: a landing page, onboarding, assessments, educational or intervention content, reminders, follow-up measures, and dashboards or review views. That can be done inside one environment instead of moving between disconnected systems.

The system is useful whenever a project needs structure over time. That includes research studies, guided learning, support programs, coaching flows, blended care models, or any process where users return repeatedly and the system needs to react to what happened before.

The key idea is simple: SelfHelp supports ongoing journeys, not one-off interactions.

### Image Placeholder

Use a workflow graphic:
- recruit
- onboard
- assess
- support or teach
- follow up
- review

Under each step, add one SelfHelp capability.

---

## Slide 5 - Why SelfHelp Works as a Platform, Not Just a Tool

- The core already covers pages, sections, dataTables, conditions, workflows, and ACL
- The API layer and mobile rendering connect web, app, and external services
- Survey, experiment, and assessment plugins extend the platform beyond classic forms
- Analysis and scoring can be pushed further through formula and R-based extensions
- SSO, sensing, notifications, and video integrations make institutional deployment more realistic

### Speaker Notes

This slide is here to prepare the audience for the three main plugins we will look at next: SurveyJS, the general LLM plugin, and the LLM Therapy Chat plugin.

Before going into those three, I want to show that they do not stand alone. They sit inside a larger platform architecture. There is an API layer that connects the web platform, the mobile app, and external services. There is external authentication support, which matters for institutional deployment. There are also plugins for Lab.js experiments, formula-based logic, R-based computation, video-linked workflows, and sensing data integration.

The sensing part is worth explaining clearly. Here SelfHelp does not collect the raw wearable data itself. Another platform collects data from devices such as Garmin and similar sources, and SelfHelp can pull that data in and use it in the wider workflow.

That tells us something important about SelfHelp's identity. It was built to support real projects with different methods and different data sources, not just one standard survey or content format.

If I mention the most important supporting pieces around the three main plugins, I would highlight the API layer, external authentication, Lab.js, R integration, and sensing integration. They make the overall platform much stronger.

### Image Placeholder

Create a platform map with five clusters:
- core CMS
- workflow and security
- research and survey tools
- analytics and sensing
- mobile and external integration

Show the three focus plugins highlighted in a different color.

---

## Slide 6 - Focus Plugin 1: SurveyJS

- Advanced survey creation with versioning, publishing, and scheduling
- Supports autosave, timing metadata, edit mode, access control, and dashboards
- Handles files, PDF export, and voice-record responses
- Allows dynamic content such as API-driven dropdowns and JSON replacement
- Strong fit for repeated assessments, diaries, intake flows, and structured questionnaires

### Speaker Notes

SurveyJS is one of the clearest examples of how SelfHelp has moved beyond simple forms.

What matters here is not only that surveys can be built. It is that surveys become managed assets inside the platform. They can be versioned, scheduled, restricted, edited, and connected to dashboards. Response metadata such as timing and completion context is also available, which is valuable for both research quality and operational monitoring.

The richer input support is also worth mentioning. File upload and voice recording make the survey layer more flexible than a standard text-only questionnaire.

So the message is: SurveyJS turns SelfHelp into a serious structured assessment environment, while still keeping it connected to the rest of the platform logic.

### Image Placeholder

Use a split visual:
- left: survey editor or creator interface
- right: response dashboard or filtered results table

Add callouts for:
- versioning
- voice response
- edit mode
- dashboard

---

## Slide 7 - Focus Plugin 2: LLM

- Adds configurable AI assistants directly inside SelfHelp pages
- Supports text, files, images, and speech-to-text input
- Can return free conversation or structured JSON and form-like outputs
- Includes reusable prompt scripts, async execution, and admin monitoring
- Prompt Lab enables testing, replay, and evaluation before live rollout

### Speaker Notes

I would present this as an AI layer for controlled use, not as a chatbot novelty.

The LLM plugin allows us to place a purpose-built assistant inside any page. That assistant can be narrow or broad depending on the prompt context. It can work with uploaded material, image-capable models, and voice input. And importantly, it can produce either conversational answers or structured outputs that the rest of the platform can use.

What makes this more serious than a generic chat widget is everything around it. There are reusable prompt scripts, background execution patterns, an admin view over conversations, and a prompt lab for evaluating prompt versions against datasets and replay cases.

That last part is especially strong in an academic environment. It means AI behavior can be reviewed, tested, and improved in a more disciplined way before it is exposed in a real program.

### Image Placeholder

Build a product montage with:
- AI chat screen
- upload and microphone controls
- example structured response card
- prompt lab or admin monitoring screenshot

---

## Slide 8 - Focus Plugin 3: LLM Therapy Chat

- Combines patient-facing AI chat with therapist oversight in one conversation space
- Therapists get a dashboard with unread counts, alerts, notes, summaries, and drafts
- Users can escalate directly to a human instead of staying only with AI
- Safety logic can block AI and move the case into human-only mode
- The result is a supervised model of AI-supported communication, not an unsupervised bot

### Speaker Notes

This is probably the most distinctive plugin in the current platform.

The important point is that it is not trying to replace human support. It is building a supervised interaction model. A user can interact with AI, but therapists remain present through a dedicated dashboard. They can review the conversation, intervene, send their own messages, create notes, generate drafts, and manage risk status.

The escalation model is central. The system supports moving from AI-supported interaction to direct human handling. And when safety signals are triggered, the conversation can be switched into human-only mode.
But it is also important to say that this plugin does not have to run as AI chat. It can also run in a human-only setup. That means we can configure different groups or different study conditions and compare, for example, AI-supported interaction versus purely human interaction.

That is why this plugin is so valuable conceptually. It is flexible enough for service delivery, but also very interesting for research design, because it allows different communication models inside the same framework while keeping therapist oversight and responsibility in place.

### Image Placeholder

Use a three-panel composition:
- user chat screen
- therapist dashboard with patient list
- alert or risk state panel showing human-only fallback

---

## Slide 9 - Mobile App: Bringing SelfHelp into Daily Use

- The mobile app uses the same platform logic through mobile-ready JSON output
- It already supports surveys, AI chat, therapy chat, notifications, camera, and microphone
- This enables repeated interaction in real contexts, not only desktop sessions
- Mobile support increases adherence, timeliness, and day-to-day relevance
- SelfHelp becomes a living service, not just a web portal

### Speaker Notes

The mobile app is important because many digital programs only become useful when they leave the desktop.

SelfHelp already has a mobile frontend that works with the same platform logic. Surveys, AI chat, therapy chat, notifications, camera-based input, and microphone-based input are already part of that picture.

That matters because repeated interaction often happens in the middle of daily life. A system that can only be used from a desktop browser is much more limited. The mobile app makes check-ins, reflections, uploads, and conversations easier and more natural.

So the platform is not just able to publish content. It can stay present where real use actually happens.

### Image Placeholder

Use phone mockups with three screens:
- survey
- AI chat
- notification or therapy chat

Optional overlay icons:
- camera
- microphone
- push notification

---

## Slide 10 - How SelfHelp Compares to Existing Open, Self-Hosted Options

- LimeSurvey is excellent for surveys, but it is primarily a survey product
- JATOS and formr are strong for online studies, yet they are less suited to content-rich program delivery
- Moodle is strong for learning delivery, but it is not built around intervention workflows or supervised support logic
- SelfHelp brings content, assessments, workflows, mobile, permissions, and AI into one coherent stack
- Its advantage is not one feature in isolation, but the fact that the pieces already work together

### Speaker Notes

I would present this carefully and fairly. There is no need to pretend that SelfHelp replaces every other system in every scenario.

LimeSurvey is a very strong open and self-hosted survey platform. If the only goal is questionnaire administration, it is a serious option. JATOS and formr are also very relevant for online studies, especially for experiment delivery and longitudinal research logic. Moodle is well established for digital learning delivery.

But SelfHelp is solving a different problem. It is trying to unify several layers that are often split apart: content delivery, structured data collection, conditional logic, automation, mobile use, permissions, and now AI-supported interaction. That makes it closer to a digital program platform than to a single-category tool.

So I would not say "SelfHelp is universally better." I would say: when an institution wants one locally controlled platform for digital programs that combine content, interaction, data, workflows, and AI, SelfHelp has a stronger overall fit than stitching together separate products.

### Image Placeholder

Use a comparison matrix with columns:
- LimeSurvey
- JATOS / formr
- Moodle
- SelfHelp

Rows:
- content programs
- surveys
- workflows
- mobile continuity
- supervised AI
- local control

Highlight SelfHelp where the cross-category combination is strongest.

---

## Slide 11 - SelfHelp 2: Why the Redesign Matters

- SelfHelp 2 is moving toward a cleaner API-first backend and modern frontend
- Page structure, section logic, and publishing become more explicit and maintainable
- The new architecture should make future plugins and interfaces easier to build
- A key strategic goal is structured page JSON that LLMs can generate or adapt
- The redesign is therefore not cosmetic; it prepares the platform for faster, safer content creation

### Speaker Notes

This slide should be framed as roadmap, not as a finished release.

The important point is why a new version matters. The redesign is not only about modern technology. It is about making the platform's content model cleaner and more explicit. When pages, sections, and fields are represented through stable APIs and schemas, the whole system becomes easier to maintain, easier to extend, and easier to validate.

That also unlocks the next major step: LLM-assisted content building. The idea is that an AI request could eventually return structured page context or page JSON, which the platform can then use in a controlled way. That is much more powerful than asking an LLM for plain text. It means AI could help generate actual platform content in the language the system understands.

That part is not finished yet, and I would say that clearly. But it is one of the strongest reasons the redesign is strategically important.

### Image Placeholder

Create a future-state architecture diagram:
- content editor
- SelfHelp 2 frontend
- SelfHelp 2 backend API
- structured page JSON
- optional LLM content generation layer
- web and mobile outputs

Add a small label: "planned direction, not final release"

---

## Slide 12 - Closing: Why SelfHelp Matters Now

- One platform for digital research, teaching, and support programs
- One structure across web, mobile, workflows, and AI
- One locally controlled foundation that can keep growing with university needs
- SelfHelp 2 can make content creation faster, more structured, and eventually AI-assisted

### Speaker Notes

I would close with a calm and confident summary.

SelfHelp is valuable because it already connects pieces that are usually scattered. It gives us one platform where content, assessments, workflows, mobile interaction, and AI can be part of the same program.

The second point is that the platform is moving in the right direction. The current system is already capable. The next version is about making that capability easier to scale, easier to maintain, and easier to create with.

If I had to end with one line, I would say this: SelfHelp is becoming a serious institutional foundation for digital programs, not just a collection of digital tools.

### Image Placeholder

Use a strong closing visual:
- one clean platform summary diagram
- or a layered stack showing content, data, workflow, mobile, and AI
- optional final tagline: "From digital pages to digital programs"
