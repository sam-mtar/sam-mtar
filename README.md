Full-Stack AI Builder · Multimodal Video & Voice Pipelines · Product-Minded Developer Advocacy

I build full-stack AI applications, multimodal media pipelines, and developer-facing workflows that turn frontier models into reliable production software—and translate how they work into clear tutorials, live workshops, and working demos.

Note on repository visibility: Most of my active day-to-day production codebases live inside private enterprise monorepos (Zero-Trust Google Cloud Run deployments) and private commercial repositories. Below is an architectural overview of what I build and ship, alongside public links where available.

What I Build

Autonomous Multimodal Video-Editing & Verticalization Agent (TypeScript · React / Vite · Node.js / Express · FFmpeg · Sharp · Gemini Multimodal API · Cloud Run)
Stateless full-stack media pipeline that ingests raw video rushes, runs FFmpeg scene-cut and pan estimation alongside multimodal vision saliency (box_2d tracking of faces, products, text, and logos), executes pacing-aware rough cuts, and renders 16:9, 9:16, and 1:1 acquisition assets via dynamic tracking crops and generative AI outpainting—enforcing automated sharpness, normalized cross-correlation (NCC) alignment, and brand-compliance fallback gates.

Deterministic UI Walkthrough & Tutorial Video Studio (TypeScript · React · Playwright / Chrome DevTools Protocol · FFmpeg · Gemini API · Cloud Run)
Browser-capture and replay engine built to power end-to-end product tutorial series (sign-up flow to first campaign & myth-busting walkthroughs). Records real DOM journeys over CDP, scrubs sensitive state into templated placeholders, aligns cursor/typing choreography with spoken script timing, and exports 1080p MP4s across parallel headless Chromium shards on Gen2 Cloud Run.

Grounded B2B Case Study & Technical Content Engine (Next.js · TypeScript · Gemini API · Cloud Run)
Multi-step agentic pipeline (grounded extraction → structured synthesis → compliance & anti-hallucination verification) deployed in a Zero-Trust enterprise environment to compress technical customer-story and demo creation from weeks to minutes.

LLM Readability & Technical Signal Auditor (TypeScript · Node.js · Google Cloud · REST APIs)
Full-stack web crawler and diagnostic agent evaluating site structure for LLM answer-engine readability and algorithmic signals—selected for Google's Connect Sales Labs [Q1'26].

Consumer iOS Apps & Open-Source Audio / Voice AI Benchmarking (iOS · Firebase · Hugging Face · RVC)
Independently built, shipped, and scaled two paid consumer iOS apps
 (#4 iPhone Paid Board Games in France, 2,400+ paying users, 53% App Store conversion rate). Benchmarked open-source TTS and Retrieval-based Voice Conversion (RVC) checkpoints on Hugging Face across sub-second latency, prosody, intonation, and artifacts—before partnering on GTM with early-stage voice-AI teams including Beside.com
 ($32M Series A, powered by ElevenLabs models in production).

Core Stack
Languages & Frontend: TypeScript, JavaScript (ES2024), React, Next.js, Vite, HTML/CSS, SQL
Backend, Media & Browser Infra: Node.js, Express, FFmpeg, Sharp, Playwright, Chrome DevTools Protocol (CDP), REST APIs & Webhooks
AI, Audio & Cloud: Multimodal LLM & Agentic Pipelines (Gemini API, MCP, Grounded Search, Automated Eval Gates), Voice & Audio AI (ElevenLabs ecosystem, Hugging Face TTS / RVC benchmarking), Google Cloud Platform (Cloud Run, Secret Manager, IAP), Firebase
Public Demos, Tutorials & Writing
🎥 On-Camera Product AMA & Walkthroughs: Google Ads Official Product AMA & Synthesis on Reddit
 + on-camera Sign-Up-to-First-Campaign & Myth-Busting video tutorial series
📱 App Store: Les Complices — iOS (#4 Paid Board Games FR)
🏆 Hackathon Laureate: Hack ton Campus with CEA LETI (Deep-Tech R&D)
📰 Press (AI Workflows at Alan): Stratégies — How Alan Embedded AI Across Outbound & Content
