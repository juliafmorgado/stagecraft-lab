---
title: The story arc
---

# The story arc

Most technical talks fail for the same reason. They're just a list of accurate facts in sensible order—where nothing is at stake. A story arc gives people a reason to actually want the next slide.

Don't invent drama. Engineering work is built on story: something was broken, you ran experiments, and something finally clicked. Choose the frame that matches your work.

## Pick your frame · 1 min

> - **You fixed something:** The Incident
> - **You changed how something works:** The Architecture Shift
> - **You built something:** The Build Story
> - **You're explaining something:** The Zoom Lens
> - **You're correcting a belief:** Myth vs Reality
> - **You're teaching by doing:** The Demo Arc
{: .card data-label="Which one are you?"}

- **The Incident** <span class="arc">Broken world → investigation → fix.</span> Use it when you fixed something that broke.
- **The Architecture Shift** <span class="arc">Manual pain → discovery → new stack.</span> Use it when you changed how a system works. Put the trade-offs in the last box. Technical audiences trust you more when you name what it cost.
- **The Build Story** <span class="arc">The goal → the dead ends → what finally worked.</span> Use it for a project built over months. Add "what we'd do differently" to the last box.
- **The Zoom Lens** <span class="arc">Why it matters → how it works (simple first, then one layer deeper) → where it breaks.</span> Use it to explain a tool or a concept.
- **Myth vs Reality** <span class="arc">What everyone believes → why it fails → what to do instead.</span> Use it to correct a common belief.
- **The Demo Arc** <span class="arc">Promise → show it → break it on purpose → fix it → recap.</span> Use it for live demos. It has five beats, so fold them into three boxes: promise / show and break / fix and recap.
{: .grid}

{% include field.html id="frame" rows=1 placeholder="e.g. The Incident" %}

## Fill your three boxes · 4 min

Write one or two lines per box. Bullet points are fine.

> Box 1 must name the **stakes**: what was at risk if nothing changed. Money, sleep, customers, a deadline, someone's job. If nothing was at risk, the audience has no reason to care how it ends.
{: .rule}

{% include field.html id="box1" rows=3 placeholder="The broken world / the pain / the goal / the myth. What was at risk?" %}

{% include field.html id="box2" rows=3 placeholder="The investigation / the discovery / the dead ends. What didn't work first?" %}

{% include field.html id="box3" rows=3 placeholder="The fix / the new stack / what worked. What did it cost? What would you do differently?" %}

## The tension curve

Your three boxes aren't flat. Tension should start high, dip while you explain the setup, then climb in steps until the one slide that pays it all off.

{% include tension-curve.svg %}

1. **Stakes.** What goes wrong if nothing changes. *(End of box 1.)*
2. **The first attempt fails.** The obvious fix didn't work, or made it worse. *(Box 2.)*
3. **The complication.** A constraint, a surprise, a second problem hiding behind the first. *(Box 2.)*
4. **The turn.** The insight, the clue, the moment it clicked. *(End of box 2.)*
{: .steps}

**The climax slide** is the payoff: the graph that drops, the one-line fix, the before and after. It's the slide people take a photo of. Then ease off for a moment and **finish rising**, on your takeaway, not on a summary.

{% include field.html id="climax" rows=2 label="My climax line" placeholder="The one sentence you'd say over your climax slide." %}

## Flat-line check · 2 min

Read your boxes back and answer honestly. Every "no" is a place where the room's attention will drop.

- [ ] Box 1 says what was at risk if nothing changed.
- [ ] Something doesn't work at least once before it works.
- [ ] Each tension point is bigger than the one before it.
- [ ] There's one slide someone would photograph. I know which one.
- [ ] I could not cut a box without the story breaking.
- [ ] The last box ends on my takeaway verb from Segment 02, not on "In summary."
- [ ] *(Architecture Shift and Build Story)* I named what it cost or what I'd change.

{% include share.html prompt="Tell your neighbor your frame and your stakes in one breath." how="“It’s an Incident talk, and if we hadn’t fixed it, we’d have lost ___.” Then hosts take 3 volunteers to share with the room." %}
