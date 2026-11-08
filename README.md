# edge-gallery-skills

Custom Agent Skills for [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery/tree/main/skills).

## Skills

| Skill | Type | Description |
|---|---|---|
| [nanobanana-prompt-generator](nanobanana-prompt-generator) | Text only | Turns an idea (in any language) into a structured English JSON prompt for NanoBanana Pro / NanoBanana 2. Defaults to 16:9. |

## Load in the app

1. Open **Agent Skills**, pick a model, tap the **Skills** chip.
2. Tap **(+)** → **Load skill from URL**.
3. Paste the skill folder URL:

```
https://raw.githubusercontent.com/mikailerdembicici/edge-gallery-skills/main/nanobanana-prompt-generator
```

Check: the same URL + `/SKILL.md` should show the raw file in a browser.
