# References and editing

Use this note when the user supplies multiple assets or wants to change footage.

## Decide what each asset contributes

Make a short mapping before drafting. Distinguish identity, clothing, product geometry, room layout, action, camera, pacing, style, and voice. A reference may contribute only one of these. A room photo should not accidentally become a character reference.

Inspect accessible media. If media cannot be inspected, use the user's description explicitly; do not pretend to have seen it. Preserve supplied order. When labels are unknown, ask for the interface mapping or write a draft using clearly marked placeholders.

Kling's guide uses upload-ordered labels such as @Image1 and @Video1. Assign each a specific role. For targeted footage changes, use `Edit @Video1`; a motion reference belongs to a generation brief instead. See [sources](sources.md).

## Define the scope of an edit

Identify the primary clip and the object of the change. Specify exactly which traits are replaced and which continue across frames. For example, changing a coat's color should leave the actor's face, coat shape, gestures, and camera framing alone.

When the user wants character replacement, ask which character if several are present. Preserve only what the request requires. If the replacement image conflicts with the source pose or crop, flag the mismatch rather than promising a perfect substitution.

For sound, ask whether it should be retained when that affects the work. Don't promise untouched source audio from a generated result. If exact sound preservation matters, suggest retaining the original audio in the final edit.

## Example assignment

Assume the user confirms:

- @Video1 is the walking shot to edit.
- @Image1 shows the replacement coat.

Original teaching prompt:

```text
Edit @Video1. Give the walking actor the olive waxed-cotton coat
shown in @Image1, including its broad collar and brass snaps.
Keep the actor's face, hair, trousers, walking rhythm, and hand
positions consistent with the source clip. Keep the street,
lighting, shot duration, and camera path consistent with @Video1.
The coat creases naturally at the elbows as the actor walks.
```

These labels are illustrative. Use the actual upload mapping in a user's prompt.
