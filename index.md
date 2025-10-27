Diary 2 – Human-Robot Interaction for Disaster Management

HUMAN-ROBOT INTERACTION FOR WAR AFFECTED COMMUNITIE

Group 5 
 Hei Ching IU
 Poon Tsz Hang
 Wing Yu Chan
 Yuhua Zhao
 Yicheng Fen

Section: Project Overview

##hhh Project Theme

We built an AI assistant for emotional support in disaster/war-time scenarios, helping affected people receive immediate calming guidance and safety tips amid high stress and information chaos.

Use Scenarios and Users Scenarios: 
shelters, temporary housing sites, community relief stations.

Users: affected individuals and families; volunteers act as referral and supervision roles.

Key Pain Points: High stress and fear lead to emotional dysregulation and communication difficulties.
Volunteers lack consistent, sustainable calming scripts and processes.
Language and accessibility barriers; weak network conditions are common.

Solution Voice/text conversational emotional-support AI:
Empathic dialogue plus breathing and grounding exercises to aid self-regulation.
Safety reminders and help-seeking pathways, with escalation to human hotlines/on-site volunteers when needed.
Multilingual, low cognitive-load interaction; key flows work under weak network/offline.
Sensitive content is auto-deescalated; all guidance shows source and last update time.

Current Progress and Outcomes: 
Running prototype implemented: empathic opening, calming exercises, help routing, and error fallbacks.
Demo video covers three scenarios: panic relief, nighttime anxiety/insomnia, and finding help.
Initial testing feedback: natural tone and clear steps; terminology and wait time have been refined.

Next Steps: 
Strengthen offline and multilingual support, improve crisis triage and human escalation, and integrate with volunteer workflows for small-scale pilots.



Empathize — Project Overview Section

Overview
Based on interviews and online research from our presentation, we focus on emotional support and information accessibility in disaster/war contexts: under high stress and uncertainty, users need timely, trustworthy, low-effort calming and clear next-step guidance.

Key Points

Increased mental health burden: anxiety and panic are frequent during and post-conflict; self-regulation is harder (from interviewees and literature).
Safety and privacy concerns: strong desire for safe spaces alongside worries about tech security and data privacy.
Scattered information sources: critical updates are unclear and fragmented, delaying decisions and help-seeking.
Family separation and education disruption: intensify stress and hinder long-term recovery (from interviewees/literature).
Weak connectivity and limited resources: unstable networks and logistic variability require brief, real-time, and offline-capable communication.
Vulnerable groups: women and ethnic minorities show higher rates of depression/PTSD (literature).

Design Principle (one sentence)
Human-centered “short, slow, step-by-step” dialogue with breathing/grounding exercises, providing verifiable-source safety reminders and escalation pathways that work under weak network and privacy constraints.

Personal Contribution (Empathize)

Conducted two user interviews: one participant in Ukraine and one in Syria.
Designed the interview guide with targeted questions about emotional needs, information access, privacy concerns, and preferred interaction style under stress.
Synthesized findings into concise themes (panic triggers, short/slow guidance preference, need for verifiable information and human escalation) to inform the dialogue flow and design principles.

POV — Team Work Overview

Defined three POV directions from user research:
AI psychological-support agent (voice/text, offline-capable, cultural/age/language adaptation, risk detection/SOS).
Calm dispatcher for step-by-step safety guidance with transparent information sources.
Family searching/matching support with flexible follow-ups.
Wrote one-sentence POV statements for each direction and ran speed-dating interviews to validate need and feasibility.
Consolidated stakeholder feedback and selected Idea 1 (psychological-support agent) as the primary POV.

POV — My Personal Contribution

Participated in ideation for all three ideas and drafted the POV statements for Ideas 1–3.
Conducted speed-dating interviews and captured insights; specifically synthesized feedback from a Ukrainian girl and a Syrian girl.
Analyzed their needs (compassionate support, offline availability, cultural/language sensitivity, privacy/safety) and recommended adopting Idea 1 as the main POV.

Prototype — Team Work Overview

Scope and positioning: Built a vertical prototype around the primary POV “AI psychological-support agent,” ensuring core conversations and exercises run in real conditions; created lightweight demos for secondary POVs (safety guidance, child mode).
Core interactions implemented:
Conversation flow: emotion check (0–5 scale), empathetic responses, short prompts, confirmation-style interactions.
Intervention exercises: guided breathing, grounding (5-4-3-2-1), self-soothing scripts; progress and completion prompts.
Risk detection and safety: identify self-harm/extreme-risk keywords; auto-surface safety advice and SOS referral info.
Multilingual and cultural adaptation: basic packs in Chinese/English/Arabic; polite forms and localized phrasing.
Basic offline capability: preserve exercise scripts and emergency info cards when the network is down.
Secondary feature demos:
Safety guidance mode: step-by-step routes and shelter hints with transparent source labeling.
Child mode prototype: gentle voice and short-command scripts, gamified breathing.
Testing and iteration: invited 4 non-team users for usability trials; collected issues (speech pace, button placement, prompt consistency) and iterated dialogue and UI.

Prototype — My Personal Contribution

Literature review: searched and organized research on trauma-informed care, effectiveness of breathing and grounding exercises, crisis intervention, and digital mental health to support scripts and risk messaging.
Offline implementation: implemented an offline model and resource pack that runs without internet; ensured core conversations and exercises remain usable during disconnection, and completed related testing and demo.

Usability Testing — Team Overview

Objectives: assess usability, comprehension, emotional relief; verify offline reliability.
Participants & settings: 4 non-team users (2 CN, 1 EN, 1 AR); quiet room, noisy corridor, weak/absent network.
Tasks: emotion check + empathetic chat (≤2 min); breathing + 5-4-3-2-1 grounding; risk/SOS trigger; offline availability.
Findings: clear UI and instructions; offline works; issues with fast TTS and inconsistent labels; ASR drops in noise—text preferred.
Improvements: slower TTS + repeat; standardized labels; segmented risk prompts; clearer offline cues.

Usability Testing — My Contribution

Participated in designing the questionnaire (survey item creation).

AI Usage Statement

AI tools were used in this project to assist with idea refinement, wording of dialogue scripts, and summarizing testing feedback. Some content (text prompts and draft copies) was AI-generated and then reviewed/edited by the team.

Other Contributions

Built the presentation PPT structure and contributed part of the slide content.














