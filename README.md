# Day 13 – AI-Powered Job Discovery & Analysis

## Overview
For this task, I used Claude with the **Indeed connector** to build a professional profile, define job search criteria, and discover internship opportunities matched to my background as a B.Tech IT student. I also briefly tested the **Dice connector** before switching to Indeed.

## Tools Used
- Claude.ai (Connectors: Dice, Indeed)
- Indeed MCP connector for live job search and job detail retrieval

## Process
1. Created a professional profile prompt covering my education, skills (C, Java, Python, JavaScript, HTML/CSS, MySQL, Git/GitHub), and project experience.
2. Defined job search criteria: Internship roles, Remote preferred, Chennai/Tamil Nadu location, last 30 days postings.
3. Ran job discovery using **Dice** first — found this connector is geared toward senior, US-based, full-time tech roles and returned no relevant India-based internships.
4. Switched to **Indeed**, which returned strong, relevant results for India-based and remote internships.
5. Reviewed and scored opportunities for fit, generated a skill-gap analysis, and compiled market insights.

## Discovered Opportunities (Top Matches via Indeed)

| Company | Role | Location | Match Score |
|---|---|---|---|
| BHAYAT NGO | Software Developer Intern | Remote | 90% |
| Adsquaretech Solutions | Python Developer Internship | Remote | 88% |
| Surya Informatics Solutions | Python Developer Intern | Chennai, TN | 85% |
| Expedite Informatics | Software Intern | Remote | 78% |
| Khurana Technology Solutions | Full Stack Developer Intern | Remote | 75% |
| Monkh AI | SDE Intern | Remote | 65% |
| Quagnitia | Full Stack Development Intern | Remote | 60% |

*(Full details, application links, stipend info, and rationale are in `Day13_Job_Discovery_Report.docx` / screenshots in this folder.)*

## Analysis Summary
- **Most in-demand skills:** Python, JavaScript, MySQL/databases, Git/GitHub, REST APIs, basic Agile/teamwork.
- **Skill gaps identified:** No framework experience yet (React, Django, Flask, or Node.js); no demonstrated REST API or cloud (AWS/Azure) exposure.
- **Market insight:** Entry-level/intern demand in Chennai/Tamil Nadu and India-remote is strongest for Python and full-stack (JS) roles. Typical stipends range ₹5,000–₹10,000/month.
- **Recommendation:** Build one small project using a framework (Flask/Django or React) to close the biggest gap before applying to full-stack-heavy roles.

## Key Learnings
- Different job-search connectors have very different regional and seniority coverage — Dice skewed heavily toward US senior tech roles, while Indeed had much better coverage for India-based student internships.
- Pairing a structured profile + criteria prompt with a discovery prompt produces well-organized, comparable results (match score, fit rationale, CTC) rather than a generic list.
- AI-assisted job search still requires human verification — all listings should be checked directly with the employer before applying.

## Files in This Folder
- `day13.md` – this summary file
- `Day13_Job_Discovery_Report.docx` – full opportunities table, skill-gap analysis, market insights, and recommendations
- Screenshots of the Claude conversation and connector usage (if added)
