# Shahzaib Arshad

**AI Engineer | Generative AI · RAG · Voice AI · Machine Learning · Automation**

I build applied AI systems and backend tools, with hands-on projects in document question answering, speech classification, real-time voice agents, and workflow automation. My public work includes a grounded RAG and lead-scoring assessment, an audio-classification web app, LiveKit voice-agent prototypes, and a FastAPI hospital monitoring system.

[Email](mailto:engineershahzaibarshad@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shahzaib-arshad-butt/) · [GitHub](https://github.com/ishahzaibarshad)

## Selected projects

### [MGC AI assessment](https://github.com/ishahzaibarshad/mgc-ai-assessment) · RAG, ML, SQL, Flask

A small, explainable assessment project with local TF-IDF retrieval over supplied documents, explicit handling of conflicting or missing information, SQL data analysis, and a logistic-regression lead-scoring baseline. The web interface brings the document Q&A and scoring workflows together. The project reports Average Precision from its training run rather than claiming a fixed benchmark.

### [Synthetic speech detection](https://github.com/ishahzaibarshad/synthetic-speech-detection) · Audio ML, Flask, Hugging Face

A Flask upload flow that uses a pretrained Hugging Face audio-classification model to label uploaded speech. Audio is loaded and resampled with librosa before inference. The repository does not publish an evaluation result, so no accuracy figure is claimed.

### [Twilio LiveKit outbound agent](https://github.com/ishahzaibarshad/twilio-livekit-outbound-agent) · Voice AI, FastAPI, Twilio

A prototype repository containing a FastAPI outbound-call API, Twilio webhook and media-stream handling, and a scripted LiveKit voice agent. The repository’s run notes identify the Twilio-to-LiveKit audio bridge as unfinished work, so this is presented as a prototype rather than a verified end-to-end calling product.

### [Final-expense voice agent](https://github.com/ishahzaibarshad/Complete_Lk_Agent_System_Outbound) · LiveKit, Groq, Cartesia

A deterministic voice workflow that collects age and name, checks interest, and can transfer a SIP call to a licensed agent when transfer is enabled and configured. Speech recognition uses Groq Whisper; speech output uses Cartesia, with Silero VAD. The flow does not use an LLM for its qualification steps.

### [LiveKit outbound caller example](https://github.com/ishahzaibarshad/livekit-outbound-caller-agent) · SIP, Deepgram, OpenAI

A Python LiveKit Agents example that places an outbound SIP call and runs a voice pipeline with Deepgram speech recognition, OpenAI language and speech services, and Silero VAD. The availability and appointment actions in the sample are placeholders rather than a connected scheduling system. The README will credit the upstream example it references.

### [LiveKit and Twilio call management](https://github.com/ishahzaibarshad/livekit-twilio-call-management) · FastAPI, LiveKit, Twilio, SQLite

A call-management prototype with FastAPI routes, a scripted voice-agent workflow, a Twilio integration, a dashboard, contact and call-management components, and an optional Streamlit interface. The repository’s run guide still lists the Twilio-to-LiveKit audio bridge as a remaining integration task. Its similarly named companion repository contains the same source files; I’m treating these as one portfolio project rather than two distinct implementations.

### [Nurse call management system](https://github.com/ishahzaibarshad/nurse-call-management-system) · FastAPI, MySQL, WebSockets

A hospital monitoring system that receives L7700 device events over UDP, decodes and stores them in MySQL, sends live updates over WebSockets, and streams RTSP camera feeds to the browser as MJPEG.

### [LiveKit room assistant](https://github.com/ishahzaibarshad/Lk_voice_agent_complete) · LiveKit, Groq, Cartesia

A real-time room-based voice assistant built with LiveKit Agents. It combines Groq language and speech services, Cartesia text-to-speech, and Silero voice activity detection, and enables room transcription.

### Make.com lead automation · Workflow automation

A lead-processing workflow connecting capture, Google Sheets, APIs, and email notifications for tracking and follow-up. This project is described in my existing profile README but does not currently have a public repository linked here.

## Focus areas

- **Generative AI and RAG:** grounded document Q&A, retrieval, conflict handling
- **Voice AI:** LiveKit Agents, speech recognition, text-to-speech, call workflows
- **Machine learning:** audio classification, data preparation, baseline modeling, evaluation
- **AI engineering and automation:** Python, FastAPI, Flask, SQL, APIs, webhooks, Make.com

## Experience

**AI Automation Engineer — Cloud Rexpo PVT LTD** · Jan 2026–Feb 2026  
**Junior Machine Learning Engineer — IDRAK AI PVT LTD** · Dec 2024–Jan 2026

## Education

**B.S. Software Engineering** — National University of Modern Languages, Islamabad · 2021–2025

## Certifications

- Machine Learning Specialization — DeepLearning.AI
- Prompt Engineering — DeepLearning.AI
- Practical AI and Machine Learning certifications — Hugging Face

