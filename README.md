# 📖 Words Reader


A vocabulary flashcard app for practising reading Japanese words written in hiragana and katakana, with meanings, romaji, and example sentences.

---

## What's Inside

- **45 Japanese words** across 3 difficulty levels
- Words shown in kana — you read them, then flip to check
- Two answer modes: multiple choice (early cards) and self-grading (later cards)
- Example sentences on the back of every card
- "Retry missed" mode to target vocabulary you struggled with

---

## Levels

Select a level from the header buttons:

| Level | Theme | Example words |
|-------|-------|--------------|
| **Level 1 · Basics** | Animals, food, basic verbs & adjectives | ねこ (cat), たべる (to eat), おおきい (big) |
| **Level 2 · Daily** | Daily life, routines, school, transport | しごと (work), でんわ (phone), むずかしい (difficult) |
| **Level 3 · Advanced** | Abstract nouns, complex expressions | おもいやり (empathy), こころざし (ambition) |
| **All Levels** | Every word shuffled together | Full 45-card mixed deck |

---

## How to Use

1. Pick a level from the top of the page.
2. A word appears in kana on the front of the card. Try to read it and recall the meaning.
3. **Tap the card** (or press `Space` / `↑`) to flip and reveal:
   - The kana reading
   - Romaji pronunciation
   - English meaning
   - An example sentence in Japanese with translation
4. Grade yourself:

### Multiple Choice Mode *(first ~half of deck)*
Four English options are shown. Tap the one you think is correct.  
- Green = correct, auto-advances after a short pause.  
- Red = wrong, correct answer is highlighted.

### Self-Grade Mode *(second ~half of deck, and all of Level 3)*
After flipping the card, choose:

| Button | Keyboard | Meaning |
|--------|----------|---------|
| ✕ Didn't know | `1` | Add to retry pile |
| ↻ Almost | `2` | Add to retry pile |
| ✓ Knew it! | `3` | Mark correct |

---

## Word List Summary

### Level 1 – Basics (15 words)
ねこ いぬ みず パン たべる のむ おおきい ちいさい あか あおい きれい でんしゃ がっこう せんせい ともだち

### Level 2 – Daily Life (15 words)
かいもの りょうり しごと やすみ おしえる はなす むずかしい たのしい でんわ びょういん にほんご えいご きょうだい おなかがすく あたらしい

### Level 3 – Advanced (15 words)
けいざい かんがえる きんちょう きけん けんきゅう かいはつ ようやく かならず むかし ちかごろ なるほど かさなる ひとりぼっち おもいやり こころざし

---

## When the Deck Ends

A summary screen shows your score (%), correct count, missed count, and "almost" count.

- **Retry Missed** — drills only the words you marked wrong or almost.
- **New Deck** — reshuffles the full level deck.

---

## Technical Notes

- Pure HTML + CSS + Vanilla JS — zero dependencies, no build step.
- Fonts: Syne, DM Sans, Noto Serif JP (Google Fonts).
- 3D card flip using CSS `rotateX` transform.
- Fully offline-capable after initial font load.

---

*Part of the Kana Learning Suite · see also `Kana flash repository` and `kana master test repository`*
