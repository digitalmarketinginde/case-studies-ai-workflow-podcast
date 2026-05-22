# 🤖 AI Tools Stack
## Every Tool in the Ideas Out Loud Production System

> **Principle:** Every tool was chosen for a specific reason — not because it was popular,
> but because it solved a real production problem better than any alternative.
> This stack produces broadcast-quality podcast content in under 2 hours per episode.

---

## 🎙️ Audio Production Tools

### 1. Gling AI — Audio & Video Cleanup
**Role in workflow:** Step 1 after recording. Removes pauses, filler words, bad takes.
**Website:** https://gling.ai

**Why Gling and not alternatives:**
Gling AI is the only audio/video editing tool that correctly recognizes and processes
Ukrainian language speech. Every alternative tested (Descript, Riverside, Cleanfeed)
either failed to transcribe Ukrainian accurately or missed Ukrainian-specific filler words
(е-е, ну, значить, тобто). Gling handles all of them reliably.

| Feature | Details |
|---------|---------|
| Ukrainian language support | ✅ Best in class — no competitor matches this |
| Auto-removes pauses | ✅ Silence detection + removal |
| Auto-removes filler words | ✅ Ukrainian filler word model |
| Cuts bad starts + repetitions | ✅ Automated |
| Auto-generates transcript | ✅ Used as SEO input for Prompt System 03 |
| Free trial | ✅ 1 full video up to 1 hour — enough to test with a real episode |
| Paid plan | $15/month (up to 10 hours footage) or $100/year |
| Creator Program | Free credits if you mention Gling in YouTube pinned comment |

**Verdict:** Non-negotiable for Ukrainian-language podcast production.
No alternative exists that performs comparably on Ukrainian speech.

---

### 2. Adobe Podcast Enhance — Broadcast Audio Quality
**Role in workflow:** Step 2 after Gling. Transforms cleaned audio into studio-quality sound.
**Website:** https://podcast.adobe.com/enhance

**Why Adobe Podcast:**
One-click AI enhancement that removes residual noise, room reverb, and mic imperfections.
The free tier is fully functional for weekly podcast production with daily limits.

| Feature | Free Plan | Premium Plan |
|---------|-----------|-------------|
| Audio enhancement | ✅ | ✅ |
| Video enhancement | ❌ | ✅ |
| Max file duration | 30 min | 2 hours |
| Daily processing limit | 1 hour/day | 4 hours/day |
| Max file size | 500 MB | 1 GB |
| Cost | Free | Paid |

**Workflow tip:** For episodes under 30 minutes — free plan covers everything.
For 40–60 minute episodes — split the file, process in two parts on free plan,
or upgrade to Premium for uninterrupted workflow.

**Verdict:** Best free AI audio enhancer available. Zero learning curve.
Upload → Enhance → Download. Done in 2 minutes.

---

### 3. Podcastle AI — Alternative Audio Enhancement
**Role in workflow:** Backup to Adobe Podcast. Used when custom audio adjustments needed.
**Website:** https://podcastle.ai

**Why Podcastle as alternative:**
When specific audio corrections are needed — equalization, noise gate adjustment,
voice clarity tuning — Podcastle's Magic Dust feature gives manual control
that Adobe Podcast's one-click model does not offer.

| Feature | Details |
|---------|---------|
| Magic Dust (AI noise reduction) | ✅ Manual strength control |
| Remote recording | ✅ Captures local audio for each participant |
| AI transcription | ✅ |
| Text-to-speech | ✅ Voice cloning available |
| Free tier | ✅ Basic recording + editing |
| Paid plans | From $11.99/month |

**When to use Podcastle instead of Adobe:**
- Recording environment has unusual acoustic problems
- Need to adjust enhancement strength manually
- Recording remote guests with separate audio tracks
- Need more control than one-click processing allows

---

## ✍️ Script & Content AI Tools

### 4. ChatGPT (GPT-4o) — Script Engineering & Content Generation
**Role in workflow:** Primary AI for Prompt Systems 01, 03, 04, 05
**Website:** https://chatgpt.com

Used for: topic validation, script structuring from raw voice transcripts,
SEO title generation, platform-native content creation, analytics interpretation.
See full prompt library in `workflow/01-script-engineering.md`

---

### 5. Claude (Anthropic) — Long-Form Analysis & Editing
**Role in workflow:** Long transcript analysis, deep content editing passes
**Website:** https://claude.ai

**Why Claude for long transcripts:**
Claude handles 200,000+ token context windows — meaning a full 60-minute podcast
transcript can be processed in a single prompt without chunking.
Preferred for Prompt 4 (Anti-AI-Slop Refinement) where the entire script
must be reviewed simultaneously.

---

### 6. Perplexity AI — Real-Time Research & GEO Optimization
**Role in workflow:** Topic research, trend validation, competitive analysis
**Website:** https://perplexity.ai

**Why Perplexity for research:**
Provides cited, real-time search results rather than training data.
Used before recording to validate that a topic has current search demand
and to identify what existing content misses.
Also used to test GEO optimization: if Perplexity surfaces your episode
as a cited source for a topic query — the GEO strategy is working.

---

## 🎨 Visual Production Tools

### 7. Figma — Thumbnail & Brand Asset System
**Role in workflow:** Master thumbnail template. One template per show season.
**Website:** https://figma.com

**The system:** One master Figma file with locked brand layers.
Only the episode title and number change per episode.
Thumbnail production time per episode: under 2 minutes.

**Community resources — free templates:**

Podcast thumbnail templates:
https://www.figma.com/community/search?resource_type=files&q=podcast+thumbnail

YouTube thumbnail templates:
https://www.figma.com/community/youtube-templates/thumbnails

**Recommended search terms in Figma Community:**
- "podcast thumbnail"
- "YouTube thumbnail minimal"
- "podcast cover art"
- "interview thumbnail"

---

### 8. CapCut — Video Assembly & Export
**Role in workflow:** Final video production. Audio + thumbnail + waveform animation → MP4.
**Website:** https://capcut.com

| Feature | Details |
|---------|---------|
| 16:9 horizontal templates | ✅ YouTube-optimized |
| Waveform animation stickers | ✅ Creates visual engagement for static podcast format |
| Auto-captions | ✅ AI-generated subtitles |
| Export quality | Up to 4K |
| Cost | Free tier covers all podcast production needs |

---

## 📡 Distribution Platforms

### 9. YouTube
**Role:** Primary video platform + discovery engine + podcast host
**Dashboard:** https://studio.youtube.com
**Channel playlist:** https://youtube.com/playlist?list=PLVxka1dXArQIsRwbrPyFnYW8daKYi4boq

**Why YouTube is the primary platform:**
YouTube is the world's second-largest search engine and the fastest-growing
podcast platform as of 2025–2026. Episodes optimized with the SEO+GEO system
continue accumulating views for months after publication.
AI dubbing feature enables automatic multilingual versions from a single recording.

---

### 10. Spotify for Creators
**Role:** Audio-first distribution + listener analytics
**Dashboard:** https://creators.spotify.com
**Podcast page:** https://open.spotify.com/show/2IhdoB9HLaeKax50vwKvBo

**Key feature in 2025:** Spotify introduced the **Plays** metric (May 2025) —
now measures actual listening events, not just download requests.
More accurate than downloads for measuring real audience engagement.

---

### 11. Apple Podcasts
**Role:** Premium audio-first audience distribution
**Dashboard:** https://podcastsconnect.apple.com
**Podcast page:** https://podcasts.apple.com/us/podcast/id1894859462

**Why Apple Podcasts matters:**
Apple Podcasts listeners have the highest consumption rates —
they listen to more minutes per episode than any other platform's average audience.
Quality over quantity signal: if your episode scores well on Apple, the content is strong.

---

## 🧰 Supporting Analytics Tools

| Tool | Purpose | Link | Cost |
|------|---------|------|------|
| Google Analytics 4 | Website conversion from podcast traffic | analytics.google.com | Free |
| OP3 | Cross-platform download tracking, IAB-certified | op3.dev | Free |
| TubeBuddy | YouTube SEO, title A/B testing | tubebuddy.com | Free tier |
| Podgagement | Ratings, reviews, rankings monitor | podgagement.com | Free tier |
| Linkfire | Smart link + click attribution | linkfire.com | Free tier |

---

## Total Stack Cost (Free Tier)

| Scenario | Monthly cost |
|----------|-------------|
| Full production on free tiers | $0 |
| Gling AI paid (10h/month footage) | $15/month |
| Adobe Podcast Premium (if 60min episodes) | Paid tier |
| **Recommended starting setup** | **$0–$15/month** |

---

## The Core Principle

> AI tools in this stack do not replace expertise — they remove friction
> so that the expert can focus on what only a human can do:
> having a genuine opinion, sharing real experience, and connecting
> with an audience that came for the human perspective, not the production quality.

---

*Part of the Ideas Out Loud AI-powered podcast production system.*
*Listen: https://youtube.com/playlist?list=PLVxka1dXArQIsRwbrPyFnYW8daKYi4boq*
