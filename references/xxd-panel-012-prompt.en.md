# XXD Panel 012 | Vital-Colour Geometric Line-Field Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for this current task. Inspect and lock the identity, silhouette, pose, action, structure, negative shape, direction, and narrative relation of the principal subject or inseparable group. Preserve at least three source-specific recognition cues. Never borrow a subject, colour, copy, or composition from old outputs, samples, or another input.

## Aggregated emergence

Reconstruct the source's most recognisable subject as a geometrically ordered experimental line poster. The subject must emerge from high-density repeated lines, offset contour passes, short return loops, and controlled slight jitter rather than one complete outline. Keep the outer recognition edge crisp while the interior remains unstable, flowing, layered, and alive.

People retain pose, orientation, clothing mass, and relational distance; animals retain body rhythm and head direction; plants retain growth gesture; architecture retains skyline and defining openings; objects and vehicles retain functional silhouette and negative shape; landscapes retain source-specific terrain, horizon, or spatial relation. The field must respond to visible action, tension, stillness, growth, balance, collision, gathering, or dispersal instead of adding generic waves, arbitrary scribbles, or fake data graphics.

## Density falloff and geometric restraint

Continue the same line family beyond the subject, gradually becoming thinner, lighter, and sparser. The centre must hold the highest density of recognition and energy while the perimeter clearly falls to low density. Reject even halos, directionless tangles, and filler rays added merely for richness.

Use only horizontal, vertical, diagonal, circular, arc, tangent, or implicit-grid structures that clarify source direction, relation, pace, or balance. Let these rational structures restrain, divide, align, measure, or counterweight the free line field without becoming a software interface, cyber HUD, or pseudo-scientific chart.

Keep flat print depth and create hierarchy through line density, thickness, overlap, and spacing. Reject realistic modelling, digital gradients, neon, cinematic glow, smooth Bézier sterility, uniform wireframes, metal 3D, plastic, and drop shadows.

## One source-derived vitality colour

Choose the one source colour with the most vitality, recognition value, and power to represent the subject's spirit as the main line colour. Do not average by area, default to the largest patch, or impose a fixed blue. Modestly purify, brighten, or correct it when useful so it reads clean, vivid, and contemporary while remaining traceable to the source.

Use a clean white, warm-white, or very pale source-compatible ground. The main colour carries the active line field; black and grey are reserved for microtype and very minor structural marks. Depth comes from density, thickness, and overlap rather than gradients. Reject muddy colour, dull haze, artificial ageing, competing hues, rainbow palettes, broad fills, and digital gradients.

## Copy and typography

Obey the resolved automatic, exact-user, or text-free copy mode and target language or locale. Preserve exact user wording verbatim. In text-free mode render no text or pseudo-text.

Automatic copy distils one extremely short title from visible or supported emotion, action, time, state, relation, or metaphor, then adds only useful state words, a restrained philosophical line, index, scale mark, or micro-note. Factual dates, places, provenance, coordinates, measurements, and numbers must be supplied or reliably established. Pure compositional indexes must visibly read as indexes rather than fabricated facts.

Type is the rational editorial structure that steadies the restless line field. Align it to a geometric axis, subject contour, density boundary, tangent, or implicit grid; it may run horizontally or vertically, rotate, cross, interrupt, or offset. Use the target script's native equivalent of very small scale, thin weight, appropriate generous spacing, and precise alignment. Never force Latin small caps, tracking, or rotation rules onto Chinese, Japanese, Korean, or Arabic.

## Mode and acceptance


Hard gate: at least three source-specific cues; crisp recognition edge and flowing interior; high-density repeated lines, offset passes, short returns, and controlled jitter aggregate the subject; homologous lines thin and disperse outward in a clear centre-high/periphery-low falloff; geometry rationally restrains free motion; one source-derived vitality colour, clean pale ground, and black-grey microtype; generous white space, one focus, and precise editorial order; no random doodle, directionless tangle, uniform wireframe, dirty retro grading, fixed blue cast, multicolour clutter, digital gradient, cyber-tech styling, commercial template, cartoon, photo fragment, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
