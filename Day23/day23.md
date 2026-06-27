##Day-23 Build Your Customer & MVP Blueprint

# Customer & MVP Blueprint

## Executive Summary

A unified platform for final-year Indian students that combines job search by company name, AI-powered resume-to-JD matching, skill-gap analysis, and ATS-optimized resume generation — eliminating the need to juggle multiple job portals and resume tools. A working backend prototype already exists; the next priority is validating demand with real users before scaling features.

## Ideal Customer Profile (ICP)

| Attribute | Detail |
|---|---|
| Who | Final-year undergraduate/postgraduate students (Engineering, CS, MBA, Commerce) |
| Geography | Tier 1–3 cities in India |
| Stage | 6–12 months from graduation, actively job hunting or about to start |
| Tech comfort | Smartphone-first, moderately tech-savvy, active on LinkedIn/Telegram/WhatsApp groups |
| Budget | Low to zero willingness to pay upfront; price-sensitive |
| Channel | College placement cells, WhatsApp/Telegram job groups, Instagram, campus ambassadors |

## Buyer Persona

| Field | Detail |
|---|---|
| Name | "Rahul/Priya, the Final-Year Job Seeker" |
| Age | 20–23 |
| Education | B.Tech/B.E./MBA/B.Com final year |
| Goals | Land a job before/at graduation, avoid backlog of rejections, look "industry-ready" |
| Frustrations | Applying on 5+ portals, resume rejected silently by ATS, doesn't know which skills recruiters actually want |
| Decision trigger | Sees friends getting interview calls, placement season starts, sees a "match %" feature demo |
| Where they hang out | Placement WhatsApp groups, Naukri/LinkedIn, Instagram reels, YouTube career channels |

## Top 10 Customer Pain Points

| # | Pain Point |
|---|---|
| 1 | Searching the same company across multiple job sites repeatedly |
| 2 | No clarity on whether they're "qualified enough" for a role |
| 3 | Resume gets auto-rejected by ATS before human review |
| 4 | Don't know which specific skills are missing for a target role |
| 5 | Generic resumes don't match job-specific keywords |
| 6 | Time wasted tailoring resumes manually for each application |
| 7 | No feedback loop — silence after applying, no idea why rejected |
| 8 | Limited awareness of which companies are currently hiring for their profile |
| 9 | Anxiety/confidence gap due to lack of structured guidance |
| 10 | Free tools are scattered (separate parser, separate tracker, separate builder) |

## Customer Journey

| Stage | Student Behavior | Your Opportunity |
|---|---|---|
| **Awareness** | Sees peers struggling with rejections; discovers tool via college group/Instagram | Share relatable "ATS rejected me" content, referral from placement cell |
| **Consideration** | Tries uploading resume to see match % "for fun" or out of curiosity | Make first-use instant and free — no signup friction |
| **Purchase** | Decides to use regularly during active placement season (free or low-cost) | Freemium model; paid tier for unlimited resume generations |
| **Retention** | Returns weekly during placement season to check new company matches | Email/WhatsApp alerts for new matching jobs, gamified skill progress |

## Key Customer Objections

| Objection | Response Strategy |
|---|---|
| "Is my resume data safe?" | Clear privacy policy, no third-party sharing, local processing where possible |
| "Will this actually get me a job?" | Position as a tool, not a guarantee — focus on match clarity & better resumes |
| "I already use Naukri/LinkedIn" | Differentiate via skill-gap + auto resume generation, not just job listings |
| "Free tools (Canva, ChatGPT) already do resumes" | Show job-specific match % + ATS scoring as the unique value, not just formatting |

## Key Buying Triggers

- Placement season starting at college
- A friend gets shortlisted using a "match %" demo
- Repeated silent rejections push them to seek a better resume
- College placement cell officially recommends the tool

## MVP Recommendation

**Build First:**
- Resume upload → skill extraction
- Job description match % + missing skills display
- Basic ATS-friendly resume generation

**Do NOT Build Yet:**
- Company-wide job aggregation across many sources (complex, low differentiation early on)
- Paid subscription/billing system
- Mobile app (start with web)
- Advanced AI mock interviews or career coaching

**Success Metrics:**
- Number of resumes analyzed
- Average match % improvement after resume regeneration
- Weekly active users during placement season
- % of users returning for a second job match

## MoSCoW Prioritization

| Priority | Features |
|---|---|
| **Must Have** | Resume upload & parsing, JD match %, missing skills list, ATS resume generation |
| **Should Have** | Email notifications for new matches, basic dashboard of applied jobs |
| **Could Have** | Company-name based job aggregation, skill-improvement resources/links |
| **Won't Have (for now)** | Paid plans, mobile app, AI mock interviews, placement cell B2B dashboard |

## Pricing Hypothesis

| Tier | Price | Includes |
|---|---|---|
| Free | ₹0 | Limited resume scans/month, basic match % |
| Pro (later) | ₹99–₹199/month | Unlimited scans, resume generation, job alerts |
| Campus License (later) | Custom | College-wide access via placement cell tie-up |

*Hypothesis: Most final-year students won't pay individually; B2B2C via college placement cells is the likely long-term revenue path.*

## Top 5 Risks

| # | Risk |
|---|---|
| 1 | No real user validation yet — feature set may not match actual student priorities |
| 2 | Resume parsing/matching accuracy may be unreliable across resume formats |
| 3 | Low willingness to pay among students — monetization unclear |
| 4 | Job-source/scraping dependency (legal/ToS risk if aggregating external job boards) |
| 5 | Crowded market (Naukri, LinkedIn, Internshala, multiple AI resume tools) |

## 30-Day MVP Plan

| Week | Focus |
|---|---|
| 1 | Test prototype internally; fix core resume parsing/matching bugs |
| 2 | Get 20–30 final-year students to test manually; collect feedback |
| 3 | Refine match % accuracy and resume generation quality based on feedback |
| 4 | Soft launch in 1–2 colleges via placement cell or student groups; track usage metrics |

## Founder Action Sheet — Top 10 Next Actions

1. Get 10–15 final-year students to test the existing prototype this week
2. Fix any major bugs in resume parsing/matching found during testing
3. Set up basic analytics (uploads, match %, resume downloads)
4. Reach out to 1 college placement cell for a pilot
5. Create a simple landing page explaining the value clearly
6. Collect testimonials/feedback after first real usage
7. Decide on a v1 scope freeze — stop adding features until validated
8. Set up a WhatsApp/Telegram group for early users for feedback loop
9. Track "match % improvement" as the core value metric
10. Plan a soft launch announcement post for one campus

## Scores (0–100)

| Metric | Score | Reasoning |
|---|---|---|
| Customer Clarity | 75 | Well-defined niche (final-year India students), but personas not yet validated with real users |
| Problem Severity | 80 | Job search fragmentation + ATS rejection is a widely felt, real pain |
| PMF Potential | 55 | Strong concept, but unproven willingness to pay and no user feedback yet |
| MVP Readiness | 70 | Core technical build already exists, ahead of typical pre-validation stage |


