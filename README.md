# AI and Manufacturing Training

Materials for the **AI & Manufacturing Workshop**, a hands-on training that helps manufacturing professionals understand and apply artificial intelligence in real production environments.

The workshop focuses on **practical, applied AI** that reduces downtime, improves quality, and supports the people on the floor.

## Training Format
- 3 days
- 3 hours per day
- 9 hours total

No prior AI or coding experience is required.

---

# Before Day 1

Please have these ready before the first session:

- **An AI account.** A free Claude account ([claude.ai](https://claude.ai)) or a personal Google account for Gemini (you must be 18 or older). Work and school Google accounts cannot use skills in the Gemini app yet. If your company uses ChatGPT or Microsoft Copilot, bring that login too.
- **A free GitHub account** ([github.com](https://github.com)) for the demos on Days 2 and 3.
- **A laptop with a webcam** and Chrome or Edge.
- **LM Studio** ([lmstudio.ai](https://lmstudio.ai)) installed for Day 1.
- **Orange Data Mining** ([orangedatamining.com/download](https://orangedatamining.com/download/)) installed for Day 3.

---

# Workshop Sessions

## Day 1: Prompting, LLMs, and AI Skills
**Theme:** Get reliable answers from AI and build a reusable skill for your job

| Time | Block |
|---|---|
| 0:00 to 0:10 | Welcome, introductions, and agenda |
| 0:10 to 0:30 | The state of manufacturing: what keeps you up at night, the workforce outlook, and the adoption gap |
| 0:30 to 0:55 | Prompting: hallucinations, safe use at work, and the RTFC framework (Role, Task, Format, Constraints) |
| 0:55 to 1:55 | AI skills: build and test a skill for one of your real problems |
| 1:55 to 2:00 | Break |
| 2:00 to 2:55 | Local LLMs with LM Studio (led by Clayton) |
| 2:55 to 3:00 | Wrap up and questions |

Topics covered:

- The state of manufacturing: the workforce shortage and the technology adoption gap
- AI fundamentals and the three areas we cover in this training: language, vision, and data
- Spotting hallucinations and using AI safely with company information
- The RTFC prompting framework
- AI skills: reusable instructions plus reference files in one SKILL.md file
- Hands-on: building a skill for SOPs, troubleshooting, or reporting
- Local LLMs: running a model on your own computer with LM Studio

**Slides**

[Day 1 Slides (PDF)](slides/Day1-Prompting-and-Skills.pdf)

### AI Skill Workshop

**Theme:** Package your instructions and documents once so the AI gives consistent answers every time

1. Participant Workbook
[Access the Day 1 Workbook](https://docs.google.com/document/d/1sAQ36oFIaEUiQMzUd1GpMWeI_vuQgNEs/edit?usp=sharing&ouid=108717541017706732541&rtpof=true&sd=true)

2. Demo Skill and Reference Material
We will build the [mill-maintenance-helper skill](skill/mill-maintenance-helper.zip) together. Its reference file is this technical manual:
[Bridgeport Knee Mill Technical Manual](https://bridgeportmachinetools.com/wp-content/uploads/KneeMill-Complete-Manual.pdf)

3. Where Your Skill Works

| Tool | How to use your skill |
|---|---|
| Claude (free plan works) | Settings > Capabilities: turn on Code execution. Then Customize > Skills > + > Create skill > Upload a skill (ZIP) |
| Gemini (personal Google account) | Settings > Skills > Upload your SKILL.md or ZIP |
| ChatGPT | Plugins > + > chat with Plugin Creator. Availability depends on your plan. |
| Microsoft 365 Copilot (license required) | In Cowork: + > Customize > Skills > Add > Upload skill |
| Any other tool | Paste your SKILL.md at the top of a new chat, attach your files, then ask your question |

### Local LLMs with LM Studio

Led by Clayton. Setup steps and materials coming soon.

---

## Day 2: Computer Vision and Vibe Coding
**Theme:** Spot defects with AI and build a simple app by describing it

| Time | Block |
|---|---|
| 0:00 to 0:10 | Welcome and Day 1 recap |
| 0:10 to 0:40 | Computer vision in manufacturing |
| 0:40 to 1:25 | Hands-on: train a model to spot defective cast parts |
| 1:25 to 1:40 | Debrief and questions for your first pilot |
| 1:40 to 1:45 | Break |
| 1:45 to 2:50 | Vibe coding: build a defect and downtime dashboard, then your own app |
| 2:50 to 3:00 | Next session and questions |

Topics covered:

- Computer vision in manufacturing: inspection, sorting, and robot guidance
- Image data and labeling best practices
- Hands-on: training a defect detection model with **Teachable Machine**
- Testing your model live with a webcam
- Vibe coding with Google AI Studio: describe an app, test it, and improve it
- Deciding when you need a prompt, a skill, or an app

**Slides**

[Day 2 Slides (PDF)](slides/Day2-Computer-Vision-and-Vibe-Coding.pdf)

### Computer Vision Hands-On

1. Download the dataset: [casting_data.zip](data/casting_data.zip) (OK and defective cast parts)
2. Train your model at [Teachable Machine](https://teachablemachine.withgoogle.com/)
3. Export Model > Upload my model, then copy the shareable link
4. Test it with your webcam in the demo below

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/grcc-resendiz/teachable-machine-demo)

### Vibe Coding Hands-On

1. Download the sample data: [manufacturing_data_export_2026-05-01.csv](data/manufacturing_data_export_2026-05-01.csv)
2. Open [Google AI Studio Build mode](https://aistudio.google.com/apps)
3. Use the [Map your workflow worksheet](https://docs.google.com/document/d/11CKnpIsUIB6B4AfStJ97ySWpeWfLDXb0A8uEMAIT0n8/edit?usp=sharing) to pick your own app idea

---

## Day 3: Predictive Maintenance and Next Steps
**Theme:** Predict machine failures from data and plan your first AI pilot

| Time | Block |
|---|---|
| 0:00 to 0:10 | Welcome and Day 2 recap |
| 0:10 to 0:20 | Why downtime matters and how predictive maintenance works |
| 0:20 to 0:50 | Machine learning basics and how to judge a model |
| 0:50 to 1:35 | Hands-on: predict machine failures in Orange |
| 1:35 to 1:45 | Break |
| 1:45 to 2:00 | Demo: the same model in Python |
| 2:00 to 2:45 | Implementation: AI readiness and your first pilot |
| 2:45 to 3:00 | Key takeaways and questions |

Topics covered:

- The cost of downtime and how predictive maintenance reduces it
- Machine learning foundations: supervised, unsupervised, and reinforcement learning
- Judging a model: confusion matrix, accuracy, precision, recall, and F1 score
- Hands-on: building a predictive maintenance workflow in Orange Data Mining
- Data readiness and the technology adoption gap
- Planning your first AI pilot: one problem, one owner, one measurable result

**Slides**

[Day 3 Slides (PDF)](slides/Day3-Predictive-Maintenance-and-Next-Steps.pdf)

[NotebookLM Tool](https://notebooklm.google.com/notebook/6f5fc899-d689-4c31-aeac-1c9c11ddd671)

### Orange Hands-On

Dataset: [predictive_maintenance.csv](data/predictive_maintenance.csv)

### Predictive Maintenance ML Demo

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/grcc-resendiz/kaggle-example)

This notebook demonstrates predictive maintenance for milling machines using machine learning.

1. Click **Open in Codespaces**
2. Wait for the environment to load
3. Open the notebook
4. Click **Run All**

---

# Tools Used in the Workshop

- Claude, ChatGPT, Gemini, and Microsoft Copilot
- LM Studio (local LLMs)
- Google Teachable Machine
- Google AI Studio
- Orange Data Mining
- GitHub Codespaces
- Open manufacturing datasets

---

# Audience

- Manufacturing leaders
- Engineers and technicians
- Process improvement teams
- Workforce development organizations

---

# For Instructors

Editable slide decks are in the [instructor](instructor) folder. When you change a deck, export a new PDF and upload both: the .pptx to `instructor/` and the PDF to `slides/` with the same file name as before, so the links above keep working.

- `Day1-Prompting-and-Skills.pptx`
- `Day1-LM-Studio-Clayton.pptx` (Clayton's section)
- `Day2-Computer-Vision-and-Vibe-Coding.pptx`
- `Day3-Predictive-Maintenance-and-Next-Steps.pptx`
