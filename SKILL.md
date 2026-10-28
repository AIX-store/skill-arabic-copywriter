---
name: arabic-copywriter
description: Writes native Arabic marketing and product copy from a brief instead of translating English line by line. Chooses the register (Modern Standard Arabic by default, Gulf or Egyptian when asked), keeps tone consistent, handles numerals, punctuation and Latin brand names safely in right-to-left text, and returns copy with length notes. Use when someone needs Arabic headlines, landing pages, app store text, push notifications, ads, onboarding screens or email copy, or asks to "make this sound natural in Arabic".
---

# Arabic Copywriter

Write Arabic that reads as if an Arabic-speaking copywriter wrote it first. The English
source, if any, is a brief, not a script.

## When to use
- Landing pages, hero headlines, ads, app store listings, push and in-app messages.
- Product UI microcopy (buttons, empty states, errors) that needs a human voice.
- Rewriting existing Arabic that sounds translated ("machine Arabic").

## Step 1 — Pin down the brief
Ask for, or infer and state, these before writing:
1. Audience: consumers or businesses; age band; country if it changes vocabulary.
2. Register: **MSA** (default, safe across the region), **Gulf white dialect** (light
   Gulf flavour readable by all Gulf audiences), or **Egyptian** (warm, informal, mass reach).
   Never mix registers inside one asset.
3. Address form: second person singular masculine is the conventional default; offer a
   gender-neutral alternative (imperative plural, or "you" avoided via noun phrases) for
   inclusive brands. Decide once and keep it.
4. Tone: formal-trustworthy (banking, government), friendly-confident (SaaS, retail),
   playful (food, lifestyle).
5. Hard limits: character counts per slot, banned words, legal claims.

## Step 2 — Write from meaning, not words
- Extract the single promise of each English line, then write the Arabic line from that
  promise. English idioms ("game-changer", "level up") have no literal equivalent; find
  the Arabic image that carries the same benefit.
- Prefer verbs over nominalisations: "ابدأ الآن" beats "قم بالبدء".
- Avoid the calque "قم بـ + masdar" for every button; use the direct imperative.
- Cut filler connectors (حيث، إنّ، كما أنّ) that pad translated text.
- Headlines: 2–6 words. Arabic headlines can drop the verb ("أمانك أولًا").
- Keep one idea per sentence; Arabic tolerates long sentences but screens do not.

## Step 3 — Mechanics
- **Numerals:** use Western digits (0–9) for digital products unless the brand or market
  explicitly prefers Arabic-Indic (٠–٩). Never mix both in one asset.
- **Punctuation:** Arabic comma "،", semicolon "؛", question mark "؟". Full stop is the
  ordinary dot. No space before punctuation; one space after.
- **Quotes:** use «…» or "…" consistently.
- **Brand names in Latin script** (product names, tickers): keep them Latin when the brand
  is known that way; place them where a bidi flip will not reorder surrounding words —
  ideally not at the very start or end of a line with trailing punctuation.
- **Numbers with units and currency:** write "99 ريالًا" or "SAR 99" per house style; keep
  the currency position consistent across all assets.
- **Tanween and shadda:** add only where they prevent misreading (ريالًا، شكرًا).
- **Hamza and taa marbuta:** spell correctly; these errors signal low quality instantly.
- **Gender and number agreement:** check every adjective and verb against its noun,
  especially with numbers 3–10 (reverse gender agreement) and 11+ (singular accusative).

## Step 4 — Self-review checklist
- [ ] Read aloud: does it sound like speech or like a document?
- [ ] Any word an Arabic speaker would only see in translated text? Replace it.
- [ ] Register consistent throughout?
- [ ] Every slot within its character limit (Arabic often runs 20–30% shorter than
      English in characters but can render wider; check visually)?
- [ ] Religious or cultural sensitivities: no alcohol/gambling imagery, careful humour
      during Ramadan, no imagery-dependent puns that fail in Arabic.
- [ ] Claims are true and not stronger than the English source.

## Output format
For each slot, return a table row:

| Slot | Arabic copy | Back-translation (meaning) | Chars | Notes |

Then offer two alternates for every headline (one bolder, one calmer).

## Worked example
Brief: "Get paid faster. Send invoices in seconds." — SME invoicing app, MSA, friendly.

| Slot | Arabic copy | Back-translation | Chars | Notes |
|---|---|---|---|---|
| Headline | استلم مستحقاتك أسرع | Receive your dues faster | 19 | "مستحقات" fits business tone better than "فلوس" |
| Sub | أرسل فاتورتك في ثوانٍ، وتابع الدفع من مكان واحد | Send your invoice in seconds and track payment in one place | 45 | Added tracking benefit implied by the brief; flag for approval |
| CTA | ابدأ مجانًا | Start free | 10 | Direct imperative, no "قم بـ" |

## Pitfalls
- Literal translation of English wordplay — it never survives.
- Over-formal MSA in a playful consumer app; over-casual dialect in finance.
- Machine-translated plurals and dual forms that are grammatically wrong.
- Exclamation marks on every line; Arabic marketing uses them sparingly.
- Forgetting to test the copy in the real right-to-left layout before sign-off.
