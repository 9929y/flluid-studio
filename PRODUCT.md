# Flluid Studio Product Notes

## Positioning

Flluid Studio is a compact visual-interaction prototype. It is not trying to be a full product; it is useful GitHub evidence because it shows how a visual shader idea can be wrapped in a clear interaction model.

## Product Question

How do you make a fluid shader feel controllable instead of decorative?

The answer in this prototype:

- Put the animated material in one clear object.
- Keep the controls close to the object.
- Use connector motion to show which option is shaping the card.
- Separate motion behavior from color theme.
- Keep keyboard and reduced-motion paths available.

## Yanice's Contribution

Frame the work as adaptation and productization of a source shader-card idea, not as a from-scratch shader engine claim.

Public wording can say:

```text
Flluid Studio adapts a fluid shader card reference into a small interaction prototype with stateful motion/theme controls, animated connectors, responsive layout, and accessibility handling.
```

Avoid:

```text
Original fluid shader invented from scratch.
No source reference.
```

## Publication Checklist

Before making the repo public or pinning it:

1. Keep or rewrite `SOURCE.md` so it clearly credits `napnow/fluid-shader-card`.
2. Check the upstream license and preserve any required notice.
3. Replace the README with `repo_cleanup_source/flluid-studio/README.md`.
4. Inspect `index.html` for source-only paths, non-public asset references, or hidden process comments.
5. Confirm CDN dependencies are acceptable for a public demo repo.
6. Add a screenshot or short GIF only if it shows the prototype itself and generic sample content.

## Recommended Repo Description

WebGL fluid-shader card interaction prototype with motion/theme controls and animated state connectors.

## Suggested Topics

`webgl`, `threejs`, `shader`, `interaction-design`, `creative-coding`, `accessibility`
