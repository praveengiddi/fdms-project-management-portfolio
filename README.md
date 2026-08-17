# Fleet and Delivery Management System — Project Management Portfolio

Project management artefacts from a Master of IT capstone project, developed as part of a 5-person team building an admin-facing Fleet and Delivery Management System (FDMS) on WordPress, using **GoPeople** (an Australian same-day delivery company) as a reference case study.

This repository documents the **Project Management** contribution to the project — cost estimation, scheduling, and risk management — structured to align with PMBOK / CAPM knowledge areas.

## 📋 Project Overview

| | |
|---|---|
| **Project Type** | Academic capstone (Master of IT), admin-facing WordPress application |
| **Reference Client** | GoPeople (case study only — not a commercial engagement) |
| **Users** | Administrator, Driver, Customer (complaint-page only, no login) |
| **Duration** | 4 weeks |
| **Team Size** | 5 members |
| **My Role** | Project Management — cost estimate, WBS, Gantt chart, risk register |

## 💰 Cost Management

A bottom-up estimation method was used — pricing each item individually against real tool costs and market labour rates, then aggregating into totals. Direct costs stayed under **$50 AUD** by relying on free/open-source tools (WordPress, ACF, GitHub, LocalWP). Labour was separately benchmarked against real Australian WordPress developer rates ($32–$100/hr depending on experience level) to demonstrate cost-awareness, even though the work itself is unpaid academic effort.

| Item | Estimated Cost (AUD) | Notes |
|---|---|---|
| WordPress, ACF, GitHub, LocalWP | $0 | Open-source / free-tier tools |
| Hosting (staging) | $0–$10/month | Local dev environment preferred |
| Domain name (optional) | $15–$20 | One-time, only for public demo link |
| Google Maps Platform API | $0 | Free monthly credit covers testing volume |
| Contingency | $15–$20 | ~15% buffer on direct cost total |
| **Total Direct Cost** | **~$30–$50** | Excludes labour |

## 🗓️ Schedule Management

The project was decomposed into 6 phases and 20 tasks via a **Work Breakdown Structure**, then sequenced across a 4-week **Gantt chart** — with Admin and Driver modules running partially in parallel to fit the timeline.

Gantt chart : <img width="1508" height="651" alt="Gantt chart" src="https://github.com/user-attachments/assets/9632147c-3728-4647-85f8-1a26947e6d88" />
WBS : <img width="5667" height="522" alt="wbs_tree_v2" src="https://github.com/user-attachments/assets/8ad6d8fc-b1b0-47c3-84c6-1388d86c2257" />



## ⚠️ Risk Management

Risks were identified using PMBOK's risk categories (scope, schedule, resource, technical) rather than an ad hoc list:

| Risk | Relevance | Mitigation |
|---|---|---|
| Scope creep | Scope expanded once during the team's own drafting process | Locked scope before the next milestone; further ideas logged as future work |
| Time constraint vs. quality | 4-week window limits testing depth | Compressed testing phase prioritises core user flows over edge cases |
| Team skill variance | 5-person student team, mixed WordPress experience | Tasks allocated by skill level; code review on complex modules |
| No production cutover | System demonstrated academically, not deployed live | Framed explicitly as an academic prototype |
| Dummy data limitations | Testing uses synthetic, not real, operational data | Varied synthetic test scenarios generated |
| Technical/platform limitation | WordPress less flexible than custom-built software | Well-supported plugins (ACF) used over heavy custom PHP |

## 🎓 Why This Repository Exists

Built while preparing for the **CAPM (Certified Associate in Project Management)** exam, to translate PMBOK concepts (bottom-up estimating, WBS decomposition, structured risk identification) into a real, applied example.

## 📚 References (Harvard Style)

Anthropic 2026, *Claude* (Sonnet 5) [large language model], Anthropic, viewed 13 August 2026, <https://claude.ai>.

Codementor 2026, *Cost to Hire a WordPress Developer*, cited in Fiverr, viewed 13 August 2026, <https://www.fiverr.com/resources/guides/programming-tech/wordpress-developer-cost>.

Glassdoor 2026, *WordPress Developer Salaries in Australia*, viewed 13 August 2026, <https://www.glassdoor.com.au/Salaries/wordpress-developer-salary-SRCH_KO0,19.htm>.

Guinhouya, KA 2023, 'Project Management Body of Knowledge – an overview', *ScienceDirect Topics*, viewed 13 August 2026.

Khan, S, Saher, N & Yunis, MS 2019, 'Project Planning, Project Success and Project Risk', *Global Social Sciences Review*, vol. 4, no. 1, pp. 315–324.

Kutsch, E & Hall, M 2009, 'The Rational Choice of not Applying Project Risk Management in Information Technology Projects', *Project Management Journal*, vol. 40, no. 3, pp. 72–81.

Rose, KH 2013, 'A Guide to the Project Management Body of Knowledge (PMBOK Guide), Fifth Edition', *Project Management Journal*, vol. 44, no. 3, pp. e1–e1.

GoPeople 2026, *About GoPeople*, viewed 13 August 2026, <https://www.gopeople.com.au/about-us/>.

---
*Academic project — GoPeople is used only as a reference case study and this repository is not affiliated with or endorsed by GoPeople.*
