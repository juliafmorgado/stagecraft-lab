---
title: Worked example
---

# Worked example

One talk, taken through every template in the lab, so you can see what a finished worksheet looks like.

> **Alex is fictional.** So are the company, the numbers, and the talk. They're here to show the shape, not to be copied.
{: .rule}

## Alex

Alex is a backend engineer who's been on an on-call rotation for a year. Their team got paged so often that two people asked to leave the rotation. They fixed it, and their manager suggested they submit a talk to a local meetup.

## Topic

> How we cut on-call pages from 412 a month to 30 without missing real incidents.
{: .card data-label="Overview · topic"}

## 01 · Imposter syndrome

**Stem:** "The thing I'm afraid someone will notice is that I'm not an alerting expert. Someone in the front row will know Prometheus better than me and ask something I can't answer."

> I'm not [an alerting expert], but I am [the person who got paged 412 times in one month], and the room needs that because [most of them are getting paged too much and think it's normal].
{: .card data-label="Alex's reframe"}

## 02 · Your talk

> This talk is about [alert fatigue] for [backend engineers who've just joined an on-call rotation] so that when they leave, they can [delete the alerts nobody acts on without losing the ones that matter].
{: .card data-label="Alex's sentence"}

The verb is **delete**. The first draft said "understand alert fatigue," which failed the verb rule.

## 03 · Story arc

**Frame:** The Architecture Shift. Alex changed how alerting works on their team.

> 1. **Manual pain.** 412 pages in March. Two engineers asked to leave the rotation. One night, a real outage was page number 38, and nobody looked at it for 40 minutes. *Stakes: losing people, and missing the real incident.*
> 2. **Discovery.** We raised every threshold. Fewer pages, but we missed a disk filling up (first attempt fails). Then we found nobody owned half the alerts (complication). So for two weeks, every page got tagged "did anyone do anything?" 81% were no (the turn).
> 3. **New stack.** Page only on user-facing symptoms, using SLO burn rate. Cause-based alerts moved to a dashboard we review weekly. *Cost:* two weeks of work, and we lost some early warning on disk space. *What we'd do differently:* start with the tagging, not the thresholds.
{: .card data-label="Alex's three boxes"}

**Climax line:** "For 81% of our pages, nobody did anything. We weren't on call. We were on notification duty."

**Flat-line check:** All boxes pass. The first draft skipped the failed threshold change because it was embarrassing. Putting it back in created tension point 2, and gave the turn something to pay off.

## 04 · Opening

**Hook pattern:** a real number.

> [Four hundred and twelve. That's how many times we got paged in March.] [I'm Alex, and I was on the receiving end of about half of those.] [In the next 25 minutes, I'll show you how we got that down to 30, and how you can find the alerts to delete in your own rotation by Friday.]
{: .card data-label="Alex's 60-second opening"}

That's about 20 seconds out loud. Plenty of room for a pause after the number.

**Closing line (callback):** "Four hundred and twelve pages in March. Thirty last month. And every one of them meant something."

## 05 · Nerves

**Ritual:** Check the mic. Three fist clenches. Two rounds of box breathing. Say: "Half of them got paged last night too."

## 06 · Voice and body

Alex tried the climax line all three ways. The **3-second pause** before "We weren't on call" worked best. They walk from home base to the X during the slide transition, plant, pause, and say it to the center zone.

## 07 · Hot seat

Alex went for rung 3, standing on the X.

> **One thing that worked:** "When you said 412 and then stopped, I wanted to know what happened."
>
> **One thing to try:** "Next time, try saying your name after the number, not before. You started with 'Hi, I'm Alex' out of habit."
{: .card data-label="Feedback Alex got"}

Take two started with the number.

## 08 · Take it home

> At my next talk, I will [pause for three full seconds before the 81% slide, and count it in my head].
{: .card data-label="Alex's commitment"}
