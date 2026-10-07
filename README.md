# Stagecraft Lab

A 60-minute speaking and storytelling workshop for technical people, published as a static site on GitHub Pages.

Participants leave with a fresh perspective, a story arc for their talk, and a polished 60-second hook.

## Segments

| | Segment | Time |
|---|---|---|
| 00 | [Overview](index.md) | 3 min |
| 01 | [Imposter syndrome](01-imposter-syndrome.md) | 7 min |
| 02 | [Your talk](02-your-talk.md) | 5 min |
| 03 | [The story arc](03-story-arc.md) | 8 min |
| 04 | [The opening](04-opening.md) | 8 min |
| 05 | [Nerves](05-nerves.md) | 7 min |
| 06 | [Voice and body](06-voice-body.md) | 8 min |
| 07 | [Hot seat](07-hot-seat.md) | 11 min |
| 08 | [Take it home](08-take-it-home.md) | 3 min |

Reference: [Worked example](examples.md) · [If you're stuck](if-youre-stuck.md) · [For hosts](hosts.md)

## Running it

1. **Settings → Pages → Source: GitHub Actions.** The workflow in `.github/workflows/pages.yml` publishes on every push to `main`.
2. Set `hook_wall_url`, and optionally `discussion_url` and `hashtag`, in `_config.yml`.
3. Read [For hosts](hosts.md).

## Editing

Pages are plain Markdown. A few conventions:

- **Template cards:** a blockquote followed by `{: .card data-label="Template card"}`. Inside a card, `[placeholder]` renders as a highlighted blank and `___` as an empty line.
- **Callouts:** `{: .rule}`, `{: .tip}`, `{: .host}` after a blockquote.
- **Card grids:** `{: .grid}` after a list. **Numbered steps:** `{: .steps}` after an ordered list.
- **Fill-in boxes:** `{% include field.html id="hook" %}`. Field ids and labels live in `_data/fields.yml`, which also drives the summary sheet on *Take it home*. Answers are stored in the participant's browser (`localStorage`) and never leave it.
- **Share prompts:** `{% include share.html prompt="..." how="..." %}`.
- **Diagrams:** `_includes/tension-curve.svg` and `_includes/stage-map.svg` are inline SVG and follow the light/dark theme.

Preview locally with Docker:

```bash
docker run --rm -p 4000:4000 -v "$PWD":/srv/jekyll -w /srv/jekyll ruby:3.3 \
  sh -c "gem install github-pages webrick && jekyll serve -H 0.0.0.0"
```

---

Frameworks developed by Julia Furst Morgado & Abdel Sghiouar.
