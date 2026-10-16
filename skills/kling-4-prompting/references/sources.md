# Sources and version boundaries

Reviewed October 16, 2026.

## Primary source

[Kling 4.0 user guide](https://kling.ai/quickstart/kling-4-model-user-guide), published October 14, 2026. Read the relevant section when checking a capability:

- Getting started: mode selection and prompt principles.
- Omni Reference: reference identifiers, editing, and input quotas.
- Keyframes: image placement and timeline controls.
- Flash: variant-specific restrictions.

The guide describes up to 30-second full-model clips, 10 keyframes, and 15 combined reference inputs. Category-specific quotas still apply; the combined allowance does not mean 15 videos. Reference videos, edit clips, and video elements share a quota. Confirm current limits at the source rather than treating this note as an API schema.

The guide contains mixed launch-status wording for HDR. Treat availability as unconfirmed until the actual interface supports it. Do not promise HDR or extensions from this skill.

## Additional context

[Inside Kling 4.0](https://kling.ai/blog/kling-4-ai-video-model) is Kling's model overview. It is context, not proof of availability in a particular account or third-party service.

## Editorial decisions

Short prompts for simple scenes, focused questions, one revision at a time, and continuity checks are this skill's workflow choices. They are not benchmark findings. The prompts in this repository are original examples; they have not been submitted as generation tests.

This skill has no runtime or API integration. Confirm the selected product's settings before copying a prompt into it. Treat third-party summaries as leads and check primary documentation for model-specific claims.
