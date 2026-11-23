# Claude Design prompt: "Before the Group Chat" pitch deck

Paste everything below the line into Claude Design. This is the original spec; [`pitch-deck.html`](../pitch/deck.html) has since been revised (9 slides, Poppins, no small text), so use the deck as the reference if they differ.

---

Build an 8-slide, 16:9 presentation deck for a 6.5-minute student pitch. It proposes a 60-minute workshop called **Before the Group Chat**, which teaches first-year engineering and IT students at the University of Queensland (UQ) to lead a group's first meeting.

The deck is presented live, so every animation step advances **on click**. Keep text on slides minimal, because the speaker carries the story. Each slide is driven by one simple line-drawn figure or diagram that shows what happens in the workshop and how it runs.

## Design system

- **Background:** warm beige `#F4EFE6` on every slide. No gradients, textures or photos.
- **Text:** ink `#1C1B19` for primary text, warm grey `#8A857C` for secondary text and captions.
- **Accent:** one colour only, terracotta `#C8553D`. Use it sparingly: Round 2 data, the key number on a slide, and the one highlighted element per slide. Nothing else is coloured.
- **Type:** Poppins (or Montserrat) for everything: semibold 64–84pt headlines, regular 26–34pt body. Nothing on a slide is smaller than 22pt. Headlines are sentence case, and each slide has one headline at most. No footer and no section labels.
- **Figures:** hand-drawn-feeling line illustrations with a single 2px ink stroke, rounded caps and no fills, except for the accent highlight. People are simple dots or minimal stick-figure outlines. No stock photos, clip art or emoji. Use line icons instead.
- **Layout:** generous whitespace with a 10% margin on all sides. Content sits left or centre. No logos, except a small "EAIT · Group 14" in grey in the bottom-left corner.
- **Motion:** calm and editorial.
  - Fade-up of 12px over 450ms with ease-out.
  - Line figures *draw on* along their strokes.
  - Numbers *count up*.
  - No bounce, spin, zoom-blur or flying-in from off-screen.
  - Each click triggers one idea.
- **Exporting to PowerPoint:** keep the animations to Fade, Wipe and Morph equivalents so they survive the export.

## Slides

### 1. "The chat that died"
- **Figure:** a phone outline, centred, showing a group chat UI drawn in line style with grey message bubbles.
- **Builds:**
  1. Messages appear one by one, each preceded by a 3-dot typing indicator: "hey team 👋" → "hi!" → "let's make a group chat" → "👍".
  2. A small grey label above the phone ticks "Week 1" → "Week 4" → "Week 7". Nothing new arrives in the chat, and "Seen by 4" fades in under the last message.
  3. The label flips to "Week 8" and one message drops in alone, in accent colour: "is anyone working on this?? due friday".
  4. The phone glides to the left third. Headline writes on at the right: **"Teams don't fail in week 8. They fail in week 1."**

### 2. "12 first meetings"
- **Figure:** a minimal line-drawn student figure on the left, labelled "First-year EAIT · O-Week". A thin horizontal timeline extends to the right.
- **Builds:**
  1. The figure draws on.
  2. Twelve small door icons pop onto the timeline one after another (stagger 120ms), each with a tiny grey label: "ENGG1100 team", "COMP1100 team", "DECO1800 team", "Society committee", "Study group", "Hackathon team", plus six unlabelled doors.
  3. A large accent counter in the top-right counts 0 → 12, with the caption "first meetings in year one".
  4. Bottom line fades up: **"No habits yet, good or bad. Nobody teaches this."**

### 3. "Strangers → agreement in 12 minutes"
- **Top half:**
  1. Five scattered dots drift together into a circle, then a small document icon draws on in the centre.
  2. Headline: **"Lead a group's first meeting: strangers to a written agreement in 12 minutes."**
  3. Subtitle in grey: "You don't need a title to lead. You need to start the meeting properly."
- **Bottom half:** three equal cards with thin ink outlines, rising in one per click. Each has a big accent number that counts up, one sentence, and a grey tag:
  - **8/10** · "Every group's Round 2 agreement covers 8 of 10 checklist items, up from Round 1." · *Group · end of hour*
  - **2 of 3** · "Every player makes 2 of the 3 leader moves in Round 2." · *Individual · end of hour*
  - **50%** · "Half of follow-up respondents led a real first meeting using the template." · *Lasting · 4 weeks*

### 4. "The hour"
- **Top:** a full-width 60-minute timeline bar that draws left to right in proportional segments, each labelled as it appears:
  - Hook 5
  - Round 1: cold 15
  - Reveal 10
  - Teach 8
  - Round 2: new group 14
  - Score + pledge 8

  Every segment fills solid ink at low opacity except **Teach**, which stays outlined. Then a bracket over the filled segments: **"52 of 60 minutes doing, not listening."** Beside the bar, a small circular arrow diagram: "Cold → Reveal → Teach → Again", with "Pledge" exiting the loop.
- **Bottom:** a top-down room map.
  - Five round tables, each ringed by 6 seat dots: 5 filled (players) and 1 hollow ring (observer). Legend in grey.
  - A small "A" marker at the front beside a screen rectangle.
  - A "B" marker that moves slowly along a dotted path looping between the tables, continuously.
- **Final build:** Table 1's grey label cross-fades from "Course team" to "Club committee" in accent, with the caption **"Round 2 uses a different kind of group, to show the skill transfers."**

### 5. "Play a card"
- **Builds:**
  1. A playing-card-sized role card, centred and face down, with a fine line-pattern back.
  2. The card does a 3D flip to its front. Front: small grey "ROLE CARD", bold title **"The Quiet One"**, and the body "You have good ideas but only speak when someone asks you directly."
  3. The card shrinks and slides to the left third. On the right, three speech bubbles fade up one per click, each with a small tag underneath (bold move · grey italic inner skill):
     - "Can we spend 10 minutes agreeing how this'll work?" → **Open the meeting** · *Self mastery*
     - "We haven't heard from you yet. What works for you?" → **Draw in a quiet voice** · *Empathy* (highlight this bubble in accent; it's the move just modelled live)
     - "Sounds like some want a 7 and some want a pass. Let's sort it now." → **Name the tension** · *Emotional awareness*
  4. Footer line fades up in grey: "Resilience: do it badly in Round 1, then do it again."

### 6. "3 → 9"
- **Left:** a minimal bar chart, five pairs of vertical bars labelled "Table 1–5", with no gridlines and a single y-axis from 0 to 10.
  - Round 1 bars are outlined in ink and grow first, to low values (3, 4, 2, 5, 3).
  - Round 2 bars are solid accent and grow second (9, 8, 8, 9, 8), past a dashed horizontal line labelled "8/10 target".
  - Then Table 1's pair gets a large label: **"3 → 9"**.
  - A small grey tag in the corner reads "Illustrative, pilot pending" *(this is editable)*.
- **Right:** two paper artefacts with a slight drop shadow, as the only depth on the deck.
  1. A "Scoring checklist" sheet with 10 tick boxes that tick themselves one by one in accent.
  2. An "Exit card" showing "Confidence to lead a first meeting: Before ①②③④⑤ / Now ①②③④⑤", with ② circled for Before and ④ for Now.
- **Bottom:** a thin timeline "Today ──── Week 4 follow-up".

### 7. "$95 and a tutorial room"
- **Left:** a narrow paper receipt that prints downward line by line, in a monospaced font:
  - Printing ........ $20
  - Card stock ...... $10
  - Snacks .......... $40
  - Follow-up prize . $25
  - Mentimeter, Forms, room ... $0

  Then a rule, and **TOTAL $95**, with the total in accent.
- **Right:** three rows that fade up, each with a line icon:
  - two-person icon · **2 EAIT Ambassadors** · "briefed in 30 minutes"
  - door icon · **Any tutorial room** · "5 tables"
  - calendar icon · **Week 1 × 3 sessions** · "promoted via ENGG1100, COMP1100, DECO1800"

### 8. "Be the one who starts it"
- **Builds:**
  1. A single business-card-shaped pledge card, centred. Three lines *handwrite themselves* onto it in a handwriting-style font, with blanks underlined:
     - "In my next first meeting, I'll open by ______"
     - "I'll make sure ______ gets heard"
     - "When I sense tension, I'll say ______"
  2. The card shrinks and moves up. The title fades in large and centred: **"Before the Group Chat"**, with grey "Be the one who starts it." underneath.

## Speaker notes

Add these to each slide's notes:
1. "Every one of us has been in this chat. By week 8 it's too late. We think the fix is the first 12 minutes."
2. "First-year EAIT students in O-Week. About a dozen first meetings ahead in year one, and no habits yet."
3. "Narrow on purpose: lead one first meeting well. Measured three ways: group, individual, four weeks later."
4. "Thirty students, five tables, two Ambassadors. Cold round, reveal, teach, then a different kind of group."
5. "[Hand a judge the Quiet One card, then model:] 'We haven't heard from you yet. What works for you?' That's one of three moves."
6. "Everything is measured in the room. Some gain is from repetition, which is why Round 2 changes context."
7. "Ninety-five dollars, two Ambassadors, one tutorial room, week 1."
8. "You don't need a title to lead. You just need to be the one who starts it. Thank you."
