# Increasing voice input usage on ChatGPT mobile in India

A product case study in three milestones: understand why so few Indian users use voice input on the ChatGPT mobile app, find the real barrier for one segment, and design a solution.

**Live prototype:** https://practice-out-loud.vercel.app

## The short version

- **Landscape:** India already talks to its phone (Google voice search, WhatsApp voice notes, Hinglish Alexa commands), just not to ChatGPT.
- **Segment:** job seekers and freshers (21–30). Interviews are spoken, so if voice can't win for interview practice, it won't win anywhere.
- **Barrier:** social and about control, not awareness. Job seekers prep in shared spaces (65% say "people around me" stops them) and need to check high-stakes text before it sends (53%). Hinglish misrecognition (44%) makes both worse.
- **Solution: Practice Out Loud.** A private, reviewable voice mock interview inside ChatGPT. A contextual card offers it, quiet mode works with earphones, you hold to talk, review and edit the transcript, then get feedback.
- **North Star:** weekly voice messages from India = weekly active voice users × voice messages per voice user.

## Repository

| Folder | What's inside |
| --- | --- |
| `milestone-1-landscape/` | 3-slide deck on the Indian voice landscape, the ChatGPT voice UX and competitors, and a KPI tree; slide source files |
| `milestone-2-research/` | 3-slide deck on the chosen segment, research insights and the Problem Framing Canvas; research kit (segments, hypotheses, survey, interview guide); survey dataset; slide source files |
| `milestone-3-solution/` | 3-pager (problem, goals, solution directions with ICE scores, user flow, wireframes, launch plan); annotated wireframes; user-flow diagram |
| `prototype/` | Single-file HTML prototype, deployed on Vercel |

## Running the prototype

Open `prototype/index.html` in a browser; there's no build step. In Chrome, holding the mic button transcribes your speech live (allow mic access). Elsewhere, a sample answer plays. Use **Annotations on/off** to show the design notes.

Export views for wireframes: `index.html?board=1` (screens 1–3 with notes), `?board=2` (screens 4–6 with notes), `?board=3` (all six in a row).

To deploy: `npx vercel --prod` from the `prototype/` folder, or drag the folder into Vercel.

## A note on the research data

The Milestone 2 survey responses (`survey_responses_mock.csv`, N = 34) and the interview quotes are **simulated**, generated with mentor approval because of time constraints. Every number in the Milestone 2 and 3 documents is calculated from that dataset. Market figures in Milestone 1 and the segment sizing come from cited public sources, listed on each slide.

## Sources (selected)

- OpenAI / TechCrunch: India has 100M+ weekly ChatGPT users (Feb 2026); India is now ChatGPT's largest market (Economic Times, Nov 2026)
- Google India: voice search 2× the global average; 40%+ of Gemini Indian-language users rely on voice; Gemini Live in 25+ Indian languages
- Amazon India: about 1 in 2 Echo users use the multilingual Hindi/English mode
- State of Working India 2026 (Azim Premji University); Apna Interview Readiness Index 2025; LinkedIn India job seeker survey (Jan 2026)
