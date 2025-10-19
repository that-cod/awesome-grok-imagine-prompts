A growing, community curated collection of 200+ high quality prompts for Grok Imagine, xAI's cutting edge image and video generator. Sourced from X creators, Reddit threads (r/grok, r/GrokAI), and web guides, this repo emphasizes fresh, non redundant examples tested for Grok's Flux based models. We've expanded to 12 genres, including new ones like Fantasy, Anime & Cyberpunk, and Action Videos, with battle tested prompts for static images, 6-10s clips, and edits.Fork, star, and contribute your prompts could inspire the next viral X video!

What is Grok Imagine?
Grok Imagine, powered by xAI's Grok 4 and Flux, turns text (or images) into photorealistic images, surreal art, or short videos with audio. Access it free (limited quotas) on x.com/grok, grok.com, or apps; SuperGrok/Premium+ unlocks unlimited. Strengths: Speed (seconds per gen), consistency in styles, and natural motion in videos. Limitations: 6-15s clips max, occasional physics glitches in complex actions, NSFW moderation (use "spicy" mode cautiously).Core Principles of Prompting Grok Imagine (Detailed Guide)Master Grok with the Expanded Five Pillars framework, refined from community tests (X threads, Reddit r/grok). Prompts work best at 50-200 words concise yet vivid.

1. Subject & Character (Foundation: 30% Weight)Be specific: "A seductive demon girl with crimson horns, obsidian wings, and emerald eyes" > "A demon."
Layers: Appearance (hair, outfit), emotion (sultry smirk), pose (hip sway).
Tip: Start prompts here—Grok prioritizes the first 20-30 words (Reddit insight: "First lines set tone").
Example Iteration: Base: "Female knight." Refined: "Powerful female knight in ornate silver armor with flowing blonde hair, defiant stance."

2. Action & Motion (Videos: Dynamic Core)For images: Implied (e.g., "mid-leap").
Videos: Explicit verbs + physics: "Flap wings slowly, cape fluttering in wind, realistic motion blur."
Templates: "Make [subject] [action] in [style], with [camera], looped, 4K, 24fps."
Reddit Tip: Linear actions > multi-step (e.g., "sip coffee, smile" works; "sip, drop, react, grimace" may glitch—break into chains).

3. Environment & Setting (World Building: Immersive Depth)Sensory details: "Lava lit cave with pulsing runes and acrid smoke."
Scale: Foreground (dew kissed petals), mid (cliffs), background (stormy horizon).
Avoid overload: 2-3 elements max; Grok struggles with "busy" scenes (e.g., forest walk > crowded city).

4. Cinematic Framing & Camera (Perspective Control: Pro-Level Polish)Lenses/Shots: "35mm DoF, slow dolly-in, overhead drone."
Video Modifiers: "Handheld shake, whip pan, crane up" (X-tested for energy).
Advanced: "Dutch tilt for tension, volumetric god rays" (from recent updates).
Tip: Specify aspect (9:16 vertical for X Reels) and FPS (24 for filmic).

5. Aesthetic & Style (Tone & Polish: Final Flourish)Anchors: "Hyperrealism, ArtStation trending, Masamune Shirow style."
Lighting/Mood: "Cold bluish underglow fading to shadow, dormant terror."
Negatives: Rare Grok ignores them; use positives like "no blur" sparingly.
Genres: Append "80s OVA anime, dark mysterious" for vibes.

Prompt Length & Strategies (Community-Tested)
Length                   Use Case                     Example Structure                                  Pros/Cons
Short (<50 words)        Quick ideation, surprises    "Rainy neon alley, handheld cyberpunk."            Fast; less control (Reddit: Good for memes).
Medium (50-150 words)    Balanced precision           Subject; Action; Env; Camera; Style semicolons     Versatile; stable outputs.
Long (>150 words/JSON)   Complex videos/edits         {"subject": "...", "motion": "..."}                Detailed; risks chaos (X tip: Cap at 200 chars for videos).

Iteration Workflow: 

Gen 1: Core idea. 
Gen 2: Add motion ("Animate flap"). 
Gen 3: Refine camera ("Orbit 360°").
Templates in Action: Plug-and-play from repo (e.g., Fantasy: Swap "knight" for "elf").
JSON for Structure: Great for videos; e.g., {"camera": {"shot": "crane up"}} (avoids rambling).

Advanced TechniquesVideo Chains: Gen image > Custom video prompt > Edit (e.g., "Add timelapse lights").

ASCII Art Prompts: Upload simple sketches for stylized gens (X hack: "Prompt with ASCII, no text for video").

NSFW/Spicy: Start with "silk robe forest walk," escalate to "striptease" in custom mode (Reddit: Moderation lenient post-update, but "cupping" or "dancing" safer starters).

Audio Sync: "Native audio: orchestral swell" for mood (works 70% per X tests).

From Reddit r/grok: Use "physics simulation" for realism; avoid negations ("no blur" > imply "sharp focus").

Troubleshooting & Best PracticesGlitches: Too many elements? Simplify (e.g., drop "floating drones" if pose breaks). Long prompts dilute prioritize first sentence.

Moderation: "Spicy" mode for edges; avoid direct "NSFW" (triggers blocks).

Quotas: Free: 10-20/day; SuperGrok unlimited. Test on x.com for speed.

Common Pitfalls (X/Reddit Consensus):Vague: "Beautiful scene" → Chaotic.
Over-Poetic: Dry facts > flowery (e.g., "lit from below" > "ethereal glow").

Multi-Action Videos: Linear only; use "cuts to" sparingly.

Optimization: Repetition locks details (e.g., "chrome bodysuit; reflective chrome"). For anime: "80s OVA, cel-shaded."

Prompt Collections
Categorized in /prompts/. Each .md has 10-15 prompts in tables, with tips. New genres added: Fantasy, Anime & Cyberpunk, Action Videos, NSFW/Spicy (tasteful examples).Photorealistic & Portraits (/prompts/photorealistic-portraits.md) (Updated with 2 new)

Sci-Fi & Futuristic (/prompts/sci-fi-futuristic.md) (Updated)
Abstract & Surreal (/prompts/abstract-surreal.md)
Nature & Everyday Scenes (/prompts/nature-everyday.md) (New: 3 from Reddit)
Video & Animation (/prompts/video-animation.md) (Expanded)
Editing & Transformations (/prompts/editing-transformations.md)
Styles & Moods (/prompts/styles-moods.md)
Fantasy (/prompts/fantasy.md) (Elves, demons, knights)
Anime & Cyberpunk (/prompts/anime-cyberpunk.md) (80s OVA, neon warriors)
Action Videos (/prompts/action-videos.md) (High-energy sequences)
NSFW/Spicy (Tasteful) (/prompts/nsfw-spicy.md) (From Reddit, moderated)
Cinematic Templates (/prompts/cinematic-templates.md) (Camera hacks)



Code of Conduct (CODE_OF_CONDUCT.md). 
Join X discussions: #GrokImaginePrompts.

Resources
xAI Docs
API
Reddit: r/grok (prompt threads)
X: Search "Grok Imagine prompts filter:media"

LicenseMIT © 2025 xAI Community. 
LICENSE.Inspired by awesome lists. 
Updated Oct 19, 2025 with 50+ new prompts from X/Reddit.

=======
# awesome-grok-imagine-prompts
A curated collection of prompts for Grok Imagine by xAI
