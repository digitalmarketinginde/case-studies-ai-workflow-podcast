# 📊 Prompt System: Podcast KPI Analytics
## Collecting, Aggregating & Analyzing Performance Across All Platforms

> **Philosophy:** Collect raw data from each platform weekly.
> Feed screenshots + exports into AI for analysis.
> Make ONE decision per week based on data — not gut feeling.

---

## Platform Analytics Sources

| Platform | Dashboard | Key Metrics Available |
|----------|-----------|----------------------|
| YouTube Studio | studio.youtube.com | Views, Watch time, CTR, Retention, Impressions |
| Spotify for Creators | creators.spotify.com | Plays, Listeners, Consumption hours, Followers |
| Apple Podcasts Connect | podcastsconnect.apple.com | Listeners, Plays, Follows, Engagement score |
| Google Analytics 4 | analytics.google.com | Sessions, Source/medium, Goal completions, Bounce rate |

---

## Part 1 — What to Collect & How Often

### Weekly Collection (every Monday, 15 min total)

    YouTube Studio → Analytics → Overview:
    - Views (last 7 days)
    - Watch time hours (last 7 days)
    - Subscribers gained
    - Top performing episode this week (by views)
    - CTR on latest episode (benchmark: above 4% is good for podcasts)
    - Average view duration on latest episode (benchmark: above 40% retention)

    Spotify for Creators → Home Dashboard:
    - Plays (last 7 days) — NEW metric introduced May 2025
    - Unique listeners (last 7 days)
    - Consumption hours (measures depth of listening, not just clicks)
    - Followers gained

    Apple Podcasts Connect → Analytics → Trends:
    - Listeners (last 7 days)
    - Plays (last 7 days)
    - Average consumption per episode (%)
    - New followers

    Google Analytics 4 → Reports → Acquisition:
    - Sessions from podcast traffic sources
    - Conversion events (email signup / contact form / booking)
    - Top landing pages from podcast listeners

### Monthly Collection (first Monday of month, 30 min)

    YouTube → Advanced Analytics → Export:
    - Export last 30 days as Google Sheet
    - Fields to include: title, views, watch time, CTR, average view duration
    - This CSV becomes the input for the monthly AI analysis prompt

    All platforms:
    - Screenshot the main dashboard overview
    - Note: top 3 episodes by engagement this month
    - Note: one metric that surprised you (up or down)

---

## Part 2 — The Weekly Analytics Snapshot System

### How to collect without special tools

Step 1 — Take screenshots of each platform dashboard:
YouTube Studio / Spotify for Creators / Apple Podcasts Connect / GA4

Step 2 — Fill in this table manually (5 min):

| Metric                    | YouTube  | Spotify  | Apple    | Website  |
|---------------------------|----------|----------|----------|----------|
| Weekly plays / views      | ·        | ·        | ·        | —        |
| New subscribers/followers | ·        | ·        | ·        | —        |
| Watch / listen time       | ·        | ·        | ·        | —        |
| Best episode this week    | ·        | ·        | ·        | —        |
| Traffic to website        | —        | —        | —        | sessions |

· = fill in manually each Monday
— = metric not available on this platform

Step 3 — Feed screenshots + completed table into AI using Prompt 1 below.

---

## Prompt 1 — Weekly Performance Analysis (Screenshots Input)

    You are a podcast analytics strategist analyzing performance data
    for "Ideas Out Loud" (Ідеї вголос) — a Ukrainian-language marketing podcast.

    I am sharing screenshots from: YouTube Studio / Spotify for Creators /
    Apple Podcasts Connect / Google Analytics 4

    Analyze the data and deliver:

    1. PERFORMANCE SUMMARY:
       What happened this week across all platforms?
       Which platform showed the strongest engagement?
       Which showed the weakest?
       State numbers precisely — no vague observations.

    2. EPISODE PERFORMANCE RANKING:
       Which episode performed best this week and why?
       What topic, title format, or length drove the performance?
       What can be replicated in the next episode?

    3. RETENTION SIGNAL:
       YouTube: what does the average view duration % tell us?
       (Below 30% = hook or early content problem)
       (30–50% = normal for long-form podcasts)
       (Above 50% = strong content, optimize title for more reach)
       Spotify/Apple: what does consumption rate tell us?

    4. GROWTH SIGNAL:
       Are subscriber/follower numbers growing, flat, or declining?
       Is organic reach increasing or decreasing?
       What is the ratio of new vs. returning listeners?

    5. ONE PRIORITY ACTION:
       Based on all data, what is the single most important thing to change
       or double down on next week?
       Be specific: a title format, a topic angle, a publishing time,
       a CTA placement, a description structure.

    Context:
    - Publishing cadence: weekly
    - Growth model: 100% organic, SEO + GEO driven
    - Current benchmarks: 32,000+ YouTube views, 2,600+ hours watch time

---

## Prompt 2 — Monthly Deep Analysis (CSV Export Input)

    You are analyzing one month of podcast performance data.

    I am sharing:
    1. YouTube Studio export (CSV) — [ATTACH FILE]
    2. Monthly screenshots from Spotify for Creators
    3. Monthly screenshots from Apple Podcasts Connect
    4. Google Analytics 4 monthly report (acquisition + conversions)

    Deliver a full monthly performance report:

    SECTION 1 — CONTENT PERFORMANCE MATRIX:
    Rank all episodes published this month by:
    - Total views/plays across all platforms
    - Engagement depth (watch time % / consumption %)
    - Subscriber/follower conversion rate
    - CTR on YouTube (if available)

    SECTION 2 — TOPIC & TITLE PATTERN ANALYSIS:
    What topic categories performed best?
    What title formats had highest CTR?
    (Question vs. statement vs. bold claim vs. list format)
    What episode length correlated with best retention?

    SECTION 3 — AUDIENCE BEHAVIOR ANALYSIS:
    Where do most listeners find the podcast?
    (YouTube search / suggested / direct / social referral)
    Which platform has the most loyal listeners?
    (Measured by repeat listens and consumption depth)
    What geographic or demographic patterns appear?

    SECTION 4 — WEBSITE CONVERSION FUNNEL:
    How many podcast listeners reached the website?
    What was the conversion rate to target action?
    (Email signup / contact / booking)
    Which episode drove the most website traffic?

    SECTION 5 — NEXT MONTH CONTENT STRATEGY:
    Based on all data, recommend:
    - Top 3 topic categories to prioritize next month
    - Optimal episode length based on retention data
    - Title format hypothesis to test next month
    - One distribution channel to invest more in

---

## Prompt 3 — Episode Title A/B Test Analysis

    You are analyzing YouTube CTR data to identify winning title patterns
    for a Ukrainian-language marketing podcast.

    I am sharing CTR data for the last [10 / 20] episodes:
    [PASTE TABLE: episode title | views | impressions | CTR%]

    Analyze and deliver:

    1. TITLE PATTERN CLUSTERING:
       Group titles into pattern categories:
       - Question format ("Чому...", "Як...", "Коли...")
       - Bold claim format ("Ця помилка коштує...")
       - Number format ("3 причини...", "80% маркетологів...")
       - Personal story format ("Я зробила...", "Мій клієнт...")
       Which pattern has highest average CTR?

    2. KEYWORD POSITION ANALYSIS:
       Do titles with primary keyword in first 3 words
       outperform titles with keyword later?

    3. EMOTIONAL TRIGGER ANALYSIS:
       Which emotion-triggering words appear in top-performing titles?
       (fear / curiosity / surprise / identity challenge / FOMO)

    4. WINNING TITLE FORMULA:
       Based on the data, define the optimal title formula for this channel.
       Example: "[Emotional trigger word] + [specific number/claim] + [audience identity]"

    5. NEXT TITLE RECOMMENDATION:
       Apply the winning formula to this upcoming episode topic: [TOPIC]
       Generate 3 title options using the data-backed formula.

---

## Prompt 4 — Cross-Platform Audience Behavior Analysis

    You are analyzing audience behavior patterns across YouTube, Spotify,
    and Apple Podcasts for a weekly marketing podcast.

    Data provided:
    - YouTube: watch time, retention curve description, traffic sources
    - Spotify: plays, consumption hours, listener location, age data
    - Apple Podcasts: listeners, plays, average consumption %
    - [PASTE DATA OR ATTACH SCREENSHOTS]

    Analyze:

    1. PLATFORM LOYALTY COMPARISON:
       Which platform has the most loyal, deep-listening audience?
       (Measure: consumption depth — hours per listener per month)
       What does this tell us about where to invest promotion effort?

    2. DISCOVERY PATH ANALYSIS:
       How are new listeners finding the podcast on each platform?
       YouTube: search vs. suggested vs. external
       Spotify: search vs. editorial playlists vs. algorithmic
       Apple: search vs. library

    3. LISTENER JOURNEY MAPPING:
       Is there evidence of cross-platform behavior?
       (YouTube viewers who also subscribe on Spotify?)
       What CTA placement would capture cross-platform migration?

    4. CONTENT FORMAT PREFERENCE:
       Does the YouTube audience prefer shorter or longer episodes?
       Does the Spotify audience listen to completion more than YouTube?
       What format optimization does this suggest?

    5. STRATEGIC RECOMMENDATION:
       Which platform should be the PRIMARY growth focus next quarter?
       Which should be maintained but not prioritized?
       What one change would have the highest cross-platform impact?

---

## Prompt 5 — Website Conversion Attribution Analysis

    You are analyzing Google Analytics 4 data to understand
    how podcast listeners convert to website leads.

    Data provided (GA4 export or screenshots):
    - Traffic sources report (last 30 days)
    - Landing pages report
    - Conversion events report
    - [ATTACH GA4 SCREENSHOTS OR EXPORT]

    Podcast links driving traffic to website:
    YouTube description → [WEBSITE URL]
    Spotify description → [WEBSITE URL]
    Social media posts → [WEBSITE URL]

    Analyze:

    1. PODCAST TRAFFIC ATTRIBUTION:
       How many sessions originated from podcast-related sources?
       (Direct / YouTube / Spotify / social referrals from episode posts)
       What % of total website traffic comes from podcast activity?

    2. CONVERSION FUNNEL PERFORMANCE:
       Of podcast-referred visitors, what % completed the target action?
       [Target action: email signup / contact form / booking / product page]
       Which landing page converts podcast traffic best?

    3. CONTENT-TO-CONVERSION CORRELATION:
       Which episode topics drove the most website visits?
       Is there a pattern between episode topic and visitor intent?
       (Marketing strategy episodes → more consultation bookings?)

    4. CTA OPTIMIZATION RECOMMENDATION:
       Based on conversion data, where should CTAs be placed?
       Which CTA format performs best for this audience?
       What one change to the description or episode outro
       would increase conversion rate?

    5. FUNNEL GAP IDENTIFICATION:
       Where are podcast listeners dropping off before converting?
       What content or page improvement would close the gap?

---

## KPI Dashboard Template

Track these metrics manually every Monday (10 min):

    WEEKLY SNAPSHOT — [DATE]

    YOUTUBE:
    Views (7d): ___
    Watch time hours (7d): ___
    CTR latest episode: ___%
    Avg view duration latest episode: ___%
    New subscribers: ___

    SPOTIFY:
    Plays (7d): ___
    Unique listeners (7d): ___
    Consumption hours (7d): ___
    New followers: ___

    APPLE PODCASTS:
    Listeners (7d): ___
    Plays (7d): ___
    Avg consumption %: ___%
    New followers: ___

    WEBSITE (GA4):
    Sessions from podcast sources: ___
    Conversion events this week: ___
    Best converting episode: ___

    THIS WEEK'S INSIGHT:
    [One sentence — what surprised you about the data]

    THIS WEEK'S DECISION:
    [One change to make next episode based on data]

---

## Recommended Free Tools Stack (2026)

| Tool | Purpose | Cost |
|------|---------|------|
| YouTube Studio | YouTube native analytics | Free |
| Spotify for Creators | Spotify native analytics + Plays metric (May 2025) | Free |
| Apple Podcasts Connect | Apple native analytics | Free |
| Google Analytics 4 | Website conversion tracking | Free |
| OP3 | Cross-platform download tracking, IAB-certified | Free |
| Podgagement | Ratings, reviews, rankings monitor | Free tier |
| Linkfire for Podcasts | Smart link + click attribution across platforms | Free tier |
| TubeBuddy / VidIQ | YouTube title and SEO competitive benchmarks | Free tier |

---

*Part of the Ideas Out Loud AI-powered podcast production system.*
*Listen: https://youtube.com/playlist?list=PLVxka1dXArQIsRwbrPyFnYW8daKYi4boq*
