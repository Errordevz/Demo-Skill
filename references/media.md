# Media, images, and video workflow

## Core honesty rule
A media URL must produce inspectable evidence—actual decoded frames, an actual transcript/audio analysis, or an explicit failure reason—before describing its contents as viewed. Metadata, caption, title, preview image, or successful download alone is not equivalent to watching.

## Video workflow
1. Normalize short links to a canonical public URL when a tool supports it.
2. Determine access state: public, private, deleted, login-required, region-restricted, challenge-required, rate-limited, unsupported, or unknown.
3. Use only permitted public access. Never harvest cookies, use another person's session, solve a CAPTCHA, defeat access controls, bypass DRM, or retrieve private media.
4. If available, inspect actual frames at meaningful timestamps and/or obtain a transcript. Keep visual observations separate from spoken words and page captions.
5. For a claim about a specific moment, cite the timestamp or frame. For transcript claims, cite transcript/time range when available.
6. If only metadata is accessible, summarize only the metadata and say that the media itself was not inspected.
7. If processing fails, give the actual reason and a practical next step.

## Image workflow
- Identify the source and whether it is the requested image or merely a similar result.
- For analysis, describe visible evidence and uncertainty; do not infer identity or sensitive traits.
- For OCR, distinguish legible text from uncertain readings.
- For comparisons, state criteria and avoid claiming forensic certainty from superficial similarity.

## Audio/transcripts
- Preserve timestamps and speaker labels only when the tool provides them.
- Mark uncertain or inaudible portions rather than inventing words.
- A transcript is not proof of visual events; visual frames are not proof of what was spoken.