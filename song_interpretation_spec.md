# One-Sentence Song Interpretation Specification

## 1) Strict output format

- **Length:** exactly **1 sentence**, **16–24 words**.
- **Perspective:** **third-person only** (no “I”, “me”, “my”, “you”, “we”).
- **Tone:** **neutral-analytic** and concrete; avoid poetic flourish, moralizing, or slang.
- **Content rule:** state the song’s central emotional conflict plus likely cause/context in plain language.
- **Output-only rule:** return only the sentence (no labels, bullets, quotes, emojis, or extra commentary).

### Pass example
The song portrays someone masking resentment with humor after repeated betrayal by a close friend, revealing unresolved distrust and emotional fatigue.

## 2) Human evaluation criteria (1–5 scales)

### A. Faithfulness to lyrics
- **1:** Contradicts or invents major meaning not supported by lyrics.
- **2:** Partly grounded, but includes clear unsupported claims.
- **3:** Mostly supported; minor overreach or missed nuance.
- **4:** Well supported with only small interpretation leaps.
- **5:** Fully grounded in lyrical evidence; no visible hallucination.

### B. Specificity (non-generic insight)
- **1:** Vague, interchangeable statement that fits many songs.
- **2:** Slightly specific but still mostly generic.
- **3:** Contains one concrete insight, but remains broad overall.
- **4:** Clearly song-specific with concrete emotional/contextual detail.
- **5:** Highly specific and distinctive, capturing unique tension or situation.

### C. Format and style compliance
- **1:** Fails multiple core constraints (sentence count, perspective, tone, or length).
- **2:** Fails one major constraint or several minor ones.
- **3:** Mostly compliant, with one noticeable issue.
- **4:** Fully compliant except tiny wording/tone drift.
- **5:** Perfect compliance with all required constraints.

## 3) Generic words to avoid

Avoid these unless directly quoted from lyrics:

- happy
- sad
- love
- pain
- heartbreak
- lonely
- struggle
- feelings
- emotions
- life
- relationship
- memories
