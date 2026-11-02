# AI Production Toolstack for Faceless Vertical Hebrew Short Videos (late 2026)

Context: a graphic designer with little coding knowledge, making about 3 to 5 short Hebrew videos a week on Rabbi Nachman's teachings in a spiritual, cinematic, emotional style. Research date: 2 Nov 2026.

Method caveat: WebFetch could not reach most hosts in this session (teamday.ai, elevenlabs.io and fialkov.co.il all failed DNS), so official pricing pages could NOT be opened directly. Almost every figure below comes from search-result snippets of third-party roundups from 2026, and those roundups often disagree. Treat every price as "reported, unverified against the vendor page" unless marked otherwise. Exchange rate used: about 3.1 ILS per USD (late Oct 2026: 6 ILS = $1.93 on 29 Oct 2026, so about 3.11) — [exchange-rates.org](https://www.exchange-rates.org/converter/ils-usd/6); 1 USD = 3.05 ILS on 4 Oct 2026 — [longforecast](https://longforecast.com/usd-to-ils).

## 1. Image generation (Midjourney, Flux, Ideogram, Firefly, Nano Banana, GPT Image, Leonardo)

### Takeaway
Midjourney (subscription, from about $10/mo) is still the default for a cinematic, painterly spiritual look. Google's Nano Banana Pro, bundled in Google AI Pro at about $19.99/mo with Veo/Flow, is the strongest value pick because one subscription covers both images and video. Adobe Firefly is the most commercially safe choice. Flux and Ideogram are mostly per-image API tools, which suit a designer less well.

### Cited Findings
- Midjourney plans are reported as Basic $10, Standard $30, Pro $60 and Mega $120 per month — [miniloop.ai / aiweekly roundup](https://www.miniloop.ai/blog/best-ai-image-generators-2026); [aiweekly.co](https://aiweekly.co/learning-ai/ai-applications/best-ai-image-generators)
- Midjourney commercial use is reported as allowed on every paid tier, but companies with over $1M a year in revenue need Pro or Mega — [stork.ai](https://www.stork.ai/blog/best-ai-image-generators-2026)
- Midjourney version status is inconsistent across sources: some describe V7 as current, while June 2026 guides cover V8.1/V8.2 and "Omni Reference" (character/object consistency). Omni-reference renders reportedly cost about 2x the GPU time of a standard job, and Midjourney video about 8x an image. Official pricing was reportedly last verified in May 2026 — [blakecrosley.com guide](https://blakecrosley.com/en/guides/midjourney); [aivideobootcamp](https://aivideobootcamp.com/blog/midjourney-complete-guide-2026/); [theneuron.ai](https://www.theneuron.ai/tools/midjourney/)
- Nano Banana (Google) API price is about $0.0336 per 1K image for Nano Banana 2.1 ($0.0168 batch) in one source, versus $0.067 per image for Nano Banana 2 in another. Google reportedly does not claim ownership of outputs — [teamday.ai via search](https://www.teamday.ai/blog/best-ai-image-models-2026); [devtoollab](https://devtoollab.com/blog/best-ai-image-generators)
- Nano Banana Pro (1K/2K/4K output) requires a paid Google AI plan (Plus or Pro) — [eesel.ai](https://www.eesel.ai/blog/nano-banana-pro-pricing); [laozhang blog](https://blog.laozhang.ai/en/posts/nano-banana-2-subscription-price)
- FLUX.2 [pro] is reported from $0.03 per image, or from $0.014 per megapixel. FLUX.2 [dev] weights are non-commercial — [datanorth.ai](https://datanorth.ai/blog/top-10-best-ai-image-generation-tools-2026); [frankx.ai](https://www.frankx.ai/blog/best-ai-image-generators-2026)
- Ideogram API is reported at $0.03 (Turbo), $0.06 (Default) or $0.10 (Quality) per image. Free-tier images are public — [autokeyworder](https://autokeyworder.com/blog/best-ai-image-generators-compared/); [stork.ai](https://www.stork.ai/blog/best-ai-image-generators-2026)
- Adobe Firefly is recommended as the safest choice for commercial work, and Adobe markets its outputs as commercially safe — [miniloop.ai](https://www.miniloop.ai/blog/best-ai-image-generators-2026)
- The Sept to Nov 2026 rankings name GPT Image 2 / 2.5, Nano Banana Pro / 2, Midjourney and FLUX as the top tier — [buildmvpfast](https://www.buildmvpfast.com/articles/best-llms-2026-guide/image-generation-ai); [devtoollab](https://devtoollab.com/blog/best-ai-image-generators)

### Inferences
- For Rabbi Nachman content (forests, a lone figure at dawn, candlelight, Breslov-style hitbodedut scenes), Midjourney's aesthetic strength plus Omni Reference fits a designer's eye. Nano Banana Pro is better at prompt-precise edits and keeping a consistent "character" across shots through reference images, and it comes in the same Google bundle as Veo.
- Text rendering in images matters little here, because Hebrew text should be added in the editor rather than generated. AI image models are unreliable with Hebrew letters (general knowledge, not verified in this search).
- Faceless style lowers the character-consistency burden: shots from behind, hands, silhouettes and landscapes avoid face drift.

### Gaps
- Current Adobe Firefly plan prices (Firefly Standard/Pro) and Leonardo plan prices were not found in this session.
- No source compared these models specifically on "spiritual/cinematic" imagery. That judgment is inference.
- GPT Image consumer pricing (via ChatGPT Plus) was not verified.

## 2. Image-to-video / text-to-video (Kling, Runway, Veo, Luma, Hailuo, Pika, Sora, Higgsfield)

### Takeaway
Kling (3.0 / 4.0) gives the best quality-per-dollar for image-to-video at a reported $0.08 to $0.13 per second. Google Veo 3.1 is the quality leader and includes native audio, but costs a reported $0.40/s on the API, or about $20/mo bundled in Google AI Pro with limited Flow credits. Higgsfield is an aggregator that resells Kling, Veo and others with camera-move presets. Sora's consumer app reportedly shut down in April 2026.

### Cited Findings
- Veo 3.1 Standard costs about $0.40/s with audio. Veo 3.1 Lite costs about $0.05/s (silent, or 720p with audio, depending on source) — [rangy.ai](https://rangy.ai/blog/ai-video-generators-compared-2026/); [teamday.ai](https://www.teamday.ai/blog/best-ai-video-models-2026); [fluxnote](https://fluxnote.io/guides/ai-video-model-pricing-comparison-2026)
- Kling 3.0 costs about $0.084/s silent and $0.126/s with audio at 720p, rising to $0.42/s at 4K. Older guides cite $0.07/s — [teamday.ai](https://www.teamday.ai/blog/best-ai-video-models-2026); [movieflow.ai](https://movieflow.ai/compare/ai-video-pricing)
- Runway Gen-4.5 costs about $0.12/s (12 credits/s at $0.01/credit), versus about $0.25/s (25 credits/s) per HeyGen. The sources conflict — [teamday.ai](https://www.teamday.ai/blog/best-ai-video-models-2026); [heygen.com](https://www.heygen.com/blog/ai-video-generator-pricing)
- Hailuo 2.3 Fast costs about $0.032/s at 768p (billed per clip), and is described as "legacy" by one source — [movieflow.ai](https://movieflow.ai/compare/ai-video-pricing)
- The Sora 2 consumer app reportedly shut down in April 2026 — [crazyrouter May 2026](https://crazyrouter.com/en/blog/ai-video-generation-api-pricing-may-2026-comparison)
- Kling direct subscriptions are reported as Standard $10, Pro $37, Premier $92 and Ultra $180 per month, plus a free tier with daily credits (66/day per another source, which also gives a $6.99 entry). Credits mostly expire each cycle, and rollover claims conflict — [higgsfield.ai blog](https://higgsfield.ai/blog/higgsfield-vs-kling-2026); [layer3labs](https://www.layer3labs.io/comparisons/higgsfield-ai-vs-kling)
- Higgsfield (late Oct 2026) is reported as Starter $19/mo (270 credits), Plus $59/mo or $47/mo annual (1,200 credits), and Ultra about $129. Other sources give conflicting figures ($15/$39/$99, or Basic $9/Pro $23/Max $59) — [heygen.com Higgsfield pricing](https://www.heygen.com/blog/higgsfield-pricing); [wireflow.ai](https://www.wireflow.ai/blog/higgsfield-ai-pricing); [fluxnote](https://fluxnote.io/guides/higgsfield-ai-questions-answered)
- On Higgsfield, Kling 3.0 costs about 7 credits per 5s clip at 720p. Kling 4.0 costs 25 credits per 5s at 720p and 37.5 at 1080p. Plus and Ultra periodically include 7-day credit-free Kling windows — [higgsfield.ai Kling 4.0](https://higgsfield.ai/blog/kling-4-0-on-higgsfield)
- Google AI Pro costs about $19.99/mo with about 1,000 Flow credits/mo (one source says 2,000). One 8s Veo 3.1 Fast video with audio costs 20 Flow credits (10 on Ultra), and AI Ultra is listed at about $100. Credits expire monthly — [mindstudio](https://www.mindstudio.ai/blog/google-flow-pricing-credits-tiers-explained); [diyai.io](https://diyai.io/ai-tools/video-generation/google-veo-pricing/); [labs.google pricing](https://labs.google/fx/tools/video-fx/pricing)

### Inferences
- A 30 to 60s short built from about 6 to 10 clips of 5s each needs about 30 to 50s of final footage. With 2 to 3x rerolls, that is about 100 to 150 generated seconds per video. At Kling 720p/1080p rates of about $0.08 to $0.15/s, that comes to about $10 to $20 per video. At 4 videos/week, that is about $160 to $320/mo of raw generation at API rates. Subscription credits (Kling Pro $37, Higgsfield Plus $59) are usually cheaper per second than API. This is estimated, not verified.
- Google AI Pro's 1,000 credits divided by 20 credits per 8s Veo Fast clip gives about 50 clips, or about 400s per month, which is enough for about 3 to 4 videos a week if rerolls are kept low. This is an inference from the reported figures.
- Native-audio features (Veo, Kling audio) matter little, since the Hebrew VO and music are added separately. Silent generation is cheaper.

### Gaps
- Luma (Ray) and Pika current plan prices were not retrieved.
- Max clip lengths per model (typically 5 to 10s per generation in 2025) were not verified for the late-2026 versions.
- No head-to-head test on slow, contemplative, "spiritual" camera motion was found.

## 3. Hebrew voiceover / TTS and voice cloning

### Takeaway
ElevenLabs v3 is the consensus best commercial Hebrew TTS in Israeli sources. Its Starter plan is $5 to $6/mo for 75k v3 characters, and Creator ($22) unlocks Professional Voice Cloning (PVC), based on general knowledge. Google Gemini TTS reportedly matches it on Hebrew error rate and is free in AI Studio. Azure Hebrew neural voices (2 he-IL voices) are cheap at about $15 per 1M characters but less expressive. Expect stress (hat'ama) mistakes that need nikud or phonetic respelling.

### Cited Findings
- Hebrew-language guides call ElevenLabs the 2026 industry standard for quality Hebrew AI voiceover, and note that OpenAI's Hebrew was mediocre as of late 2025 — [shivuknet.co.il](https://shivuknet.co.il/blog/hebrew-ai-voiceover/); [aicenter.co.il](https://aicenter.co.il/article/elevenlabs-voice-guide)
- Eleven v3 includes Hebrew among 70+ languages. Multilingual v2 (29 languages) does NOT include Hebrew, so use v3 — [tzedek.me](https://tzedek.me/blog/elevenlabs-guide); [aicenter.co.il](https://aicenter.co.il/article/elevenlabs-voice-guide)
- One Hebrew guide rates ElevenLabs Hebrew support as "good, not excellent". An Israeli voiceover-studio article warns output can be accurate in stress yet still sound "cold", and is titled "what already works in ElevenLabs and what doesn't yet" — [masha-bar.co.il](https://masha-bar.co.il/tools/elevenlabs/); [fialkov.co.il](https://www.fialkov.co.il/ai/hebrew-ai-voiceover/) (page could not be fetched; snippet only)
- Resemble AI (a competitor, so not neutral) measured about 4% errors for both Gemini TTS and ElevenLabs v3 in Hebrew, with Gemini free in Google AI Studio — [shivuknet.co.il summary](https://shivuknet.co.il/blog/hebrew-ai-voiceover/)
- ElevenLabs plans are Starter $6 (or $5), Creator $22, Pro $99 and Scale $299 per month. Starter includes 75,000 v3/Multilingual characters. API pricing is $0.08 per 1k characters (v3), as checked in early Oct 2026 — [cartesia.ai](https://www.cartesia.ai/learn/elevenlabs-pricing); [bigvu.tv](https://bigvu.tv/blog/elevenlabs-pricing-2026-plan-worth/); [benchlm.ai](https://benchlm.ai/elevenlabs/pricing)
- One source mentions an ElevenLabs v4 model (90+ languages) with a promotion that ended 12 Oct 2026 — [techpilot / search summary](https://techpilot.ai/tools/elevenlabs/)
- Azure Neural TTS costs about $15 per 1M characters (standard) and $22 to $30 per 1M (HD). Custom Neural Voice costs $24 per 1M plus training fees, and the free tier is 0.5M characters/mo (sources conflict) — [beri.net](https://www.beri.net/article/elevenlabs-vs-cartesia-vs-azure-tts-latency-pricing-voice-cloning-2026); [aiindigo](https://aiindigo.com/blog/microsoft-azure-neural-tts-a-practical-review-for-2026)
- JSON2Video lists two Hebrew (he-IL) Azure voices — [json2video Hebrew](https://json2video.com/ai-voices/languages/hebrew/)
- The open-source Hebrew option is Phonikud (G2P, Interspeech 2026, uses Dicta's nikud model, with a phonikud-tts library). It needs Python, so it does not suit a non-coder — [pypi phonikud](https://pypi.org/project/phonikud/); [arXiv 2506.12311](https://arxiv.org/abs/2506.12311)

### Inferences
- A 45s short is about 90 to 110 Hebrew words, or about 600 to 700 characters. 20 videos/mo with retakes is about 20 to 30k characters, which fits ElevenLabs Starter ($5 to $6). Upgrade to Creator ($22) for professional cloning of one's own voice and more headroom.
- For a warm male narrator: browse the ElevenLabs Voice Library filtered to Hebrew/male/"narration", or clone one's own voice. A recording of one's own voice reading Breslov texts gives the most authentic result and avoids voice-rights issues.
- Rabbi Nachman quotes contain Aramaic and Hasidic terms (hitbodedut, tikkun, Likutei Moharan). Expect mispronunciation, and fix it by adding nikud on problem words (for example with Dicta Nakdan) or respelling phonetically.
- Legal: cloning one's own voice is fine. Never clone a rabbi or another person without written consent. TikTok, YouTube and Meta require labeling realistic AI-generated or synthetic content (platform policies, general knowledge, not verified in this session).

### Gaps
- Exact ElevenLabs Creator/PVC feature split for late 2026 was not verified (elevenlabs.io could not be fetched).
- No Israeli commercial Hebrew TTS startup with public pricing was found in this session.
- No current Google Cloud TTS Hebrew price was found.

## 4. Editing and Hebrew captions (RTL)

### Takeaway
No independent benchmark of Hebrew auto-caption accuracy exists in what was found. CapCut is the practical default editor, but its Hebrew auto-caption support is not confirmed by official documentation, and RTL rendering bugs reported for Arabic plausibly affect Hebrew. Submagic and VEED explicitly advertise Hebrew. The Israeli plugin Kaps handles Hebrew captions inside Premiere. Plan to proofread every caption.

### Cited Findings
- CapCut auto-caption language counts conflict (47 vs 55+ languages), and one Sept 2026 guide says auto captions are Pro-only while others say free — [typito](https://typito.com/blog/capcut-auto-captions-add-subtitles-in-capcut/); [caption-x](https://caption-x.com/blog/how-to-add-captions-capcut); [CapCut help](https://www.capcut.com/help/how-to-recognise-subtitles)
- CapCut RTL rendering for Arabic still depends on font and direction choice, and the reversed-word-order issues "have not fully disappeared". Hebrew issues are inferred, not confirmed — [arwriterai](https://arwriterai.com/en/blog/how-to-add-arabic-subtitles-capcut-2026/)
- CapCut's Hebrew-language pages claim "near-perfect" AI captions, while its own tutorials say auto captions sometimes need fixes — [capcut.com he-il](https://www.capcut.com/he-il/resource/how-to-add-subtitle-in-capcut); [msl.org.il CapCut guide](https://msl.org.il/)
- Kaps (Israeli Hebrew captions plugin for Premiere) claims up to 98% accuracy with good recordings and 85% with fair audio. This is a vendor claim — [kaps.co.il](https://kaps.co.il/)
- Submagic has a dedicated Hebrew subtitles page and claims "as well as a native Hebrew speaker" quality, plus 99% accuracy across 123 languages (not broken out by language) — [submagic Hebrew](https://submagic.co/auto-subtitle-generator/hebrew-subtitles)
- VEED offers Hebrew speech-to-text and Hebrew subtitle generation (vendor claim of accuracy, no error rate given) — [VEED Hebrew STT](https://VEED.IO/tools/transcription/speech-to-text-hebrew)
- Captions.app Hebrew support is unconfirmed — [dupple review](https://dupple.com/learn/best-ai-subtitle-generators)
- Premiere Pro auto-captions are in the paid version and require internet. Hebrew support in Premiere's built-in tool was not confirmed — [capcut.com he-il Premiere guide](https://www.capcut.com/he-il/resource/premiere-pro-subtitles)

### Inferences
- Because the voiceover is generated from the user's own script, captions can be made from the script text itself (paste the script, then auto-align or import SRT) rather than relying on speech recognition. That removes most accuracy concerns. Keep the nikud-free version of the script for on-screen captions, and use the nikud version only for the TTS input.
- Hebrew fonts: use a proper Hebrew font (for example Assistant, Heebo, Rubik or Frank Ruhl Libre from Google Fonts, or a licensed Hebrew display font) and check punctuation placement, since RTL punctuation jumping to the wrong end is a common bug.
- A designer may prefer Premiere plus Kaps, or DaVinci Resolve (free), for typographic control. CapCut is fastest for animated word-by-word captions.

### Gaps
- CapCut commercial-use terms for its music/effects library and current CapCut Pro price were not retrieved.
- Canva Hebrew caption support and DaVinci Resolve Hebrew transcription were not verified.
- No data was found on nikud rendering in caption tools.

## 5. Music (royalty-free libraries, Suno/Udio, niggun-style)

### Takeaway
Epidemic Sound Creator (about $9.99/mo annual, about $17.99 monthly) or Artlist Music (about $199/yr) give safe social-media licensing. Suno Pro/Premier (about $8 to $10 and $24 to $30 per month) can generate niggun-style wordless melodies with commercial rights, but its ownership wording changed after the Warner deal and UMG/Sony litigation continues.

### Cited Findings
- Epidemic Sound Creator costs $9.99/mo billed annually ($119.88/yr) or $17.99 monthly, with monthly plans and no long-term contracts — [creatorstackclub](https://www.creatorstackclub.com/software/epidemic-sound); [epidemicsound.com/pricing](https://epidemicsound.com/pricing)
- Artlist's cheapest plan is reported at $9.99/mo (annual) or $14.99 monthly. Another source says it is annual-only, at about $199/yr for Music — [photutorial](https://photutorial.com/artlist-pricing); [soundstripe](https://www.soundstripe.com/blogs/artlist-alternatives)
- Suno free-tier songs are non-commercial. Pro and Premier give commercial rights to songs made while subscribed, and those rights are not retroactive to earlier free songs — [dubspot](https://blog.dubspot.com/ai-music-licensing-explained-2026); [toskyrecords](https://toskyrecords.com/2026/06/09/the-working-artists-guide-to-suno-paid-tiers-rights-distribution-monetization-in-2026/)
- After the Warner settlement (25 Nov 2025) and the launch of licensed models (Sept 2026), Suno reportedly retains authorship and grants a perpetual commercial license. Another source says the ToS uses assignment language. The sources conflict — [musicinafrica](https://www.musicinafrica.net/magazine/suno-adjusts-ai-music-ownership-terms-after-warner-music-partnership); [propakistani](https://propakistani.pk/2026/09/10/suno-launches-licensed-ai-music-models-after-warner-copyright-settlement/); [terms.law](https://terms.law/ai-output-rights/suno/)
- UMG and Sony are still litigating against Suno, and talks reportedly broke down in April 2026 — [tech-insider](https://tech-insider.org/suno-v6-warner-bmg-licensing-deal-2026/)
- Suno Pro is reported at about $8 (annual) to $10 monthly, and Premier at $24 to $30 — [hookgenius](https://hookgenius.app/learn/suno-legal-guide/)
- The US Copyright Office generally does not register purely AI-generated audio — [dubspot](https://blog.dubspot.com/ai-music-licensing-explained-2026)

### Inferences
- For niggun or Breslov flavor, Suno prompts like "slow wordless Hasidic niggun, solo violin, clarinet, soft male humming, ambient" are likely effective, though this was not tested. Avoid imitating known Breslov niggunim (for example "Na Nach" melodies) note-for-note, because of the copyright on specific recordings and arrangements.
- Platform libraries (TikTok/Instagram trending sounds) are licensed for in-app use only and are risky for YouTube or reuse.

### Gaps
- No dedicated Jewish or niggun royalty-free library with licensing terms was found in this session.
- Udio's 2026 licensing status was not retrieved.

## 6. All-in-one faceless video tools and automation

### Takeaway
All-in-one tools (InVideo, Pictory and similar) are weak for Hebrew. InVideo lists Hebrew for voice but NOT for subtitles. Automation pipelines (n8n/Make with ElevenLabs plus image/video plus Shotstack/Creatomate/JSON2Video) are possible but require technical setup that is beyond a low-code designer at the start.

### Cited Findings
- InVideo's help center lists Hebrew among additional supported languages, but also lists Hebrew among languages where subtitles are not yet supported — [help.invideo.io](https://help.invideo.io/en/articles/9387980)
- Published n8n workflows chain Gemini, ElevenLabs, Leonardo and Shotstack for automated faceless videos — [growwstacks](https://growwstacks.com/workflows/create-faceless-videos-with-gemini-elevenlabs-leonardo-ai-and-shotstack)
- JSON2Video has Hebrew Azure voices and an n8n integration — [json2video](https://json2video.com/ai-voices/languages/hebrew/israel/)
- Kapwing offers Hebrew TTS in-browser — [kapwing](https://www.kapwing.com/tools/text-to-speech/Hebrew)

### Inferences
- The recommended approach is semi-manual: an LLM (ChatGPT/Claude/Gemini) writes the script and shot list from a Likutei Moharan passage, and the human generates assets and edits. Automate later, once the format stabilizes.
- Pictory Hebrew support was not verified. Assume it is poor.

### Gaps
- Pictory, Fliki and Make Hebrew capabilities and prices were not retrieved.

## 7. Recommended stacks (lean / mid / premium) with monthly cost and time per video

### Takeaway
The lean stack costs about $30/mo (about 95 ILS), the mid stack about $90 to $110/mo (about 280 to 340 ILS), and the premium stack about $250 to $300/mo (about 780 to 930 ILS). Estimated production time is about 60 to 120 minutes per video once a template exists. All figures are inferences built from the reported prices above, at 3.1 ILS/USD.

### Cited Findings
(Prices are those cited in sections 1 to 5. The stack composition is inference.)

### Inferences
**Lean (about $30/mo, about 95 ILS):**
- Google AI Pro $19.99 (Nano Banana Pro images plus about 50 Veo 3.1 Fast clips/mo via Flow)
- Plus the Kling free daily credits for extra image-to-video
- ElevenLabs Starter $6 (Hebrew v3, about 75k characters)
- CapCut free/desktop, with captions from the script, or DaVinci Resolve free
- Music: Suno Pro about $10 (commercial) or YouTube Audio Library (free)
- Total about $36, or about 110 ILS. Use Gemini TTS free as a backup voice.

**Mid (about $100/mo, about 310 ILS):**
- Midjourney Standard $30 for the cinematic look
- Kling Pro $37 (or Google AI Pro $20 plus Kling Standard $10)
- ElevenLabs Creator $22 (professional clone of one's own voice)
- Epidemic Sound Creator about $10 to $18
- CapCut Pro (price not verified) or Submagic for Hebrew captions
- Total about $100 to $120, or about 310 to 370 ILS.

**Premium (about $250 to $300/mo, about 780 to 930 ILS):**
- Midjourney Pro $60 (stealth mode, plus video)
- Higgsfield Plus $59 or Ultra about $129 (Kling 4.0, Veo and others in one place), and/or Google AI Ultra about $100
- ElevenLabs Pro $99 or Creator $22
- Artlist (music plus SFX, about $17/mo annualized) or Epidemic
- Adobe Creative Cloud with Premiere plus the Kaps Hebrew plugin (prices not verified, typically about $55 to $70/mo for Premiere or the full CC suite)
- Total about $250 to $330.

**Estimated time per 30 to 60s video (inference, not sourced):**
- Script and shot list with an LLM, plus nikud fixes: 15 to 20 min
- 6 to 10 images: 15 to 25 min
- Image-to-video with rerolls: 20 to 40 min, mostly waiting on render queues
- Voiceover and retakes: 10 min
- Edit, captions, music and export: 20 to 30 min
- Total about 1.5 to 2 hours at the start, falling to about 60 to 75 min with templates (CapCut caption style preset, prompt library, reusable intro and outro)
- 4 videos/week is about 4 to 8 hours/week

### Gaps
- None of the stack prices were verified against official pricing pages in this session (fetch blocked). The user should check midjourney.com/pricing, klingai.com, one.google.com, elevenlabs.io/pricing, epidemicsound.com/pricing and capcut.com before subscribing.
- ILS figures exclude VAT (17% to 18%), which Israeli users may be charged on digital services. The VAT rate was not verified.
- Production-time estimates are not from a source. No Israeli creator time studies were found.
