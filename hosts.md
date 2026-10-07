---
title: For hosts
---

# For hosts

Everything you need to run the lab: the script, what to cut when you're behind, what to do when nobody volunteers, and how to set up the room.

## Before the day

- [ ] Set `hook_wall_url` in `_config.yml` to your anonymous wall (see [below](#anonymous-hook-wall)). Optionally set `discussion_url` to a GitHub Discussions thread and change `hashtag`.
- [ ] Turn on GitHub Pages: **Settings → Pages → Source: GitHub Actions**. Every push to `main` republishes the site.
- [ ] Make a slide with a QR code to the site and another to the hook wall.
- [ ] Decide who leads which segment. Two hosts work well: one leads, one watches the clock and the room.
- [ ] Each host prepares a 30-second imposter story (prompts [below](#host-story-prompts)) and runs through the flawed opening once.

## Room setup

- **Tape an X** on the floor at the front, center stage, about two steps from the front row. Tape a second one in the aisle if the room is big.
- **QR code on screen** as people walk in, so they open the site before you start.
- **Shared timer** that everyone can see: a big countdown on the projector or a phone on a stand. Participants relax when they can see how long an exercise lasts.
- **Seat people next to someone.** Every segment has a neighbor exercise. Close gaps, and move people sitting alone.
- **Index cards and pens** for anyone without a phone, or who'd rather write.
- **A mic for volunteers**, if the room needs one. A handheld that gets passed is fine.

## Minute-by-minute

| Clock | Segment | What you do |
|---|---|---|
| 0:00 | **Overview** · 3 min | Welcome. One-line promise: "You'll leave with a 60-second opening you've already said out loud." Show the QR. Ask everyone to pick a topic now. |
| 0:03 | **01 Imposter** · 7 min | Host stories (1 min). Neighbor stems (2 min). Reframe writing (2 min). Everyone reads their reframe at once on "three" (1 min). 3 solo volunteers (1 min). |
| 0:10 | **02 Your talk** · 5 min | Who's in the room (1 min). Write the sentence (2 min). Read to neighbor, neighbor names the verb (1 min). 3 volunteers (1 min). Call out any "understand." |
| 0:15 | **03 Story arc** · 8 min | Read the frame picker aloud (1 min). Fill three boxes (4 min, timer on screen). Explain the tension curve while they write. Flat-line check (2 min). Neighbor share (1 min). |
| 0:23 | **04 Opening** · 8 min | Walk through 2 or 3 hooks (1 min). Write hook (1 min). Write 60-second opening, then whisper-time it (3 min). Closing line (1 min). Hook wall (2 min): read 5 or 6 aloud with one kind comment each. |
| 0:31 | **05 Nerves** · 7 min | Backstage checklist, quickly (1 min). **Lead the room** through fist clench, 4 rounds of box breathing (count out loud), anchor phrase (3 min). Write ritual (1 min). On-stage recovery (1 min). Anchor phrase all at once (1 min). |
| 0:38 | **06 Voice & body** · 8 min | Three micro-drills on the climax line (3 min). Stage map, demo it yourself on the tape X (3 min). Everyone stands for the body checklist (1 min). Everyone says the climax line standing (1 min). |
| 0:46 | **07 Hot seat** · 11 min | Explain rungs and feedback rule (1 min). Hook round (3 min). 2 or 3 volunteers, 60 s + feedback + take two (6 min). Name what improved (1 min). |
| 0:57 | **08 Take it home** · 3 min | Commitment card (1 min). Tell them to copy their sheet. Point at the hashtag. End on a line, then thank them. |

## The cut line

If you hit **0:31 and you're still in Segment 04**, you're behind. Cut in this order:

1. **05:** skip writing the ritual. Do the breathing together, then move on. Ritual becomes homework.
2. **06:** skip the body checklist. Keep the micro-drills and the stage map.
3. **03:** shorten the flat-line check to the first two boxes.
4. **07:** one volunteer instead of three. **Keep the hook round.** It's the one moment everyone speaks to the full room.

**Never cut:** the Segment 02 sentence, the 60-second opening, the hook wall, and the hook round. Those are the outcomes you promised.

## Host story prompts

Pick one. True, short, and ending with what you did anyway. Aim for 30 seconds.

- The first talk you gave, and what you were sure would go wrong.
- A time you almost withdrew a talk, or did.
- A question from the audience that you couldn't answer, and what happened next.
- The moment you realized the "experts" in the room were as nervous as you.
- Something you still do before every talk, even now.

End with a line that hands it to the room: "So if you're thinking 'who am I to give a talk?', you're in good company. Let's write that down."

## If nobody volunteers: the flawed opening

If the hot seat goes quiet for more than five seconds, a host stands on the X and delivers a deliberately bad opening:

> "Hi, um, so, my name is ___ and I work at ___. Sorry, I'm a bit nervous, I put this together last night. So here's the agenda. First I'll talk a bit about me, then some background on alerting, then..."
{: .card data-label="Flawed opening script"}

Then ask the room: **"What should I fix?"** Take three answers. They'll name the name-first opening, the apology, and the agenda. Then do take two using the 60-second formula with a real hook.

The room has now coached someone, and the bar for volunteering is low. Ask again: "Who wants to try theirs?" Someone usually does. If still nobody, run the hook round with everyone reading to a neighbor.

## Anonymous hook wall

The goal: everyone submits their hook, nobody's name is attached, and you can read a few aloud.

Use any tool that allows **anonymous, no-login, open-text** responses:

- **Slido or Mentimeter:** an open-text question with participant names off. Turn moderation on so you choose which ones to read.
- **A Google Form or Microsoft Form:** one short-answer question, "collect emails" off. Read from the responses tab.

Put the link in `hook_wall_url` in `_config.yml`, and the QR on a slide. When you read hooks aloud, say one specific thing that works about each ("That number is great, I want to know what happened") and never read one to criticize it.

> Test the wall from a phone on mobile data before the session. Conference wifi will block or slow it down. If it fails on the day, see [If you're stuck](if-youre-stuck.md#the-wifi-is-down).
{: .tip}

## Running it again

- Change the [worked example](examples.md) to match your audience if they aren't engineers.
- The footer credit comes from `credit` in `_config.yml`. Keep it when you reuse the frameworks.
