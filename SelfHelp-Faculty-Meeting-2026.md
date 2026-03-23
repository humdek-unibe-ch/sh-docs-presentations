# SelfHelp Presentation for Faculty Meeting

Audience: Faculty meeting for sports education and psychology, University of Bern  
Presentation length: 10 minutes  
Prepared from repository review dated March 23, 2026  
Historical anchors used: October 11, 2021 notes and October 25, 2023 lecture deck

## Slide 1 - SelfHelp: From Research Platform to Intelligent Care Ecosystem

- SelfHelp started as a platform for self-aided therapy and research websites
- Today it supports content, data collection, workflows, mobile use, and AI
- It is built to help teams launch real interventions, not just static pages
- The goal is practical impact for research, teaching, and psychological support

### Speaker Notes

Start with a simple message: SelfHelp is no longer just a website builder. It has grown into a platform that can support the full journey from study design, to participant interaction, to data collection, to follow-up, and now even AI-supported conversations.

It is especially relevant for our faculty because the needs in sports education and psychology are rarely only "publish a page." We often need recruitment pages, assessments, repeated measurements, personalized feedback, protected data, mobile access, and in some cases guided support or therapeutic communication. SelfHelp is evolving in exactly that direction.

You can position this talk as a short story of progression: where we started, what is possible today, and where the next version is heading.

### Image Placeholder

Use a clean title slide with:
- University of Bern branding
- SelfHelp logo or platform screenshot
- Optional visual: a simple three-part strip showing web, mobile, and AI

---

## Slide 2 - What SelfHelp Is

- A modular platform for building research and intervention applications
- Pages are assembled from reusable sections and components
- Data collection, automation, permissions, and mobile are built in
- It can be hosted in-house for strong control over sensitive data
- It is designed so non-programmers can configure a lot through CMS

### Speaker Notes

Explain SelfHelp in plain language. It is a platform where a team can build a study website, psychoeducational program, intervention journey, or patient-facing tool from configurable building blocks. Instead of hard-coding each page, you assemble pages from sections such as text, forms, cards, lists, media, data displays, and interactive components.

The important point for this audience is that SelfHelp combines several things that are usually scattered across tools: content delivery, participant interaction, data collection, workflows, user groups, and increasingly AI features. That reduces fragmentation.

Also emphasize data control. Because SelfHelp can be hosted on institutional infrastructure, it supports a more controlled research and clinical environment than depending entirely on external SaaS tools.

### Image Placeholder

Add a simple architecture diagram:
- Researcher/therapist on left
- SelfHelp platform in center
- Outputs on right: web page, survey, mobile app, dashboard, AI chat

---

## Slide 3 - How SelfHelp Evolved

- October 11, 2021: presented as a self-aided therapy and research website platform
- October 25, 2023: emphasis expanded to modular pages, scheduling, and mobile
- 2024 to March 2026: stronger data model, workflows, security, events, and AI
- The platform moved from "publish content" toward "orchestrate interventions"

### Speaker Notes

Use this as the bridge from old presentations to the new story.

In the October 11, 2021 notes, the core message was: SelfHelp is a webpage for self-aided therapy, a website-building platform, open source, tailored to research data collection, easy to customize, and possible to host locally. That was already a strong proposition.

By the October 25, 2023 lecture phase, the platform story had broadened to modular page building, survey and job-related integrations, and mobile integration.

What is new in the current codebase through March 2026 is the shift from a helpful CMS toward a full operational system: unified data tables, advanced workflows, stronger access control including 2FA, mobile parity improvements, refresh-event infrastructure for asynchronous processing, SurveyJS growth, and two new AI layers: general LLM capabilities and therapy-specific supervised chat.

So the message is not that SelfHelp changed identity. It deepened its usefulness.

### Image Placeholder

Create a horizontal timeline with 3 milestones:
- 2021 foundations
- 2023 platform expansion
- 2024-2026 intelligent workflow and AI expansion

---

## Slide 4 - What Users Can Achieve with SelfHelp

- Build study websites, intervention journeys, and psychoeducational programs
- Collect structured data, repeated measures, files, and media
- Automate emails, notifications, reminders, and scheduled actions
- Personalize content by user, group, language, or data state
- Reach participants on web and mobile with the same platform logic

### Speaker Notes

This is the first strongly marketing-oriented slide. Avoid talking about code here. Talk about outcomes.

A researcher can build a recruitment and screening flow, gather baseline data, deliver intervention content, trigger reminders, and collect follow-up data in one environment.

A lecturer or program designer can create guided learning modules, structured exercises, reflections, check-ins, and progress tracking.

A clinician or therapist can support blended care: psychoeducation, structured questionnaires, messaging, and supervised AI-enhanced support.

The real value is that SelfHelp does not stop at page publishing. It supports intervention logic over time.

### Image Placeholder

Use a workflow diagram:
- Recruit -> onboard -> assess -> intervene -> follow up -> analyze
- Under each step, add example SelfHelp capabilities

---

## Slide 5 - Core Platform Strengths

- Component-based CMS for flexible page and program building
- Unified dataTables system for forms, records, and retrieval
- Workflow engine for actions, jobs, email, and notifications
- Fine-grained permissions, groups, ACL, and two-factor support
- Plugin architecture for specialized extensions such as surveys and AI

### Speaker Notes

This is the "why this platform is strong underneath" slide, but keep it non-technical.

First, pages are modular. That means teams can compose intervention flows and content without rebuilding everything from scratch.

Second, data is first-class. The unified dataTables system means forms and records are not isolated one-off submissions; they can be stored, retrieved, filtered, displayed, and reused in logic.

Third, automation matters. SelfHelp includes workflows and scheduled jobs, so it can send reminders, queue tasks, trigger messages, and react to events after user input.

Fourth, security and access are mature enough for institutional use: groups, ACL, page permissions, audit trails, and 2FA for sensitive roles.

Fifth, the plugin system is a major strategic strength. It lets the platform grow into surveys, statistical tools, mobile APIs, and now AI without rewriting the whole core.

### Image Placeholder

Add a "capabilities wheel" or 5-column graphic with:
- Build
- Collect
- Automate
- Protect
- Extend

---

## Slide 6 - Deep Dive: SurveyJS Plugin

- Advanced survey builder with versioning and publishing
- Supports metadata, timing, file uploads, PDF export, and voice recording
- Includes edit mode, access control, dynamic content, and dashboards
- Useful for questionnaires, screening, diaries, and repeated measurements

### Speaker Notes

Explain that the SurveyJS plugin makes SelfHelp much more than a simple form tool. It gives a dedicated survey creation and management layer.

Important current strengths from the repo are survey versioning, activation windows, autosave, edit mode, response dashboards, metadata collection such as duration and page flow, dynamic dropdown values from services, and dynamic replacement of survey JSON when needed.

The plugin also supports richer response types such as file uploads and voice recording. That matters for psychology and sports contexts where text-only input is not always enough.

For this audience, the use cases are obvious:
- baseline and post assessments,
- symptom or well-being check-ins,
- injury rehabilitation diaries,
- EMA-style repeated surveys,
- course feedback,
- athlete self-reflection modules.

The selling point is flexibility with governance: it is powerful, but still connected to the wider SelfHelp user, workflow, and data ecosystem.

### Image Placeholder

Use a split image:
- Left: SurveyJS creator/editor screenshot
- Right: results dashboard or response table
- Optional callouts: versioning, voice record, edit mode, PDF

---

## Slide 7 - Deep Dive: LLM Plugin

- Adds configurable AI chat to any SelfHelp page
- Supports file upload, image analysis, speech-to-text, and structured forms
- Includes reusable prompt scripts, async execution, and admin monitoring
- Prompt Lab enables testing, dataset replay, and evaluation before rollout
- Useful for guided learning, screening, coaching, and research support

### Speaker Notes

Position this as a practical AI layer, not hype.

The LLM plugin is not just a chatbot widget. It is a configurable AI framework inside SelfHelp. A page can host an AI assistant with a defined conversation context, limits, safety settings, and optional structured response behavior.

What stands out in the current plugin is breadth:
- regular chat,
- structured JSON responses,
- interactive form mode,
- file uploads and image-capable models,
- speech-to-text,
- danger detection,
- reusable scripts,
- admin monitoring of conversations and payloads,
- and a Prompt Lab for testing prompts against datasets before using them with real users.

That last point is especially important for an academic audience. It shows the platform is not only using AI, but creating a workflow for evaluating AI behavior more systematically.

Possible faculty use cases:
- an educational tutor for sport psychology concepts,
- an intake or screening assistant,
- a guided reflective coach for students,
- a research interview guide,
- a participant screening assistant,
- a structured feedback or triage layer before human contact.

### Image Placeholder

Best image is a product montage:
- AI chat window
- microphone or upload icon
- structured form response
- admin console or prompt lab screen

---

## Slide 8 - Deep Dive: LLM Therapy Chat

- Patient-facing AI chat with direct therapist escalation
- Therapist dashboard with unread counts, alerts, notes, risk level, and summaries
- Patients can tag therapists with `@therapist` and classify issues with `#topics`
- AI drafts help therapists respond faster while keeping human oversight
- Safety logic can switch a conversation into human-only mode

### Speaker Notes

This is the most distinctive and impressive plugin for the faculty audience.

Explain that this is not a fully autonomous therapy bot. It is a supervised communication model. Patients can talk to an AI assistant, but therapists remain in the loop. Therapists can read messages, intervene, send direct replies, generate AI-assisted draft responses, create notes, summarize conversations, and manage risk levels.

The safety aspect matters. The plugin includes danger handling, alerting, and the ability to block AI and move into human-only mode if risk becomes critical. That makes the design much more aligned with responsible use in psychological settings.

Also mention operational features: group-based therapist assignments, unread badges, alerts, email and push notifications, and CSV export. This is close to a real care workflow, not just an experimental chat.

For marketing language, say: this opens the possibility of blended support models where scalable AI assistance and clinician oversight coexist.

### Image Placeholder

Use a three-part composition:
- patient chat screen
- therapist dashboard with patient list and unread badges
- callout overlay for alert/risk/AI draft/human-only mode

---

## Slide 9 - Mobile App: SelfHelp in Participants' Daily Context

- The mobile app mirrors SelfHelp content through JSON-based mobile rendering
- Supports surveys, AI chat, therapy chat, notifications, camera, and microphone
- Enables field use, repeated check-ins, and more natural daily engagement
- Makes research and support available beyond the desktop session

### Speaker Notes

This slide is important for sports education and psychology because many relevant interactions happen outside the office, lab, or classroom.

The mobile app is not an unrelated add-on. It is connected to the same SelfHelp ecosystem. The current app supports SurveyJS, LLM chat, therapy chat, notifications, event-based refresh behavior, camera/photo handling, and microphone recording.

That means the platform can support real-life use cases such as:
- daily well-being check-ins,
- voice reflections after training,
- mobile completion of repeated questionnaires,
- on-the-go access to psychoeducational content,
- mobile therapist or AI-supported contact.

This makes SelfHelp more realistic for behavior change, adherence, and longitudinal research.

### Image Placeholder

Use a phone mockup with 3 stacked screens:
- survey screen
- AI chat screen
- therapy chat or notification screen

---

## Slide 10 - Why This Matters for Sports Education and Psychology

- One platform can cover recruitment, intervention, monitoring, and follow-up
- Supports both research rigor and practical support delivery
- Enables blended formats: self-help, guided support, and supervised AI
- Fits use cases from athlete well-being to psychoeducation to clinical pathways

### Speaker Notes

Now make it local and relevant.

For sports education, SelfHelp can support athlete education, recovery adherence, self-monitoring, motivation, and reflective learning journeys.

For psychology, it can support psychoeducation, repeated assessments, stepped-care pathways, therapist-supported digital interventions, and research studies with structured participant interaction.

For both fields, it can reduce tool fragmentation. Instead of separate systems for web content, surveys, mobile access, reminders, and AI pilots, teams can build coherent journeys in one environment.

A strong line to use here is: SelfHelp helps us move from isolated digital elements to complete digital programs.

### Image Placeholder

Add a 2-column use-case slide:
- Sports education examples
- Psychology examples

Optional visual icons:
- athlete
- clipboard/survey
- phone
- therapist dashboard

---

## Slide 11 - SelfHelp 2: The Next Step

- SelfHelp 2 is emerging as an API-first backend plus modern React frontend
- Backend repo shows versioned APIs, JWT security, page versioning, and cleaner services
- Frontend repo shows dynamic style rendering, multi-language support, modern CMS UX, and plugin loading
- The direction is a more scalable, maintainable, and extensible platform

### Speaker Notes

Frame this carefully as a forward-looking vision grounded in the current repositories.

Based on the `sh-selfhelp_backend` and `sh-selfhelp_frontend` repositories, SelfHelp 2 appears to be moving toward a cleaner split architecture:
- a Symfony backend with versioned REST APIs, JWT authentication, JSON schema validation, dynamic routing, and page versioning,
- and a Next.js/React frontend with modern CMS editing, dynamic style rendering, multi-language support, and even a documented model for dynamic plugin loading.

This suggests a future where SelfHelp becomes easier to scale, easier to extend, and easier to modernize without losing the strong domain logic already built in the current system.

Be explicit that this is the direction visible in the codebase, not yet the finished product shown today.

### Image Placeholder

Use a future-state architecture diagram:
- SelfHelp 2 Backend API
- SelfHelp 2 Frontend CMS/Web
- Mobile App
- Plugins / AI services

---

## Slide 12 - Closing Vision

- From content platform to intervention platform
- From digital pages to intelligent, supervised journeys
- From isolated tools to one research and practice ecosystem
- SelfHelp 2 can become the foundation for the next generation of digital programs at Bern

### Speaker Notes

End with confidence and ambition.

Suggested closing line:
"SelfHelp is already a strong research and intervention platform. What is exciting now is that it is becoming not only more powerful, but more connected: surveys, workflows, mobile, and AI are no longer separate experiments. They are becoming one ecosystem."

Then add the forward-looking message:
"SelfHelp 2 gives us the chance to turn that ecosystem into a more scalable institutional platform for digital research, education, and psychological support."

Pause there. Do not over-explain. Let the audience leave with the sense that this is both real and expandable.

### Image Placeholder

Use a bold closing visual:
- "SelfHelp -> SelfHelp 2" evolution arrow
- Keywords around it: Research, Teaching, Mobile, AI, Care, Data, Bern

---

## Bonus: Strong Vision Statements for SelfHelp 2

1. SelfHelp 2 can become a single institutional platform where digital interventions, research workflows, and participant support are designed, delivered, and evaluated together.
2. SelfHelp 2 can make high-quality digital programs easier to build, easier to govern, and easier to scale across projects and departments.
3. SelfHelp 2 can combine human expertise, structured data collection, and responsible AI in one environment instead of spreading them across disconnected tools.

## Bonus: Example Future Features for SelfHelp 2

- Visual program builder with easier page and section management
- Stronger API-based integrations with external systems and faculty tools
- Better plugin marketplace or plugin loading model for specialized modules
- More advanced publishing, version comparison, and rollback workflows
- Improved analytics and dashboards across interventions and studies
- Easier multilingual deployment for different participant populations
