---
name: kling-4-prompting
description: Write, revise, or troubleshoot Kling 4.0 video prompts from scene ideas, images, video references, storyboards, or keyframes. Use for prompt writing and shot planning; does not generate videos.
metadata:
  author: aedev-tools
  version: "1.0.0"
---

# Kling 4 prompting

Translate the user's creative intent into a ready-to-use video prompt. Keep simple requests simple. Preserve their subject, supplied assets, sequence, spoken words, language, and deliberate visual choices.

## Start with the brief

Use information already supplied. Ask a focused question only when the answer changes the result materially, such as which person to replace or which image is the endpoint. Infer ordinary creative choices and mention material assumptions outside the prompt. Do not run a compulsory questionnaire.

Separate prompt wording from interface settings. Confirm the selected model, mode, and available controls when a request depends on them. Full 4.0 capabilities do not establish Flash or third-party availability. For changing specifications, use [sources](references/sources.md).

## Select only the detail you need

- For references or a footage edit, read [references and editing](references/references-and-editing.md).
- For multiple shots or keyframes, read [shots and keyframes](references/shots-and-keyframes.md).
- For illustrative prompts or a failed result, read the relevant section of [examples](references/examples.md).

Do not load every reference for an ordinary single-shot request.

## Direct the shot

Describe visible behavior that can unfold in the requested time. Use a clear subject, an action, and an intelligible camera position. Add setting, lighting, texture, and audio where they help the requested result. Avoid padding every scene with film-stock names, arbitrary lens specifications, or unrelated mood adjectives.

For an existing image, spend the prompt on what changes. For a scene from scratch, establish the appearance and location first. Tie camera direction to the action. A fixed camera can watch a turning subject; an orbit moves the viewpoint. These are different instructions.

For speech, identify the speaker, preserve the exact requested words and language, and give space for pauses and reactions. If the lines cannot reasonably fit, offer a shorter script or longer clip without silently rewriting the dialogue. Distinguish ambient sound from music; silence can be intentional.

## Check before returning

Check the brief against the draft:

- Can the described actions fit the available time?
- Does the camera receive incompatible directions at the same moment?
- Do reference roles conflict with the requested change?
- Is the prompt asking to preserve something it also replaces?
- Are all asset labels backed by supplied media and confirmed ordering?
- Are suggested settings actually available, or clearly conditional?

For a failed result, change the instruction most closely related to the failure first. Explain the revision briefly. Prompt wording cannot guarantee exact identity, text, timing, or motion.

## Return the result

Lead with one copyable prompt in a fenced text block. Follow with only necessary reference assignments, settings, or assumptions. Label an illustrative asset mapping as such; unresolved labels are not a finished runnable prompt.

Match the user's requested prompt language. Keep dialogue in its requested language even if the surrounding direction uses another language. Offer alternatives when requested or when a real creative fork needs a choice.

Write prompts only unless the user separately requests generation. Do not invent tests, generated clips, benchmark scores, or credit savings. Suggestions here are direction to try, not measured output improvements.
