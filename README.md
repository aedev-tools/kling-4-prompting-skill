# Kling 4.0 Prompting Skills

**Another model, another skill.**

Tell your AI assistant what you want to film. Get a Kling 4 prompt you can copy and use.

```bash
npx skills add aedev-tools/kling-4-prompting-skill
```

Then ask:

> Use kling-4-prompting. Animate this photo: the dog notices a tennis ball, looks at me, then looks back at the ball. Keep the camera still.

Your agent turns the idea into a shot:

```text
Start from the supplied photo. The dog looks down at the tennis ball,
then raises its eyes toward the camera. After a short pause, it looks
back at the ball and leans forward slightly. The camera stays fixed
at the dog's eye level throughout. Soft room tone and a quiet collar
jingle. No background music or subtitles.
```

That's the basic loop. Describe it, refine it if you want, paste it into Kling.

## What is a skill?

A small set of instructions your AI assistant can read. This one helps it turn your ideas into video direction: what happens, how the camera behaves, and what should stay consistent.

You keep the creative decisions. Your agent handles the prompt structure. If something important is missing, it asks a short question. If you've already given enough detail, it writes the prompt.

The skill writes prompts. You generate the video in Kling or your preferred provider. The skill is free; your assistant and video generation service may have their own costs.

## Try these

- **Start with an idea:** "A tiny robot opens a bakery for the first time. Warm morning light. One continuous shot."
- **Use your references:** "Photo one is the person, photo two is the room. Have them walk to the window."
- **Plan a sequence:** "A 12-second coffee ad in three shots. Close on the beans, pour the coffee, finish on the cup."
- **Edit footage:** "Replace the jacket in this video. Keep the person, action, and framing."
- **Fix a prompt:** "The camera keeps circling. I want it to stay in place while the subject turns."

## Use it with your agent

The installer lets you choose a supported agent, including Claude Code, Codex, or Cursor. Restart the agent session if the skill doesn't appear immediately.

Prefer to skip installation? Open [the skill](skills/kling-4-prompting/SKILL.md), give its contents to your assistant, and ask it to use those instructions. You can also read the [examples](skills/kling-4-prompting/references/examples.md) yourself.

## What the agent handles

| You bring | The skill helps with |
| --- | --- |
| A scene idea | Action, framing, light, and sound |
| Photos or videos | Giving each reference a clear job |
| Several shots | Shot order, timing, and continuity |
| Start, middle, or end images | Planning the movement between keyframes |
| Existing footage | Defining the edit and what to preserve |
| An unwanted result | A focused revision you can compare |

The detailed instructions live [inside the skill](skills/kling-4-prompting/SKILL.md), with separate notes for [references and editing](skills/kling-4-prompting/references/references-and-editing.md), [shots and keyframes](skills/kling-4-prompting/references/shots-and-keyframes.md), and [sources](skills/kling-4-prompting/references/sources.md).

## About this version

Built with AI assistance, directed and maintained by [Michael Nahmias / aedev.tools](https://aedev.tools). It follows our [Kling 3 skill](https://github.com/aedev-tools/kling-3-prompting-skill), with a separate set of instructions for Kling 4.

Based on [Kling's 4.0 user guide](https://kling.ai/quickstart/kling-4-model-user-guide), reviewed October 16, 2026. Features vary by model, mode, and provider. Examples here are original teaching prompts, not clips we've generated or benchmarked. Independent of Kling AI.

Got a prompt that goes sideways? [Open an issue](https://github.com/aedev-tools/kling-4-prompting-skill/issues) with the prompt, selected model and mode, and what happened. Remove private media or details before sharing.

MIT licensed. Read it, adapt it, make it useful for your own workflow.
