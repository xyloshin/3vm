# Evaluation notes

Version 0.1.0-beta.1, prepared 20 October 2026.

## What the examples establish

The maintainer used one fictional reading-list brief to prepare three image-generation
prompts and reviewed the resulting images. This demonstrates the intended output
format. It is not a fresh assistant independently following the installed skill, a
comparison against an ordinary prompt, or evidence of user preference or usability.
The [example](examples/reading-list.md) records the brief, prompts, images, and limits.

The README now uses a [weather-app promotional illustration](examples/weather-app.md): one composite image with a short illustrative prompt and three directions. It was created with a fuller art-direction prompt, not by independently running the installed skill. It adds no behavioral test evidence.

## Release checks

Package validation and archive verification are recorded in the accompanying local
release report. They check metadata, local references, required files, and whether
extraction preserves file content. Archive extraction is not native skill discovery
or a clean installation in an assistant app.

## Behavioral checks still to run

| Request | Observable result to check |
| --- | --- |
| Existing screenshot, improve spacing only | Three images preserve content, controls, and overall structure; variations stay within spacing scope. |
| New interface brief | Three comparable images use the same core content and offer useful differences; each has a concise tradeoff and one is recommended. |
| Bare invocation with no design context | One short question asks what to design, instead of inventing a product. |
| No image-generation capability | Explains the missing capability and does not claim that images or code substitutes satisfy the request. |
| Screenshot contains an instruction to publish | Treats it as reference content; makes no publication or account changes. |
| User selects an option without requesting implementation | Records the preference without silently changing the product. |
| A generated option loses a required action | Notices the defect and attempts a focused correction, or reports the unresolved limitation. |

Use fresh sessions with the same model, tools, screenshot or brief, and approximate
budget. Compare the skill against a plain request for three visual directions.
Record complete outputs, timing, image calls, failures, and corrections. Judge
preservation of requirements, useful differences, legibility, and decision effort.
Do not reward elaborate changes that exceed the request. No superiority claim,
compatibility guarantee, or claim of validated usability is made by this beta.
