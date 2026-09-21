# CareAtlas NJ: judge-focused demo video script

**Target runtime:** 3:35–3:50. The GIBC V2 requirement is 2–5 minutes, and the video must show the working project and explain the approach in English audio or with accurate English subtitles.

**Goal:** Make the strongest Track 03 case in one clean story: CareAtlas is creative because it connects evidence that normally lives apart, well executed because the full workflow works, potentially impactful because a result can be understood and shared, and polished because every claim remains inspectable.

**Core line:** One map, three questions, and no black box.

Directions marked **Show** are not spoken. Everything marked **Say** is ready to read aloud.

## Before recording

### Prepare the browser

- Record the deployed app at <https://careatlas.lmayzel930.workers.dev>, not a local build.
- Use a clean Chrome window at 1920×1080 or 2560×1440. Set zoom so map labels, buttons and evidence values remain legible in the final 1080p video.
- Hide bookmarks, unrelated tabs, notifications, account menus, credentials and personal information.
- Keep three tabs ready: the live app, the repository [README at the pipeline diagram](../../README.md#how-it-works), and the [successful public CI run](https://github.com/methmoussa/careatlas-nj/actions/runs/35541183296).
- Turn on a visible cursor highlight if available, but avoid click animations that cover text.
- Prioritize clean voice audio. Add reviewed English captions even if the narration is already in English.

### Rehearse this exact route

1. **Potential gaps** → search **Newark City** → **View gap tracts** → open one potential-gap tract → reveal its inputs, reason, rule/source dates and limitations.
2. **Hospitals & community health centers** → keep or reselect **Newark City** → open one grouped marker → reveal an individual listing and source context.
3. **Doctor offices (pilot)** → **Dermatology** → search **Edison** → **View results** → open a clear office listing and **About this listing**.
4. Return to the tract record → **Copy link** → open the copied URL in a clean tab → show **Print brief** or **Download this tract JSON**.
5. Show the README pipeline diagram, then the green public CI run with both Ubuntu and Windows jobs.

Test every interaction immediately before recording. If a print, clipboard or download action is unreliable, omit that action rather than narrating a result the video does not show. Read any result-specific count from the screen; do not memorize changing Newark or Edison counts.

### Optional minimal overlays

Use only short overlays that reinforce what is already on screen:

- Opening: `CareAtlas NJ · GIBC V2 Track 03`
- Scope: `21 counties · 564 municipalities · 2,181 census tracts`
- Closing: `One map · Three questions · No black box`

Do not begin with a slide deck or a long logo animation. The working product should be visible within the first two seconds.

## Timed recording script

### 0:00–0:25 — Hook and promise

**Show:** Begin on the working New Jersey map with the CareAtlas name and the three modes visible. Move directly into **Potential gaps** and begin searching for Newark City. Keep the optional title overlay on screen for no more than two seconds.

**Say:**

> What does healthcare access look like where you live? A map pin cannot answer that—and neither can a score you cannot inspect. I’m Leo, and I built CareAtlas NJ to connect fragmented public evidence across every New Jersey county and municipality. You can see recorded care locations, then open a tract-level screening result with its inputs, source dates and limits. Let me show you Newark.

### 0:25–1:20 — Lead with the differentiator

**Show:** Select **Newark City**, click **View gap tracts**, and choose one potential-gap tract from the list or map. Pause first on the status and plain-language reason. Then reveal the inputs, rule version, source dates and limitations. Move the cursor deliberately; do not scroll while naming a value that is not visible.

**Say:**

> I start with Potential gaps. The purple areas meet a published screening rule: elevated community-health need or social barriers appear alongside reviewed primary-care shortage evidence. I can open one tract and, instead of trusting a color, inspect the exact inputs, classification reason, rule version, source dates and limitations. Missing evidence stays missing; CareAtlas never quietly turns unknown into zero. A potential-gap flag is a planning signal, not a diagnosis or proof that care is unavailable.

### 1:20–1:52 — Recorded facilities, kept separate

**Show:** Switch to **Hospitals & community health centers** while Newark remains the context. Open one grouped marker, then an individual listing. Hold on its recorded name, address, contact or directions link and source information.

**Say:**

> Now I keep the place and switch the question. This layer shows 62 hospitals and 153 HRSA community health centers across New Jersey. Opening a group reveals individual recorded locations with addresses, contact options, directions and source context. These pins help someone discover care locations, but they never create or change the tract screening result.

### 1:52–2:25 — Specialty-office pilot

**Show:** Switch to **Doctor offices (pilot)**, select **Dermatology**, search **Edison**, and choose **View results**. Open a clear result such as Aura Dermatology at Edison, reveal the listed clinicians, then open **About this listing** long enough for its source context to be readable.

**Say:**

> The third view is a clearly labeled doctor-office pilot. I choose Dermatology, search Edison and open the filtered results. Each office expands to the clinicians and specialty records grouped there, with source dates and listing context. The pilot contains 734 CMS-listed locations. It does not claim that an office is open, accepts a particular insurance plan or has appointments.

### 2:25–2:50 — Make the evidence reusable

**Show:** Return to the selected tract. Click **Copy link**, paste it into a clean tab and show that the same official tract reopens. Then show one rehearsed action: **Print brief** or **Download this tract JSON**. Do not wait through a native save dialog on camera.

**Say:**

> A result becomes more useful when it can be checked later. Copy link preserves the official tract identifier and reopens this same record. I can print a readable brief or download the validated record. The explanation, sources and limitations travel with the result instead of being separated from it.

### 2:50–3:18 — Prove the engineering

**Show:** Switch to the repository README already positioned at the pipeline diagram. Trace the flow once with the cursor. Then switch to the successful CI run and hold on the two green Ubuntu and Windows jobs and the test summary. Do not scroll through code.

**Say:**

> Under the interface is a reproducible pipeline joining Census geography, CDC health and vulnerability measures, HRSA shortage evidence, and CMS and HRSA care-location records. It preserves provenance and missing values, applies a versioned rule, and validates all 2,181 tract records before publication. The repository is public, and the same full check passes on both Linux and Windows. I built the project solo with ChatGPT and Codex assistance, which is disclosed in the repository and submission.

### 3:18–3:42 — Close on value, not features

**Show:** Return to the live map with the CareAtlas name, Newark context and three modes visible. Stop moving the cursor. Use the short closing overlay only after the final sentence begins.

**Say:**

> CareAtlas does not claim to prove where care is or is not available. It gives residents and planners a transparent way to ask better questions: start with a place, trace every result to public evidence, and share what you find. Next, I’ll test it with residents and independent public-health and GIS reviewers. That is CareAtlas NJ: one map, three questions, and no black box.

## Teleprompter-only copy

What does healthcare access look like where you live? A map pin cannot answer that—and neither can a score you cannot inspect. I’m Leo, and I built CareAtlas NJ to connect fragmented public evidence across every New Jersey county and municipality. You can see recorded care locations, then open a tract-level screening result with its inputs, source dates and limits. Let me show you Newark.

I start with Potential gaps. The purple areas meet a published screening rule: elevated community-health need or social barriers appear alongside reviewed primary-care shortage evidence. I can open one tract and, instead of trusting a color, inspect the exact inputs, classification reason, rule version, source dates and limitations. Missing evidence stays missing; CareAtlas never quietly turns unknown into zero. A potential-gap flag is a planning signal, not a diagnosis or proof that care is unavailable.

Now I keep the place and switch the question. This layer shows 62 hospitals and 153 HRSA community health centers across New Jersey. Opening a group reveals individual recorded locations with addresses, contact options, directions and source context. These pins help someone discover care locations, but they never create or change the tract screening result.

The third view is a clearly labeled doctor-office pilot. I choose Dermatology, search Edison and open the filtered results. Each office expands to the clinicians and specialty records grouped there, with source dates and listing context. The pilot contains 734 CMS-listed locations. It does not claim that an office is open, accepts a particular insurance plan or has appointments.

A result becomes more useful when it can be checked later. Copy link preserves the official tract identifier and reopens this same record. I can print a readable brief or download the validated record. The explanation, sources and limitations travel with the result instead of being separated from it.

Under the interface is a reproducible pipeline joining Census geography, CDC health and vulnerability measures, HRSA shortage evidence, and CMS and HRSA care-location records. It preserves provenance and missing values, applies a versioned rule, and validates all 2,181 tract records before publication. The repository is public, and the same full check passes on both Linux and Windows. I built the project solo with ChatGPT and Codex assistance, which is disclosed in the repository and submission.

CareAtlas does not claim to prove where care is or is not available. It gives residents and planners a transparent way to ask better questions: start with a place, trace every result to public evidence, and share what you find. Next, I’ll test it with residents and independent public-health and GIS reviewers. That is CareAtlas NJ: one map, three questions, and no black box.

## Editing notes

- Aim for calm narration at roughly 125–135 words per minute. Leave small pauses after the opening question, after the tract result appears and before the final line.
- Cut loading delays, typing mistakes and dead cursor movement, but keep enough continuous interaction to make clear that this is the working deployed app.
- Use simple cuts rather than decorative transitions. Do not speed up the cursor or zoom so aggressively that the interface feels staged.
- Keep background music absent or very low. Clear speech matters more than production effects.
- Normalize voice volume and remove obvious background noise. Do not apply heavy noise reduction that distorts speech.
- Add accurate captions for `CareAtlas`, `HRSA`, `CMS`, `CDC`, `census tract`, `Newark`, `Edison` and `provenance`; automatic captions often miss them.
- Use the project card as the thumbnail, with at most a short subtitle such as `Transparent healthcare-access evidence`.

## Claims to avoid

- Do not say CareAtlas proves that care is available or unavailable, diagnoses a community or ranks providers.
- Do not call the facility or office layers complete directories.
- Do not claim measured resident impact, completed resident testing, clinical validation or independent expert review.
- Do not suggest that facility or office pins affect the tract rule.
- Do not describe optional Gemini text as the system that calculates results; it is disabled in the demonstrated deployment and never creates classifications.
- Do not read unstable Newark or Edison result counts from this script. Use only numbers visibly shown in the recorded interface.

## Upload checklist

- Export at 1080p or better and confirm that evidence text remains readable after upload processing.
- Keep the final cut between 2 and 5 minutes. A target near 3:40 leaves useful safety margin.
- Upload to YouTube, Vimeo or Youku as **public** or **unlisted**, never private.
- Open the hosted URL in a signed-out or incognito window and watch the complete processed video with captions on.
- Confirm that the first frame is intentional, audio starts immediately and no private notification appears.
- Add the verified hosted URL to Devpost only after this check.

Suggested title: **CareAtlas NJ — Transparent Healthcare-Access Evidence | GIBC V2 Demo**

Suggested description:

> CareAtlas NJ turns fragmented Census, CDC, HRSA and CMS evidence into one transparent, explorable New Jersey map. This live demo shows tract-level screening evidence, recorded hospitals and health centers, a clearly labeled doctor-office pilot, shareable briefs and the reproducible public pipeline behind them.
>
> Live app: https://careatlas.lmayzel930.workers.dev
>
> Source: https://github.com/methmoussa/careatlas-nj
>
> GIBC V2: Track 03 — Open (General Technical Invention)
>
> CareAtlas is a screening and planning tool, not medical advice, a diagnosis, a provider ranking or proof that care is available or unavailable.
