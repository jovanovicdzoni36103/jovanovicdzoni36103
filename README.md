# Nikola Jovanović

Co-founder at CuliFlow, where I handle development and automation. BSc in Information Technologies (MEF, Belgrade, 2026). Learning Python toward AI/ML.

I build websites and the automation behind them: forms that write to Google Sheets and send email, n8n workflows that connect Gmail, Sheets and LLM APIs, and small JavaScript tools on top of Webflow. Most of my recent code was written with Claude Code as an AI pair programmer. I write the spec, make the decisions, review, test and deploy. Writing the same things unaided is what I'm working toward.

I'm open to internship and junior roles in workflow automation, web development or frontend, in Belgrade or remote.

## What I'm working on

**CuliFlow, Co-founder (since July 2026).** A small web and automation agency in Serbia. My side is development and automation.

- An AI client-finding system for the agency: four scheduled Claude agents (outreach, lead handling, daily and weekly reports) and two n8n webhook workflows, a Gmail send bridge (attachments and threading) and a Google Sheets read/write service. State lives in Google Sheets and Drive. In September 2026 it sent 343 cold emails; the n8n workflows logged 486 successful runs between 17 and 21 September. It has been paused since 21 September, when the n8n plan's monthly execution limit ran out.
- Five client websites built in September 2026, all pre-launch or in client review: a fitness studio, a dry cleaner, holiday apartments, a villa and spa, and a B2B caterer. They are static sites (one in Astro) with Google Apps Script backends that write inquiries and orders to Google Sheets and email the business. The repositories stay private until each client launches and agrees to be shown.

**Personal n8n workflows (March to June 2026).**

- Sara, trend research: SerpAPI and Tavily results go to a Groq-hosted LLM that proposes topics, then to Google Sheets, a ClickUp task and a Slack report.
- AI Gmail auto-responder: a Groq-hosted LLM reads incoming mail and either drafts a reply from a Google Sheets knowledge base, which is sent, or marks the email as spam or "Needs Review". Every run is logged to Sheets, with a Slack alert for review items.

Neither workflow is public yet. I can walk through both in an interview.

## Selected public work

| Project | What it is | Built with |
|---|---|---|
| [Invoice Generator](https://github.com/jovanovicdzoni36103/invoice-generator) | Five-step service picker. Every choice lives in one state object, the total updates as you pick, and it downloads a PDF with a reference number. No backend. [Live](https://nikola-jovanovic-guess-my-number.webflow.io/generator-faktura) | JavaScript, jsPDF, Webflow |
| [Website Cost Calculator](https://github.com/jovanovicdzoni36103/cost-calculator) | Multi-step quote form that ends with a price total and an estimated delivery date that skips weekends. | JavaScript, Webflow |
| [Tic Tac Toe](https://github.com/jovanovicdzoni36103/tictactoe-js) | A bot that wins, blocks or plays random. It's beatable: an optimal player wins about 93% of games, and the README shows why. [Live](https://klonovi.webflow.io/x-o-game) | JavaScript, Webflow |
| [Python 100 Days of Code](https://github.com/jovanovicdzoni36103/python-100-days-of-code) | My Python learning log since 16 August 2026: fundamentals, OOP, CSV and JSON, first API calls with requests. | Python |

Smaller ones: a [two-page Webflow invitation](https://github.com/jovanovicdzoni36103/wedding-invitation) for a real 2025 wedding (the RSVP uses Webflow's native form), a [landing-page template](https://github.com/jovanovicdzoni36103/webflow-animation-practice) I rebuilt in Webflow to practise carousels and scroll counters, and [Guess My Number](https://github.com/jovanovicdzoni36103/guess-my-number), the course exercise I started with. Its code is the course's reference solution.

The Webflow layouts were built visually in 2025, so those repos hold only the JavaScript embeds, uploaded in August 2026. That is why each one has a single code commit.

## Learning now

- Python, through Angela Yu's 100 Days of Code. I started on 16 August 2026 and commit my progress as I go.
- Next: SQL, then machine learning fundamentals.

## What I can't do yet

I have built TypeScript and Apps Script backends with AI assistance; writing them unaided is what I'm working on. No SQL, React or machine learning yet, and I haven't worked in a team on someone else's codebase. That last one is most of why I want a junior role.

## Background

- BSc in Information Technologies (Applied Information Technologies, 240 ECTS), MEF, Belgrade. October 2022 to July 2026, GPA 8.42/10.
- Thesis: a literature-based analysis of no-code business-process automation with n8n, covering n8n's architecture, a comparison of n8n, Zapier and Make, and two illustrative process scenarios.
- English C1 (course certificate, 2022). Serbian native.
- Before this I ran a short-form video brand, Short Form Cuts (2023), and a small Instagram shop, eProdaya (2022 to 2023).

## Contact

[LinkedIn](https://www.linkedin.com/in/nikola-jovanovic-dev/) · nikola.jovanovic.mef@gmail.com
