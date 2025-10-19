# 🧲 Ad Headlines Prompt

````markdown
You are a paid ads copywriter.
Write 10 ad headlines (8–12 words max) for [product/offer].
Each headline should highlight one of these angles:
- Pain point
- Desired outcome
- Proof/stat
- Curiosity
Tone: persuasive but natural.
Return a 2-column table: Headline | Angle.
Tip: Add a second prompt — “Critique each headline for clarity & emotional punch, then rewrite the weakest 3.”

---

### 💌 2️⃣ `prompts/welcome_email.md`
```markdown
# 💌 Welcome Email Prompt

**Goal:** Write a friendly but strategic welcome email for new subscribers.

````markdown
You are an email copywriter.
Write a 150–200 word welcome email for [brand/course/product].
Include:
- A warm personal intro
- What they’ll get next
- A single clear call to action
Tone: human, conversational, trustworthy.
Return 2 versions: casual / professional.
Example Output

Subject: Welcome aboard — here’s your first bonus

Hey [Name], thanks for joining! Here’s a quick freebie to start…
[CTA link]

---

### 📢 3️⃣ `prompts/social_post_prompts.md`
```markdown
# 📢 Social Post Generator

**Goal:** Create 5 ready-to-post captions with hooks + CTAs.

````markdown
You are a content strategist.
Generate 5 social media posts for [topic/product].
Each post = Hook line (max 10 words) + 2–3 sentences of value + CTA.
Tone: friendly + scroll-stopping.
Return them as a numbered list.
Bonus Ask: "For each, suggest 1 emoji and 2 hashtags."

---

### 🧠 4️⃣ `prompts/storytelling_prompt.md`
```markdown
# 🧠 Storytelling Prompt

**Goal:** Turn a fact or lesson into a micro-story.

````markdown
You are a storytelling coach.
Write a 150-word story for [topic].
Structure:
1. Relatable problem
2. Unexpected twist or insight
3. Lesson that ties to the offer
End with a one-line CTA.
Tone: emotional and authentic.
“Last year, I almost quit freelancing. Then one small prompt changed everything…”

---

### 🧮 5️⃣ `prompts/value_ladder_prompt.md`
```markdown
# 🧮 Value Ladder Copy Prompt

**Goal:** Write clear copy for 3 offers at different price levels.

````markdown
You are a marketing strategist.
Create copy blurbs for a value ladder:
1. Free Lead Magnet
2. Mid-tier Course or Offer
3. Premium Service
Include name, one-sentence promise, and CTA for each.
| Tier    | Name           | Promise                     | CTA           |
| ------- | -------------- | --------------------------- | ------------- |
| Free    | Prompt Toolkit | Learn pro prompts in 15 min | Download free |
| Mid     | AI Copy Sprint | Write 5x faster in 5 days   | Enroll now    |
| Premium | 1:1 Copy Audit | Get your prompts fixed live | Book session  |

---

### 💬 6️⃣ `prompts/comment_engagement.md`
```markdown
# 💬 Comment Engagement Prompt

**Goal:** Generate natural comment replies that build relationships.

````markdown
You are a community manager.
Write 5 comment replies for this post text: [paste post].
Each reply should:
- Sound like a real human
- Add value or a question
- Keep the convo going
Tone: friendly and concise.
Return 5 unique replies.

---

### 🔍 7️⃣ `prompts/hook_angle_test.md`
```markdown
# 🔍 Hook Angle Tester

**Goal:** Test different emotional angles for a hook.

````markdown
You are a creative strategist.
Write 8 hooks for [topic].
Each one should target a unique angle:
1. Pain
2. Desire
3. Curiosity
4. Proof
5. Contrarian
6. Fear of missing out
7. Speed/Ease
8. Status
Return a table: Hook | Angle | Emotional driver.
Bonus: Ask AI — “Which 2 hooks feel most emotionally charged and why?”

---

### 🧩 8️⃣ `prompts/product_description.md`
```markdown
# 🧩 Product Description Prompt

**Goal:** Create short & long product descriptions.

````markdown
You are a copywriter.
Write:
1. 3 short (under 50 words) descriptions for social media.
2. 1 long (150 words) product page description.
Include 3 benefits, 1 proof element, and a strong CTA.
Product: [describe product]. Audience: [describe audience].
Tip: “Now rewrite the long version in a friendly storytelling tone.”

---

### 🧰 9️⃣ `prompts/problem_solution.md`
```markdown
# 🧰 Problem–Solution Prompt

**Goal:** Write a short persuasive piece showing problem → fix.

````markdown
You are a conversion copywriter.
Write a 120-word paragraph following the Problem → Agitation → Solution format.
Topic: [your offer or issue].
Include a CTA that feels like a relief (“Here’s the shortcut” tone).

Example
Problem: Writing is slow.
Agitation: You stare at a blank screen daily.
Solution: Steal my free AI prompts.

---

### 🗣️ 🔟 `prompts/testimonial_prompt.md`
```markdown
# 🗣️ Testimonial Extractor Prompt

**Goal:** Turn raw testimonials into punchy social proof lines.

````markdown
You are a copywriter.
Summarize these testimonials into 5 punchy proof bullets (≤12 words each).
Focus on results, numbers, and emotions.
Testimonials:
- “[testimonial 1]”
- “[testimonial 2]”
- “[testimonial 3]”
Return a table: Proof Bullet | Emotion Trigger.
