# AI and Manufacturing Training

Materials for the **AI & Manufacturing Workshop**, a hands-on training that helps manufacturing professionals understand and apply artificial intelligence in real production environments.

The workshop focuses on **practical, applied AI** that reduces downtime, improves quality, and supports the people on the floor.

## Training Format
- 3 days
- 3 hours per day
- 9 hours total

No prior AI or coding experience is required.

**Day 3 is here:** [jump to the Claude workshop guide](#day-3-claude-smb-workshop). Every prompt is on this page, with a copy button.

---

# Before Day 1

Please have these ready before the first session:

- **An AI account.** A free Claude ([claude.ai](https://claude.ai)) or ChatGPT ([chatgpt.com](https://chatgpt.com)) account works. If your company provides Microsoft Copilot or Gemini, bring that login too.
- **A free GitHub account** ([github.com](https://github.com)) for the demos on Days 2 and 3.
- **A laptop with a webcam** and Chrome or Edge.
- **LM Studio** ([lmstudio.ai](https://lmstudio.ai)) installed for Day 1.
- **Orange Data Mining** ([orangedatamining.com/download](https://orangedatamining.com/download/)) installed for Day 3.

---

# Workshop Sessions

## Day 1: Prompting, LLMs, and AI Projects
**Theme:** Get reliable answers from AI and build a reusable AI project for your job

| Time | Block |
|---|---|
| 0:00 to 0:10 | Welcome, introductions, and agenda |
| 0:10 to 0:30 | The state of manufacturing: what keeps you up at night, the workforce outlook, and the adoption gap |
| 0:30 to 0:55 | Prompting: hallucinations, safe use at work, and the RTFC framework (Role, Task, Format, Constraints) |
| 0:55 to 1:55 | AI projects: build and test a project for one of your real problems |
| 1:55 to 2:00 | Break |
| 2:00 to 2:55 | Local LLMs with LM Studio (led by Clayton) |
| 2:55 to 3:00 | Wrap up and questions |

Topics covered:

- The state of manufacturing: the workforce shortage and the technology adoption gap
- AI fundamentals and the three areas we cover in this training: language, vision, and data
- Spotting hallucinations and using AI safely with company information
- The RTFC prompting framework
- AI projects: saved instructions plus your documents, in the AI tool you already use
- Hands-on: building a project for SOPs, troubleshooting, or reporting
- Bonus: turning your project into a portable skill
- Local LLMs: running a model on your own computer with LM Studio

**Slides**

[Day 1 Slides (PDF)](slides/Day1-Prompting-and-Skills.pdf)

### AI Project Workshop

**Theme:** Package your instructions and documents once so the AI gives consistent answers every time

1. Participant Workbook
[Access the Day 1 Workbook](https://docs.google.com/document/d/1sAQ36oFIaEUiQMzUd1GpMWeI_vuQgNEs/edit?usp=sharing&ouid=108717541017706732541&rtpof=true&sd=true)

2. Demo Project and Reference Material
We will build a mill maintenance helper together. Its reference file is this technical manual:
[Bridgeport Knee Mill Technical Manual](https://bridgeportmachinetools.com/wp-content/uploads/KneeMill-Complete-Manual.pdf)

3. Where to Build Your Project

| Tool | How to build it |
|---|---|
| Claude (free plan works) | Projects > + New Project > Set project instructions, then add files |
| ChatGPT (free plan works) | New project > Project settings for instructions, then add files (5 files on Free) |
| Microsoft Copilot | Notebooks > New notebook > add files under References > ... > Instructions |
| Gemini, work or school account | Gems > New Gem > instructions, then Knowledge > Add files |
| Gemini, personal account | Settings > Skills > Create manually |
| Any other tool | Paste your instructions at the top of a new chat and attach your files |

4. Bonus: Turn It Into a Skill
Gems and custom GPTs are turning into skills. Download the demo skill, [mill-maintenance-helper.zip](skill/mill-maintenance-helper.zip), and see section 2.5 of the workbook to turn your own project into one.

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
- Deciding when you need a prompt, a project, or an app

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

## Day 3: Claude SMB Workshop
**Theme:** Put Claude to work on one real job from your shop, with a workspace that remembers how you work

Day 3 is a Claude SMB Workshop, run by the GRCC AI Incubator in partnership with The Right Place and Muskegon Community College.

| Time | Block |
|---|---|
| 0:00 to 0:15 | Welcome, the mental model, the 4Ds framework, and data safety |
| 0:15 to 0:50 | Demo: how I run my work with Claude, using folders called HQs |
| 0:50 to 1:15 | Hands-on: set up Claude and build your workspace |
| 1:15 to 1:35 | Hands-on: build the Example Equipment Co. HQ and run the demo prompts |
| 1:35 to 1:40 | Break |
| 1:40 to 2:10 | Hands-on: build an HQ for the one job you would hand off first |
| 2:10 to 2:25 | Hands-on: connect a tool |
| 2:25 to 2:50 | The Claude for Small Business plugin |
| 2:50 to 3:00 | Keep it sharp, questions, and survey |

Topics covered:

- The 4Ds of AI fluency: delegation, description, discernment, and diligence
- Context beats prompts: instructions, knowledge, and memory
- Hands-on: a Claude workspace with a CLAUDE.md rules file and a MEMORY.md notepad
- Hands-on: an HQ that quotes from a price list, refuses to make up prices, and remembers a customer's requirement
- Hands-on: your own HQ for quoting, quality, maintenance, or safety and training
- Connectors: letting Claude read a tool you already use, with your OK
- The Claude for Small Business plugin

**Slides**

[Day 3 Slides (PDF)](slides/Day3-Claude-SMB-Workshop.pdf)

### Claude Workshop Guide

**Theme:** Save your context once, so Claude works the way your shop does every time

This is your copy and paste guide. **Prompts are tucked into lines that start with ▸ Prompt.** Click the line to open it, click the copy icon in the top right corner of the gray box, then paste it into Claude. Every prompt works as is, except the one in Step 8, which has one blank (____) for you to fill in. After each step, "You should see" tells you it worked.

By the end you will have:

- Claude set up with your preferences and a few safety guardrails
- A Claude workspace folder that remembers how your shop works, from one session to the next
- A demo HQ for a fictional conveyor shop that quotes from a price list, refuses to make up prices, and remembers a customer's requirement
- An HQ of your own, built around the one job you would hand off first
- One of your tools connected to Claude
- The Claude for Small Business plugin installed and onboarded

**Before we start,** check these three things. The steps stall without them.

1. **Claude desktop app** installed and signed in ([claude.com/download](https://claude.com/download)). The phone app and the website can't reach folders on your computer.
2. **Your Claude Max code redeemed** on the web at [claude.ai](https://claude.ai). Codes don't work in the mobile app.
3. **This page open** in a browser next to Claude, so you can copy and paste.

Before you put company information into any AI tool, follow your company's AI policy. The demo company in this guide is fictional.

### Part 1: Set Up Claude

#### Step 1. Your general Claude preferences

Open a regular Claude chat and paste this. Claude will interview you and then write your preferences.

<details>
<summary><strong>Prompt: General Claude preferences</strong></summary>

```text
Interview me so you can write my personal preferences for Claude. Ask exactly these four questions, one at a time, and no others:

1. What is your role, what company do you work for, and what does the company make or do?
2. How do you like answers: short or detailed, and in paragraphs or bullet points?
3. How much should I explain technical things like files, settings, and spreadsheets?
4. When something is unclear, should I ask you first or make a reasonable call and tell you what I assumed?

When we're done, write my preferences as one block of text in the first person, under 300 words, with two short sections: "About Me" and "How to Work With Me." I will paste it into my Instructions for Claude in Settings, so give me only the text, ready to paste.
```

</details>

Answer the questions. When Claude gives you the finished text, click its copy button. Then:

1. Click your initials in the lower left corner of the app.
2. Click **Settings**, then **Your Claude**.
3. Paste the text into the **Instructions** box and save.

These instructions apply to every conversation.

**Looks different?** Some versions of the app show **Settings → Account → Instructions for Claude** instead. It is the same box.

**You should see:** your preferences saved under Instructions.

#### Step 2. Your guardrails

Go back to the same box: **Settings → Your Claude → Instructions**. Paste these lines **below** your preferences and save. They make Claude read your workspace rules first, and stop it from touching your files or sending anything without asking. Loosen them later, once you trust how it behaves.

<details>
<summary><strong>Guardrails to add to your Instructions</strong></summary>

```text
How I want you to work:
- When I'm working in a folder, read the CLAUDE.md and MEMORY.md files in that folder before doing anything else, and follow them.
- Before deleting, overwriting, or renaming any existing file, show me exactly what will change and wait for my confirmation.
- Never modify files outside the folder I'm currently working in unless I explicitly ask you to.
- For any multi-step task, outline a brief plan first and wait for my approval before executing.
- Before sending emails, posting messages, changing calendar events, or taking any other external action, show me the proposed action and wait for confirmation.
- If instructions conflict, required context is missing, or you are unsure which file should be changed, stop and ask instead of guessing.
- Preserve existing file names, folder structure, formatting, and content unless I explicitly ask you to change them.
```

</details>

**Looks different?** If your app still has a separate Cowork tab, these go in **Settings → Cowork**: click **Edit** next to **Global instructions**.

**You should see:** your preferences and the guardrails together in one Instructions box.

---

### Part 2: Build Your Workspace

Here is what you're building. Claude writes every file for you.

```text
Claude Workspace/                 ← the "root" folder: rules here apply to everything
├── CLAUDE.md                     ← how Claude should behave (the rules)
├── MEMORY.md                     ← what Claude should remember (the notepad)
├── 00_Resources/
│   └── voice-principles.md       ← how you write
├── Example Equipment Co. HQ/     ← an "HQ": rules for one job only (demo)
│   ├── CLAUDE.md                 ← instructions
│   ├── MEMORY.md                 ← memory
│   └── Example Equipment Co. HQ Resources/   ← knowledge
│       ├── price-list.md
│       └── past-quote.md
└── (your own HQ)/                ← the job you would hand off first
```

**About the folder:** Claude works inside one folder on your computer, the one you pick. It can read, create, and change files in that folder, and it sees nothing outside it. We start with a brand new, empty folder, so nothing of yours is in reach today. Files Claude reads are processed on Anthropic's servers, like anything you type. If your work laptop blocks this step, that is your IT policy: pair with a neighbor today.

**Heads up:** because of the guardrails from Step 2, Claude will show you a plan or the changes and then wait before doing anything. That's the guardrails working. Read the plan and reply **"Looks good, go ahead."**

#### Step 3. Create the root folder

1. In Finder (or File Explorer), create a folder in Documents called **Claude Workspace**. Leave it empty.
2. In the Claude desktop app, start a new chat. In the chat bar, click **Work in a folder** (some versions say **Work in a project or folder**) and choose your Claude Workspace folder. Jon will show you where it is.
3. Open the prompt below and paste it into Claude. It creates your three starter files.

**From now on, every chat for this guide starts the same way:** new chat, **Work in a folder**, Claude Workspace. A chat without the folder selected can't see your files.

<details>
<summary><strong>Prompt: Create your workspace files</strong></summary>

```text
Set up this folder as my Claude workspace. Create these three files with exactly the content shown between the markers, then create a folder called 00_Resources and put voice-principles.md inside it. CLAUDE.md and MEMORY.md stay in the root of this folder. When you're done, show me the folder tree.

=== FILE: CLAUDE.md ===
> Adapted from the Cowork Toolkit by Jeff Su (coworkacademy.ai/toolkit)

# CLAUDE.md

## Memory System

At the start of every session, read MEMORY.md before responding. Use what you find to inform your work. Don't announce what you found, just be informed by it.

When I say "remember this," write the information to MEMORY.md immediately and confirm you've done it.

**Where things go:** Apply two tests when deciding where to save something. Test 1: Does it prescribe behavior? Look for words like "always," "never," "before doing X, do Y." If yes, add it to this file (CLAUDE.md) under the right section. Test 2: Does it describe a fact about the world that could change? Contact details, job status, decisions, things I've told you to remember. If yes, add it to MEMORY.md. When unsure, suggest which file it belongs in and ask me to confirm.

Before working on a task, read the CLAUDE.md and MEMORY.md in every folder between this root folder and the folder the task's files live in, top to bottom.

## Preferences

- Write the way a good shift lead talks: plain, short, specific. If it sounds like a corporate memo, rewrite it.
- Keep responses concise, under 300 words unless I ask for more detail.
- Give me one strong recommendation. Don't give me three options unless I ask for alternatives.

## Rules

- Show your work. Any number you give me comes with the math and the file it came from.
- If you're not sure about something, say so. Never guess a price, a tolerance, a date, or a safety requirement.
- Everything you produce is a draft or a recommendation. Nothing goes to a customer, a supplier, or an employee until I approve it.
- Never put one customer's drawings, part numbers, or pricing into work for another customer.
- Before producing any written content on my behalf, read voice-principles.md in the 00_Resources folder.

## Routing Map

*Add a row to this table each time a new HQ is created. At the start of a task, check this table to decide which HQ folder to load.*

| HQ | Route here when I... |
| :---- | :---- |

## References

*Files in 00_Resources. Load each one only when its trigger applies.*

| Resource | Read when... |
| :---- | :---- |
| voice-principles.md | Writing any content on my behalf |

## Creating New HQs

When I ask you to create a new HQ, create a subfolder with the HQ name and add these three items inside:

1. **CLAUDE.md** with these sections in this order:
   - **Identity**: One paragraph: who you are in this HQ, what routes here, what doesn't, and what stays with me.
   - **Resources**: Table with "Resource" and "Read when..." columns. Start empty.
   - **Workflow**: Numbered steps for the primary task. Start simple; I'll refine over time.
   - **Editorial Rules**: Always opens with: "Follow my voice principles in 00_Resources (voice-principles.md)." Then add rules specific to this kind of work.
2. **MEMORY.md** with this structure:
   - Header: "[HQ Name] Memory"
   - Sections: Contacts (people relevant to this area) and Key Decisions (the reasoning behind choices).
   - You fill this in over time as we work. I don't write it by hand.
3. **[HQ Name] Resources/**: An empty folder for this area's reference files.

After creating the HQ, add a new row to the Routing Map above.
=== END FILE ===

=== FILE: MEMORY.md ===
> Adapted from the Cowork Toolkit by Jeff Su (coworkacademy.ai/toolkit)

# MEMORY.md

*Last updated: (today's date)*

## Active Projects

*What I'm working on right now. I'll say "add this to active projects" when I start something and "this is done" when it's finished.*

- **Workspace setup.** Building my Claude workspace and my first HQ.

## Core Memory

*Facts Claude has learned about me and my work. I'll say "remember this" to add an entry.*
=== END FILE ===

=== FILE: voice-principles.md ===
> Adapted from the Cowork Toolkit by Jeff Su (coworkacademy.ai/toolkit)

# Voice Principles

*These rules teach Claude how to write in my voice. They start generic. I'll make them mine over time.*

## Tone

- Direct and friendly. State the key point first, then add supporting detail.
- With customers: confident and specific. If we were late or wrong, say so and say what we're doing about it.
- With the floor: short sentences, plain words.

## Words and Phrases to Avoid

- Never use: "per my last email," "leverage," "circle back," "touch base," "at this time."
- No em dashes. Use commas, colons, or periods instead.

## Formatting Defaults

- One idea per paragraph.
- Numbers get units, every time.
- Use lists for steps, sentences for explanations.
=== END FILE ===
```

</details>

**You should see:** a folder tree with CLAUDE.md, MEMORY.md, and 00_Resources/voice-principles.md.

#### Step 4. Make it yours

The starter files are generic. Four quick questions turn them into yours.

<details>
<summary><strong>Prompt: Personalize your workspace</strong></summary>

```text
Interview me to personalize my workspace. Ask exactly these four questions, one at a time, and no others:

1. What company do you work for, what does it make, and roughly how many people work there?
2. What is your role, and which three tasks eat most of your week?
3. Where does your work live today (for example an ERP, spreadsheets, email, a shared drive, paper)?
4. What is one thing I should always do, or never do, when I work on your company's business?

Sort each answer using the two tests in the Memory System section of CLAUDE.md: behavior rules go in CLAUDE.md under Preferences or Rules, facts go in MEMORY.md under Core Memory. Keep each entry to one or two sentences. When we're done, show me exactly what you added to each file.
```

</details>

**You should see:** a list of what Claude added to CLAUDE.md and to MEMORY.md, in your own words.

---

### Part 3: Demo HQ, Example Equipment Co.

An HQ is a subfolder for one job, with its own rules that stack on top of the root rules. Everyone builds the same demo HQ first, so we can compare results.

Example Equipment Co. is a fictional conveyor shop: 60 people in West Michigan, custom conveyors for food and industrial plants. Its customers, prices, and quotes are made up for this demo.

Every HQ saves three things:

| Part | What it is | Where it lives |
| :---- | :---- | :---- |
| **Instructions** | Rules that always apply | CLAUDE.md |
| **Knowledge** | Reference material | The Resources folder |
| **Memory** | What changes over time | MEMORY.md |

#### Step 5. Test your memory first

Before the HQ, one quick win. In your workspace, type:

```text
Remember this: I don't take meetings before my second cup of coffee.
```

**Look for:** Claude confirming it saved the line to MEMORY.md, the notepad file in your workspace. Then start a **new** chat with your workspace folder selected and ask:

```text
When's a good time to schedule a meeting with me?
```

**You should see:** an answer that steers you away from first thing in the morning. It didn't just repeat the fact, it used it.

#### Step 6. Build the HQ

One prompt builds all three parts.

<details>
<summary><strong>Prompt: Create the Example Equipment Co. HQ</strong></summary>

```text
Create an HQ called Example Equipment Co. HQ, following the "Creating New HQs" instructions in my root CLAUDE.md. This is a demo HQ for a fictional company. Use exactly the content below.

=== Its CLAUDE.md ===

Identity: You are the quoting assistant for Example Equipment Co., a 60 person shop in West Michigan that designs and builds custom conveyors and material handling equipment for food processing and industrial plants. Customer requests, quotes, and follow up emails route here. I approve every quote before it goes out. You never send anything.

Resources table, two rows:
price-list.md | Pricing anything
past-quote.md | Drafting any quote, for the format and the usual line items

Workflow:
1. Read the request and this HQ's MEMORY.md. Apply every requirement listed for that customer and every Key Decision that is still in effect.
2. Build the quote in the format of past-quote.md, using only prices from price-list.md.
3. Use the past quote as the pattern for line items: one 1 HP motor and gearbox, one basic control panel, guarding for the full length, and 8 hours of engineering and drawings, unless the request or the customer's requirements say otherwise. List these as assumptions.
4. Show the math for the total, then the lead time and assumptions.
5. Draft the quote in your reply. Don't create a file unless I ask.

Editorial Rules, after the standard opening line:
- Pricing rule: never give a price that isn't in price-list.md. If an item is missing, say "Not on the price list, needs an estimate from engineering" and leave it out of the total.
- Quotes are valid for 30 days.
- Standard lead time is 8 to 10 weeks from approved drawings.
- Freight and installation are always quoted separately.
- Plain, direct language. Answer first.

=== Its MEMORY.md ===

# Example Equipment Co. HQ Memory

*Last updated: November 9, 2026*

## Contacts

- Customer A: snack food plant. Buys conveyors for packing lines. Contact is their purchasing manager.
- Customer B: pet food plant. Wants a recommended spare parts kit included in every quote.
- Customer C: automotive parts plant. Expects quotes within 3 business days and pays Net 45.

## Open Requests

- Customer A: 40 foot incline conveyor for bagged snacks, quote due November 13.
- Customer C: replacement belt and guarding for an existing line, quote due November 12.

## Key Decisions

- October 2026: Through December 31, add a 5 percent material surcharge to all quotes because steel prices went up.

=== FILE in its Resources folder: price-list.md ===
# Example Equipment Co. Price List

Fictional prices for training use only. Effective October 1, 2026.

| Item | Unit | Price |
| :---- | :---- | :---- |
| Flat belt conveyor, painted carbon steel frame | per foot | $450 |
| Flat belt conveyor, stainless steel frame | per foot | $1,000 |
| Incline section, any frame (add on) | each | $4,000 |
| Motor and gearbox, 1 HP | each | $2,200 |
| Motor and gearbox, 1 HP, washdown rated | each | $3,500 |
| Safety guarding, painted | per foot | $125 |
| Safety guarding, stainless | per foot | $250 |
| Basic control panel (start, stop, e-stop, speed) | each | $3,000 |
| Engineering and drawings | per hour | $150 |
| Installation labor | per hour | $135 |
| Recommended spare parts kit (belt, bearings, sprockets) | each | $1,500 |

Freight is quoted separately. Installation is quoted separately when requested.
=== END FILE ===

=== FILE in its Resources folder: past-quote.md ===
# Example Equipment Co. Quote Q-2026-118

Date: September 22, 2026
Customer: Customer B (pet food plant)
Valid for: 30 days

## Scope

One 30 foot flat belt conveyor to move filled bags from the bagger to the palletizer.

| Item | Qty | Unit price | Total |
| :---- | :---- | :---- | :---- |
| Flat belt conveyor, painted carbon steel frame | 30 ft | $450 | $13,500 |
| Motor and gearbox, 1 HP | 1 | $2,200 | $2,200 |
| Safety guarding, painted | 30 ft | $125 | $3,750 |
| Basic control panel | 1 | $3,000 | $3,000 |
| Engineering and drawings | 8 hrs | $150 | $1,200 |
| Recommended spare parts kit | 1 | $1,500 | $1,500 |
| **Total** | | | **$25,150** |

Lead time: 8 to 10 weeks from approved drawings.
Assumptions: Customer provides power to the control panel location. Freight and installation not included.
Terms: Net 30. FOB our dock.
=== END FILE ===

Finally, add this row to the Routing Map in my root CLAUDE.md: Example Equipment Co. HQ | ...am working on an Example Equipment Co. customer request, quote, or follow up.

Show me the folder tree when you're done.
```

</details>

**You should see:** an Example Equipment Co. HQ folder holding CLAUDE.md, MEMORY.md, and a Resources folder with two files, plus a new row in your Routing Map.

#### Step 7. Run the demo prompts, in order

Start a **new** chat with your workspace folder selected first, so Claude starts fresh and has to find its own way.

**Prompt 1, draft a quote** (expect about **$35,070**):

```text
Draft a quote for this Example Equipment Co. request:

From: Purchasing Manager, Customer A
Subject: Quote request, incline conveyor
Hi,
We need a quote for a 40 foot incline belt conveyor to move bagged snacks from our packing line up to the palletizer, about 600 bags per hour. Please include a control panel and guarding. We'd like the quote by Friday.
Thanks
```

**You should see:** the past quote's format, painted steel prices, and a 5 percent surcharge. Nobody typed the surcharge. It came from memory.

**Prompt 2, what's open:**

```text
What Example Equipment Co. quotes are open, and what's due first?
```

**You should see:** Customer C due November 12, then Customer A due November 13. Customer A still shows as open, because memory only changes when you tell it something changed.

**Prompt 3, the guardrail** (expect "Not on the price list"):

```text
Customer A also wants a metal detector on this conveyor. Add it to the quote.
```

**You should see:** no made up price. The total stays at $35,070.

**Remember this:**

```text
Remember this: Customer A requires stainless steel frames and guarding on every conveyor in their plant because of daily washdown.
```

Then ask Claude to show you what it saved:

```text
Show me that memory file.
```

**You should see:** the new fact on Customer A's line, and nothing else changed. You didn't open the file. Claude did the upkeep.

**Ask again.** Start a **new** chat with your workspace folder selected, then:

```text
Redo the Customer A quote for Example Equipment Co.
```

**You should see:** a stainless frame, stainless guarding, a washdown rated motor it picked on its own, and a total of about **$64,785**.

**Got about $63,420 instead?** Claude kept the standard motor. Ask it: "Should a plant with daily washdown get the washdown rated motor?" Checking its work is part of the job.

| | Before | After |
| :---- | :---- | :---- |
| Conveyor frame, 40 ft | $18,000 | $40,000 |
| Guarding, 40 ft | $5,000 | $10,000 |
| Motor | $2,200 | $3,500 |
| Total with surcharge | $35,070 | $64,785 |

Same request. Same tool. One saved fact nearly doubled the quote.

---

### Part 4: Build Your Own HQ

Now the real one. Pick the one job you would hand off first. Start from a starter HQ close to your job, or build one from scratch in Step 8.

| Starter HQ | Good for |
| :---- | :---- |
| [Requests and Quotes](starters/requests-and-quotes.md) | RFQs, estimates, quotes, and follow ups |
| [Quality](starters/quality.md) | Nonconformance reports, corrective actions, customer responses |
| [Maintenance](starters/maintenance.md) | Downtime, preventive maintenance, work orders |
| [Safety and Training](starters/safety-and-training.md) | Work instructions, toolbox talks, onboarding |

More ideas if none of those fit:

| HQ idea | Route here when I... |
| :---- | :---- |
| Purchasing HQ | am chasing a late PO, comparing supplier quotes, or planning a material buy |
| Scheduling HQ | am building the week's production schedule or answering "when will it ship" |
| Email HQ | am triaging my inbox or drafting replies |
| Meetings HQ | am preparing for a meeting or turning notes into action items |
| HR and Hiring HQ | am writing a job posting, interview questions, or a first week plan |

#### Step 8. Create your HQ

Fill in the one blank with your HQ's name, then paste.

<details>
<summary><strong>Prompt: Create your own HQ (fill in one blank)</strong></summary>

```text
Create an HQ called ____________, following the "Creating New HQs" instructions in my root CLAUDE.md.

Before you write anything, interview me. Ask exactly these five questions, one at a time, and no others:

1. What do you bring me for this job (an email, an export, a form, notes)?
2. What should I hand back (a draft, a report, a list, a filled in template)?
3. Walk me through the steps you follow today when you do this by hand.
4. What must I never do or never decide in this job? What stays with you?
5. Who reads the result, and what do they care about most?

Then write the Identity, Workflow, and Editorial Rules from my answers. Put what stays with me into the Identity paragraph and repeat it as a stop in the Workflow, the same way the demo HQ stops at a price that isn't on the price list. Add the row to the Routing Map in my root CLAUDE.md. Show me each file you wrote.
```

</details>

**You should see:** your new HQ folder, a Workflow in your own steps, and a new row in the Routing Map.

#### Step 9. Give it a real file and a one line task

**Before a file goes in the folder, ask yourself:**

- Is this customer drawing or spec under an NDA? Read the agreement first.
- Is this export controlled work? Talk to your compliance lead first.
- Personnel and medical records stay out.
- Passwords and access tokens never go in a chat or a file.

No safe file handy today? Skip the file and describe a made up example in a sentence. You can add real files back at the shop.

1. Drag one file into your **Claude Workspace** folder (the top level is fine).
2. Paste this:

```text
I dropped a file into my workspace. Move it into the Resources folder of the HQ where it belongs, add it to that HQ's Resources table with a "Read when..." trigger, and tell me where you put it.
```

3. Start a new chat with your workspace folder selected and give your HQ a one line job, in your own words. For example: "Start the write up for last night's issue" or "What should we fix first?"

**You should see:** Claude follow your steps and stop where you told it to stop. If it gets something wrong, correct it and say **"remember this."**

---

### Part 5: Connect a Tool

A connector is a plug. It lets Claude read, and with your OK act, inside a tool you already use. **Read** means Claude can look. **Write** means Claude can act, and it asks you first. You sign in to each tool yourself, and you can switch it off anytime.

#### Step 10. Connect email or calendar and test it

Jon will show you where connectors are in the Claude desktop app. Pick Gmail or Google Calendar (or the Microsoft equivalent), sign in, and approve.

Then paste one of these:

```text
What are my most recent emails about? Summarize the top 5.
```

```text
What does my schedule look like this week? Any conflicts I should know about?
```

**You should see:** your real inbox or calendar, summarized.

**Work account blocked?** Many companies lock this down. Use a personal account today, or watch a neighbor, and ask your IT lead about it this week. **Sign in window missing?** It often opens behind the app.

#### Step 11. (If time) Give your inbox an HQ

<details>
<summary><strong>Prompt: Create an Email HQ</strong></summary>

```text
Create an HQ called Email HQ, following the "Creating New HQs" instructions in my root CLAUDE.md. Fill in the sections with this content:

Identity: You are my inbox assistant. With my email connector on, you read new mail, sort it, and draft replies for me to review. You draft only. You never send, delete, or archive. Everything about email lives here unless another HQ's Routing Map row fits better, and when it does, tell me.

Workflow:
1. Sort new mail into four groups: needs my decision, needs a routine reply, FYI only, and automated or junk.
2. For each message that needs a decision, give me one line: who, what they need, by when.
3. For routine replies, check whether a thread already exists with that person, then draft the reply in that thread and save it as a draft.
4. Match the formality of the message I'm replying to.
5. Tell me what you drafted and what you left alone. Never tell me something is handled unless a draft exists.

Editorial Rules, after the standard opening line:
- Lead with the answer. Dates and quantities go in the first two lines.
- No pricing in an email unless I gave you the number in this session.

Add this row to the Routing Map: Email HQ | ...am triaging my inbox or drafting replies to customers, suppliers, or the team.
```

</details>

Then, in a new chat with your workspace folder selected:

```text
Triage my inbox.
```

**You should see:** four groups, a one line summary for anything that needs your decision, and drafts waiting in your email. Nothing sent.

---

### Part 6: The Claude for Small Business Plugin

The plugin is a package of ready made workflows and connectors for the front office: cash, sales, marketing, proposals, hiring. Your HQs know your shop. The plugin knows small business. Use both.

#### Step 12. Install it and run onboarding

1. In the Claude desktop app, open **Customize** in the left sidebar.
2. Go to **Plugins**, click the plus, and install **Small Business**.
3. Type:

```text
/smb-onboard
```

Claude asks a few questions about your business and helps you connect a tool or two.

**You should see:** the plugin toggle on, and an onboarding interview.

#### Step 13. Run your first workflow

Try one of these and read what comes back with the four Ds in mind: is it accurate, what is missing, what needs pushback.

| Command | In a shop, use it for |
| :---- | :---- |
| `/monday-brief` | The week ahead and your top three, every Monday |
| `/proposal-builder` | Turning an RFQ email into a priced first draft |
| `/speed-to-lead` | A same day reply to a new customer inquiry |
| `/close-month` | Month end reconciliation and the story in the numbers |

Not every workflow fits a manufacturer, and the plugin's connectors may not include your ERP. Check the connector list for the systems you run.

---

### Part 7: Keep It Sharp

Use these whenever you have a few minutes. They make the workspace smarter over time.

**Teach it once.** Any time you correct Claude, say "remember this" and it saves the correction.

**End of session audit** (run once to create the skill, then say "audit this session" at the end of any session):

<details>
<summary><strong>Prompt: Create the session audit skill</strong></summary>

```text
Create a skill called session-audit. It should run at the end of any session and do exactly two things:

1. Scan the whole conversation for corrections I made to your output, preferences I stated directly (words like "always," "never," "I prefer"), decisions I made, and new facts about me or my work that you didn't already know.
2. For anything not already written in my CLAUDE.md or MEMORY.md files, tell me the exact wording to save and which file and section it goes in, then wait for me to approve before writing anything.

If nothing new came up, just say so. Trigger it whenever I say "audit this session," "session audit," or "what did we miss."
```

</details>

**Right file, right place** (run after a few weeks):

<details>
<summary><strong>Prompt: Right file, right place</strong></summary>

```text
Review my root CLAUDE.md and MEMORY.md. In CLAUDE.md, flag any entry whose primary purpose is recording a fact or status rather than prescribing how you should behave. In MEMORY.md, flag any entry whose primary purpose is telling you how to behave rather than recording a fact. Recommend where each flagged entry should move.
```

</details>

**Add an HQ whenever a job repeats.** Reuse the Step 8 prompt. One HQ per job, not one giant folder.

---

### If Something Goes Wrong

- **Claude is waiting and nothing happens:** it's showing you a plan and waiting for approval. Scroll up, read it, and reply "Looks good, go ahead."
- **Claude says it can't find a file:** the file is still in Downloads or on the Desktop. Drag it into your Claude Workspace folder and ask again.
- **Claude answers without using the HQ:** the chat doesn't have your folder. Start a new chat, click **Work in a folder**, and choose Claude Workspace. If it still skips the HQ, say "Read my CLAUDE.md and MEMORY.md first."
- **Claude made up a price, or skipped a step:** say "Stop. Follow this HQ's workflow." Then say "remember this" so it sticks.
- **Your quote total is different from the guide:** ask Claude to show the math line by line. Check that it used 8 hours of engineering and added the 5 percent surcharge.
- **A connector won't sign in:** look for a sign in window behind the app. If your work account is blocked, use a personal account today.
- **You pasted a prompt and got a wall of questions:** that's the interview. Answer one at a time. Short answers are fine.

*The workspace structure in Day 3 is adapted from Jeff Su's Cowork Toolkit ([coworkacademy.ai/toolkit](https://coworkacademy.ai/toolkit)).*

---

## On Your Own: Predictive Maintenance and Next Steps
**Theme:** Predict machine failures from data and plan your first AI pilot

This was the original Day 3. The materials stay here so you can work through them at your own pace.

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
- The Claude desktop app and the Claude for Small Business plugin
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
- `Day3-Claude-SMB-Workshop.pptx`
- `Day3-facilitator-plan.md` (run of show for the Claude SMB Workshop)
