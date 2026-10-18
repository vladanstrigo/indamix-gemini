# In Da Mix for Gemini CLI

A [Gemini CLI](https://github.com/google-gemini/gemini-cli) extension that connects the
**In Da Mix** gas blending calculator for scuba divers: nitrox, trimix, heliair and heliox fill
plans, gas usage from banks, how many fills your banks give, top-ups, best mix and MOD.

It uses the public In Da Mix server (`https://indamix.divingtechnics.com/mcp`, no account, no
API key) with the same engine as the In Da Mix app.

## Install

```
gemini extensions install https://github.com/vladanstrigo/indamix-gemini
```

Then ask, for example:

- How many 12 L tanks can I fill with NX32 to 200 bar from my 50 L oxygen bank at 180 bar?
- How do I blend trimix 18/45 to 220 bar into an empty tank?
- What's the best nitrox for 30 m?

## Notes

- A calculation aid only: a gas is what the analyser says it is. Analyse every gas before use.
- Privacy: https://indamix.divingtechnics.com/privacy · Terms: https://indamix.divingtechnics.com/terms
- Other assistants (ChatGPT, Claude, Cursor, VS Code): https://indamix.divingtechnics.com/ai

© Diving Technics
