# The OBSD Case Writing Kit

Turn a news article into a classroom-ready dilemma teaching case — with any AI assistant, including free ones.

**Version 1.0 — July 2026**
Method: Dr. Andrew Schenkel (Stockholm School of Economics), Dr. Ciara Sutton (Stockholm School of Economics), Dr. Olof Brunninge (Jönköping International Business School).
*[Credit and license line to be confirmed with the authors before publication.]*

---

## What this kit does

Good teaching cases are scarce, and writing one takes time most educators do not have. This kit turns a real news article into a short dilemma teaching case — the kind that ends at a fork in the road, where a real decision-maker must choose between two defensible actions, and the discussion in your classroom does the rest.

The kit is built on the OBSD method: **O**bjective, **B**ackground, **S**ituation, **D**ilemma. You provide the thinking. The AI provides structure and drafting. It never replaces your judgment, and it never decides for the protagonist.

It is free to use and works with free AI tools.

## Which version should I use?

**The Full Version** — for free ChatGPT, Gemini, Claude, DeepSeek, or similar. Paste it into a new chat, or save it as the instructions of a Project, Gem, or custom GPT — your choice. The AI interviews you through the OBSD questions, tests whether your dilemma is strong enough, writes the case, and shows you where every fact came from.

**The Light Version** — for small or local AI models (for example, models running on your own PC), or if you prefer to think on paper first. You answer the OBSD questions yourself, the AI does exactly one thing — write the case — and you check the facts yourself with a short checklist.

Both versions carry the same method. The Light Version asks more of you and less of the model.

At the end of this kit you will also find: **three repair prompts** for when a case comes out wrong, an optional **instructor's epilogue** step, and a **complete worked example** — a fictional article, filled-in answers, and the finished case. If this is your first case, read the worked example first; it is faster than any instruction.

## Three honest warnings — read once

1. **You are the author.** The AI is a drafting tool. You are responsible for the accuracy and quality of anything you use in class.
2. **AI models invent plausible facts.** In our own testing, models added numbers and details that appeared in no source — even under strict instructions. The fact-check step in each version is not optional politeness; it is where errors are caught. Verify every name, number, and date against your article before classroom use.
3. **Your students have AI too.** If you use AI to write cases, students will use AI to analyse them. The learning happens in your facilitation — clear objectives, mastery of the case facts, a live discussion. The case is the starting gun, not the race.

**Practical note:** keep this kit as a plain text or markdown file and copy from it directly. Do not copy from a PDF — PDF line breaks can silently corrupt the instructions.

---
---

# THE FULL VERSION

*(Paste everything between the START and END lines into a new chat with any capable AI assistant — free ChatGPT, Gemini, Claude, or similar — or save it as the instructions of a Project, Gem, or custom GPT. Then follow the assistant's lead.)*

```
--- START OF INSTRUCTIONS ---

YOUR ROLE

You are a case-writing assistant. You help an educator turn a real news
article (or similar source document) into a short teaching case for
classroom discussion, using the OBSD method (Objective, Background,
Situation, Dilemma) developed by Dr. Andrew Schenkel, Dr. Ciara Sutton
(Stockholm School of Economics) and Dr. Olof Brunninge (Jönköping
International Business School).

A dilemma teaching case places students inside a real situation where a
decision-maker must choose between two actions that appear mutually
exclusive, each supported by strong reasons. The case ends at the moment
of decision and never reveals the outcome. The educator provides the
thinking; you provide structure and drafting. You never replace their
judgment.

YOUR WORKFLOW

Work through these phases in order. Do not skip ahead. Do not write the
case until Phase 4.

PHASE 1 — SOURCE MATERIAL
Ask the educator to paste the full text of their news article (or attach
it, if their tool allows). More than one article is fine. When you have
it, confirm in one sentence what the article is about, then move to
Phase 2. From this point on, the pasted article(s) and the educator's
interview answers are your only sources of facts.

PHASE 2 — OBSD INTERVIEW
Interview the educator ONE QUESTION AT A TIME. Ask a question, wait for
the answer, then ask the next. If the educator asks for a faster pace,
you may instead ask one OBSD section at a time. Keep your comments
brief. If the educator is unsure of an answer, you may propose a draft
answer based on the article and ask them to confirm or edit it — but
never silently answer for them.

The questions:

O — OBJECTIVE
1. Teaching objective: What should students understand, practise, or be
   able to do as a result of discussing this case?
2. Case objective: What is the central challenge the protagonist must
   resolve? State it as the managerial problem the case is built around.

B — BACKGROUND
3. Who is the single accountable decision-maker? (Name and role.)
4. What formal authority does this person have? Any approval
   requirements or legal boundaries?
5. What constraints limit this person right now?
6. What prior action, commitment, or public statement makes this
   decision more difficult?
7. What aspects of the organisation (culture, strategy, resources,
   history, internal politics) shape how the protagonist can act?
8. What external conditions (market, regulation, competition, societal
   expectations) narrow the protagonist's options?

S — SITUATION
9. What event triggered the situation?
10. What did people reasonably expect to happen, and why was that
    expectation reasonable at the time?
11. What actually happened instead?
12. What consequence increased the pressure?
13. What is becoming irreversible?
14. Why can the decision not be postponed?

D — DILEMMA
15. Describe the two actions the protagonist could take.
16. For each action: what does choosing it protect that the protagonist
    genuinely cares about, and what would be lost or made harder?

PHASE 3 — DILEMMA STRESS TEST
Before writing anything, test the two options against three checks and
tell the educator plainly how each check comes out:
a. Fork in the road: do the options appear mutually exclusive at first
   glance? Choosing one must make the other significantly harder — and
   any way of combining them must not be obvious.
b. Both matter: does each option protect something the protagonist
   genuinely cares about? If one option is clearly inferior, students
   will not engage.
c. No obvious answer: would a colleague who does not know the case be
   unable to immediately name the "right" choice?
If any check fails, say which one, explain why, and suggest how to
strengthen it. Then ask the educator whether they want to revise their
answers or proceed anyway. Their call.

PHASE 4 — WRITE THE CASE
Write a decision-forcing case of 750–1,000 words. Rules:
- Use the OBSD structure internally, but never show the labels
  Objective, Background, Situation or Dilemma in the output. Sparing
  descriptive headings (e.g. "Mounting Pressure") are allowed.
- Use only facts from the pasted article(s) and the educator's answers.
  Do not invent facts, statistics, quotes, or motivations — and do not
  add durations, countdowns, or dates that appear in no source.
- You may STAGE scenes (a meeting, a phone call, a moment of reading a
  report) to carry the narrative, as long as every staged element is
  consistent with the documented facts. Staging a scene is allowed;
  inventing a fact, number, name, or motivation is not.
- Rewrite entirely in original language. Do not copy the article's
  structure, phrasing or sequencing. If it reads like journalism, it is
  not yet a teaching case.
- Remove hindsight. Reconstruct the situation as it looked at the time
  of the decision, using only what the decision-maker could have known
  then. Never reveal or hint at the eventual outcome.
- Begin with a concrete moment of pressure. Escalate efficiently: every
  event should increase pressure and reduce room for manoeuvre. Make
  clear why the decision must be made now.
- Continuous narrative prose. No bullet points, no analysis, no theory,
  no teaching commentary, no moral judgment, no signal of which option
  is better.
- Set the final scene at the deadline itself, with the protagonist
  about to act. The case must end at the exact moment the decision can
  no longer be postponed — not hours or days before it.

PHASE 5 — SOURCE CHECK
Immediately after the case, add a section titled "Source check", with
three lists:
1. Every name, number, date, and factual claim used in the case, and
   where each one appears in the pasted article or in the educator's
   answers.
2. "Staging — consistent with the sources, not documented in them":
   every staged scene element (timings, meetings, calls you added for
   narrative flow).
3. "Not verified — educator must check or delete": any statement not
   directly supported by the sources. Aim for this list to be empty.
Remind the educator: verify every fact against the original source
before classroom use. You are a drafting tool; the educator is the
author and is responsible for accuracy.

PHASE 6 — TEACHING NOTE AND EPILOGUE (OPTIONAL)
Ask one question: "Would you like a short teaching note — a board plan,
opening questions, and a suggested discussion flow?" If yes, produce
one, clearly grounded in the teaching objective from Question 1.
Then ask one more: "Would you like an instructor-only epilogue — 100 to
150 words on what actually happened, drawn from the article — to reveal
only after the class discussion?" If yes, produce it under the heading
"Instructor only — do not distribute with the case."

GENERAL CONDUCT
Be brief and practical between phases. If the educator names their
language of instruction, conduct the interview and write the case in
that language. If they name their student level (undergraduate, MBA,
executive), match the case's vocabulary and complexity to it. Never
resolve the dilemma or
recommend an option, in the case or in conversation. If the educator
asks you to skip the interview and "just write it", do it — but say
first, in one sentence, that the quality of the dilemma depends on the
quality of the answers, and note in the Source check which OBSD
elements were never provided.

--- END OF INSTRUCTIONS ---
```

---
---

# THE LIGHT VERSION

*(For small or local AI models — for example, models run on your own PC — and for any free chatbot. Three steps. Only Step 2 uses the AI.)*

## STEP 1 — Answer the OBSD questions (no AI needed)

Open a text file (or take a sheet of paper) and answer these questions in your own words. Short answers are fine. Draw on your news article where useful. This thinking is the case — do not skip it.

**OBJECTIVE**
1. What should students understand or be able to do after discussing this case?
2. What is the central problem the protagonist must resolve?

**BACKGROUND**
3. Who is the single accountable decision-maker? (Name and role.)
4. What authority does this person have, and what approvals or legal limits apply?
5. What constraints limit this person right now (money, time, regulation, stakeholders)?
6. What prior action, commitment, or public statement makes this decision harder?
7. What inside the organisation (culture, strategy, resources, politics) shapes what the protagonist can do?
8. What outside conditions (market, regulation, competition, society) narrow the options?

**SITUATION**
9. What event triggered the situation?
10. What did people expect to happen, and why was that reasonable at the time?
11. What actually happened instead?
12. What consequence increased the pressure?
13. What is becoming irreversible?
14. Why can the decision not be postponed?

**DILEMMA**
15. Describe the two actions the protagonist could take.
16. For each action: what does it protect that the protagonist cares about, and what does it sacrifice?

**Before Step 2, check your two options:**
- Do they look mutually exclusive at first glance — no obvious way to combine them?
- Does each protect something that genuinely matters?
- Would a colleague be unable to immediately name the "right" choice?

If any answer is no, sharpen your answers to questions 15 and 16 first.

**Then prepare your article:** in your copy of the article text, DELETE any paragraphs that reveal how the story ended — the outcome, the verdict, what commentators said afterwards. The case must stop at the decision; if the model never sees the ending, it cannot leak it.

## STEP 2 — Generate the case (paste this into the AI)

Copy everything between the START and END lines into the chat, replacing the two placeholders at the bottom with your Step 1 answers and your prepared article text.

```
--- START OF PASTE ---

Write a teaching case of 750–1,000 words based only on the CASE
MATERIALS below, following the OBSD case method (Schenkel, Sutton &
Brunninge). A teaching case puts the reader inside a real decision:
one accountable person facing two options that seem impossible to
combine.

Follow these 8 rules exactly:
1. Use only facts found in the CASE MATERIALS. Do not invent names,
   numbers, quotes, events, or motivations — and do not add durations,
   countdowns, or dates that are not in the materials.
2. Use only information the decision-maker could have known at the
   time. Do not reveal or hint at what happened afterwards.
3. Write in your own words. Do not copy sentences or structure from
   the article.
4. Start with a concrete moment of pressure (a meeting, a deadline, a
   phone call — you may stage such scenes, as long as they fit the
   documented facts). Build pressure with each paragraph and make
   clear why the decision must be made now.
5. Present both options so that each seems defensible. Never suggest
   which is better.
6. Write flowing narrative prose. No bullet points, no analysis, no
   theory, no advice.
7. Set the final scene at the deadline itself, with the protagonist
   about to act. The last paragraph must take place at the moment the
   decision can no longer be postponed — not hours or days before it.
   Do not resolve anything.
8. Output only the case text. Nothing else.

CASE MATERIALS

My answers to the OBSD questions:
[PASTE YOUR STEP 1 ANSWERS HERE]

The article:
[PASTE YOUR PREPARED ARTICLE TEXT HERE]

--- END OF PASTE ---
```

If the model's output stops mid-text or ignores the materials, your model may have a small memory. Trim the article to only the paragraphs that matter for the decision and try again.

**Optional lines** — if you want them, add either or both at the end of the 8 rules before pasting:

```
9. Write the case in [your language of instruction].
10. My students are [undergraduates / MBA students / executives] —
    match vocabulary and complexity to them.
```

## STEP 3 — Check the case yourself (no AI)

The AI is a drafting tool. You are the author, and you are responsible for accuracy. Before using the case in class:

1. **Circle every name, number, date, and factual claim** in the case.
2. **Find each one in your article or your Step 1 answers.** Delete or correct anything you cannot find. AI models invent plausible facts — in our testing, even careful models added a countdown ("seventy-two hours") that existed in no source.
3. **Read the final paragraph:** does it take place at the moment the decision can no longer be postponed — and stop there, revealing nothing? If not, cut or rewrite until it does.
4. **Read both options:** would a colleague find each defensible? If one sounds obviously right, rewrite the framing until the tension returns.
5. **Read it once as a student would:** is there a real fork in the road, and a reason it must be decided today?
6. **Check the length:** roughly 750–1,000 words. Long enough for substance, short enough for a focused discussion.

## STEP 4 — Optional: the instructor's epilogue

A classroom tradition: after the discussion ends, the instructor reveals what actually happened. The paragraphs you deleted from the article in Step 1 are exactly that material. If you want an epilogue, paste this into the AI:

```
From the article paragraphs below, write an epilogue of 100–150 words
titled "What actually happened", in neutral language, for the
instructor to reveal only after the class discussion.

[PASTE THE PARAGRAPHS YOU DELETED IN STEP 1]
```

---
---

# IF THE CASE COMES OUT WRONG — THREE REPAIR PROMPTS

These cover the failures we saw most often in testing. Paste the matching line into the same chat and the model will revise its own draft.

**The case favours one side:**
```
The narrative currently makes one option look better. Rewrite the case
so both options are equally defensible, without adding any new facts.
```

**The ending arrives too early, or reveals too much:**
```
Rewrite the final paragraphs so the case ends at the exact moment the
decision can no longer be postponed, and reveals nothing about the
outcome.
```

**It still reads like a news article:**
```
This still reads like journalism. Restage it as a narrative: concrete
scenes, building pressure, no commentary — using the same facts only.
```

---
---

# APPENDIX — A COMPLETE WORKED EXAMPLE

*Everything below is fictional — invented company, people and events — created to show the full journey from article to case. Read it once before your first attempt; it is faster than any instruction.*

## The source article (fictional)

> **West Africa Commerce Weekly — May 2026**
>
> **The thirty-six hours that tested Ashanti Harvest**
>
> In March of this year, Efua Mensah, chief executive of the Accra-based food processor Ashanti Harvest Foods, faced the kind of decision that defines a career. What follows is an account assembled from interviews with company staff, customers and industry observers.
>
> Ashanti Harvest, founded in 2009, employs 420 people at its processing plant outside Accra. In January it signed the largest contract in its history: €2.4 million a year supplying peanut paste to Van Doren Distribution of Rotterdam — about 60 per cent of the company's export revenue. The deal followed two years of audits and sample shipments. Van Doren had dropped its previous supplier over missed delivery windows; its head of procurement told Mensah during the final negotiation that "reliability is the product."
>
> On the Friday before the company's first quarterly shipment — 240 tonnes, booked onto a vessel whose loading gate at the port of Tema closed the following Tuesday at 19:00 — Ashanti Harvest's internal laboratory flagged a problem. Three of ten samples drawn from the production run tested above the European Union's limit of four parts per billion for total aflatoxin, at six, seven and nine parts per billion. Seven samples were clean, and blending records put the consignment's aggregate below three parts per billion. The failed samples traced to two lots from a growing region that had suffered unseasonal rain in February. An independent retest by an accredited laboratory was commissioned, but results would not arrive before Thursday morning — after the vessel's departure. The next vessel with space was twelve days later.
>
> The contract carried an €85,000 late-delivery penalty and a review clause for missed windows. Company accounts seen by this magazine suggest Ashanti Harvest was holding about eleven weeks of operating cash, with payments to farmer cooperatives due the following month.
>
> Mensah's position was complicated by her own words. After the collapse of rival Volta Groundnut last year — its contaminated shipment was seized in Hamburg — she told an industry forum there would be "zero compromise on safety, whatever it costs."
>
> Consignments failing an EU border test are destroyed at the exporter's cost, and a public alert is posted in the EU's food-safety system — an outcome industry figures say can tighten controls for a whole country's exporters.
>
> In the event, Mensah held the shipment. The Thursday retest cleared the consignment, Van Doren invoked the penalty but kept the contract, and the paste sailed twelve days late. "Her caution was vindicated," said one Accra-based food-safety consultant. "Shipping on those numbers would have been reckless — this should be taught as a lesson in doing the right thing."

*Note for the Light Version: the last paragraph is exactly what Step 1 tells you to delete before pasting — it reveals the outcome. It is also exactly the material Step 4 turns into the instructor's epilogue.*

## The educator's OBSD answers (fictional example)

**OBJECTIVE**
1. Students should practise decision-making under uncertainty when risks are asymmetric and partly irreversible, learn to separate the quality of evidence from the pressure of consequences, and map stakeholder trade-offs.
2. Should the CEO release the consignment for loading, or hold it for the independent retest and miss the vessel?

**BACKGROUND**
3. Efua Mensah, Chief Executive Officer, Ashanti Harvest Foods.
4. Full operational authority over shipment release; the board oversees but no approval is required. EU food-safety law applies to the product on arrival.
5. About eleven weeks of operating cash; an €85,000 late-delivery penalty plus a contract review clause; the retest cannot arrive before the loading gate closes; the next vessel is twelve days later; payments to farmer cooperatives are due next month.
6. Her public pledge after the Volta Groundnut collapse: "zero compromise on safety, whatever it costs."
7. The company is proud of its quality reputation; the quality director and the commercial director are in open disagreement; the workforce knows the run was flagged.
8. The EU limit of four parts per billion; random EU border testing, with destruction of the consignment and a public alert on failure; the buyer left its previous supplier over reliability; a failure could harm all Ghanaian groundnut exporters.

**SITUATION**
9. Three of ten samples over the aflatoxin limit on the first consignment of the new flagship contract.
10. A clean run was expected — the line operated normally and the lots had passed intake sorting.
11. Three samples failed at six, seven and nine parts per billion, traceable to two lots from a rain-affected region, while the blended aggregate remained compliant.
12. The retest timing collided with the loading gate; the commercial director warned a missed window could trigger the review clause; the quality director warned of seizure at a European port.
13. Once loaded and sailed, the consignment cannot be recalled; once the window is missed, the penalty and review clause trigger; cash is burning weekly.
14. The release order must reach the freight forwarder before the gate closes on Tuesday at 19:00.

**DILEMMA**
15. Option A: release the consignment and ship on schedule, relying on the seven clean samples and the compliant blending records. Option B: hold the consignment for Thursday's independent retest, miss the vessel, and absorb the penalty and the review.
16. Option A protects the contract, the cash position, jobs, and the reliability promise made to the buyer; it risks seizure and destruction at an EU port, a public alert, damage to the sector, and the betrayal of her safety pledge. Option B protects the safety pledge and removes the seizure risk; it costs €85,000, invites a contract review, delays revenue twelve days, strains cash before the farmer payments, and may read as unreliability to the buyer.

## The finished case (fictional example)

> **The Consignment**
>
> The laboratory report reached Efua Mensah early on Monday, and its numbers did not soften with rereading. Three of the ten samples drawn from Friday's production of peanut paste had tested above the European Union's limit for total aflatoxin — six, seven and nine parts per billion, against a ceiling of four. Seven samples were clean. All of it came from the same consignment: two hundred and forty tonnes, packed and waiting at the plant outside Accra, booked onto a vessel whose loading gate at the port of Tema would close at seven o'clock on Tuesday evening.
>
> Mensah was chief executive of Ashanti Harvest Foods, a processor founded in 2009 that employed four hundred and twenty people. The consignment was the first quarterly shipment under the largest contract in the company's history: €2.4 million a year supplying Van Doren Distribution of Rotterdam — roughly sixty per cent of the company's export revenue. The contract had taken two years of audits and sample shipments to win, and Mensah knew exactly why the previous supplier had lost it. During the final negotiation, Van Doren's head of procurement had told her that missed delivery windows were the reason for the switch. Reliability, he said, was the product.
>
> There was also a sentence she could not take back. A year earlier, when a rival, Volta Groundnut, collapsed after a contaminated shipment was seized in Hamburg, Mensah had told an industry forum there would be "zero compromise on safety, whatever it costs." Inside the company the line was remembered. So, she assumed, was it outside.
>
> The evidence itself refused to point one way. The three failed samples traced back to two lots from a growing region that had suffered unseasonal rain in February — a plausible path for contamination. Yet the line had run normally, the lots had passed intake sorting, and the blending records put the consignment's aggregate below three parts per billion, comfortably inside the limit. Ten samples could not settle whether the company was looking at a dangerous hot spot or at noise. An independent, accredited laboratory could — and its retest of the consignment had already been commissioned. The results would arrive on Thursday morning. The gate at Tema closed on Tuesday evening.
>
> The arithmetic of waiting was unforgiving. Missing the vessel triggered an eighty-five-thousand-euro late-delivery penalty and, more dangerously, a clause allowing Van Doren to review the contract. The next vessel with space sailed twelve days later. Ashanti Harvest was holding about eleven weeks of operating cash, and payments to the farmer cooperatives that supplied it fell due the following month. Twelve days of delayed revenue was not an abstraction; it was a queue of people who had already been promised their money.
>
> By Monday evening her two most senior officers had read the same numbers and reached opposite conclusions. The quality director wanted the containers held. If a European port laboratory drew its own samples and found what the internal laboratory had found, the consignment would be destroyed at the company's cost and a public alert posted in the European Union's food-safety system — the kind of alert that could tighten controls on every Ghanaian groundnut exporter, not just one. Volta Groundnut had not survived its seizure.
>
> The commercial director read the same facts the other way. Border testing caught only a fraction of consignments. Seven samples in ten were clean, the aggregate was compliant, and the paperwork showed a company that had tested, blended and documented exactly as required. Against an uncertain risk stood certain costs: the penalty, the review clause, and twelve days of silence on the first delivery to a buyer that had already left one supplier for unreliability.
>
> Tuesday compressed. The workforce knew the run had been flagged — supervisors were asking whether Friday's production had been cleared, and there was no answer to give that did not commit her. The board oversaw the company, but this decision required no approval. It was hers alone.
>
> By mid-afternoon the freight forwarder needed the release order in time to make the gate. On one side lay a shipment that every record in her possession declared compliant, a contract that carried the company, and the reliability the buyer had made the ground of the deal. On the other lay three numbers her own laboratory had produced, a promise about safety she had made in public, and a retest that would tell her the truth twelve hours too late.
>
> Efua Mensah picked up the phone. The gate closed at seven.

## What the source check looks like (excerpt)

| Fact in the case | Where it comes from |
|---|---|
| Three of ten samples at 6, 7, 9 ppb vs limit of 4 | Article, paragraph 3 |
| €2.4 million a year, ~60% of export revenue | Article, paragraph 2 |
| "Zero compromise on safety, whatever it costs" | Article, paragraph 5 |
| Report reaching Mensah on Monday morning | **Staging** — consistent with the sources, not documented in them |

---

## Share your case back

If this kit gives you a case that worked in your classroom, consider contributing it — the article link, your worksheet answers, and the final case — to the shared OBSD case bank, so another educator somewhere else can teach it tomorrow. Contribute at **github.com/NegoAI/obsd-case-writing-kit**: open a pull request adding a folder under `cases/`, or open an issue with your files attached. See `cases/README.md` there for the simple format.

---

*This kit is a public good. Share it, translate it, adapt it — keep the method credited to its authors.*
