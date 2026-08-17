# demo-1

A 19-shot film made in [Reelix Studio](https://github.com/reelixstudio/reelix-studio).

**This repo is the thinking, not the footage.** About 23 MB — the world rules, the shot
list, the approved reference picture for every character and location, and the log of what
was decided and why. That's the part you can learn from. You cannot get *"why the palette
changed at scene 4"* from watching a finished film.

## Watch it

`_review/cut.mp4` — the finished cut at 720p.

## Read how it was built

| File | What's in it |
|---|---|
| `dna.json` | The world: setting, rules, characters, and the camera grammar — lens set, movement vocabulary, what the film refuses to do |
| `spine.json` | Every scene and shot: framing, length, voiceover, and which elements are in frame |
| `elements.json` | The element registry — one blessed reference image per character, prop and location |
| `bible.json` · `cut.json` | The story bible and the timeline |
| `assets.json` | Where the raw footage lives, and its public URL |

## The footage

117 clips, 494 MB. Too big for a repo, so it lives in object storage — `assets.json` has a
direct URL for every one. Downloads are free; you can watch any shot without cloning
anything.

## Open it in Studio

```bash
git clone https://github.com/reelixstudio/demo-1 projects/demo-1
```

from inside a Reelix Studio checkout, then open the project. Or point an agent at it and
ask why a shot was built the way it was — the reasoning is in the files.
