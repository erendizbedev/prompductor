# Prompductor

AI Music Prompt Engineering Studio for Suno and Udio.

Prompductor is a guided, step-by-step studio that helps you craft high-quality prompts for AI music generators such as Suno and Udio. Choose a genre, tune tempo and mood, define vocal and production details, and receive a ready-to-use style prompt and lyrics structure in one place.

## Features

- Two-stage prompt engine: builds a structured Suno/Udio-compatible style prompt in a first stage, then refines production, vocal and effects details in a second stage.
- Bilingual interface: full Turkish (TR) and English (EN) support with a one-click language switch.
- Farabi makam integration: optional Turkish makam selection for music rooted in the makam tradition.
- Accessible high-contrast UI: pure black background designed to reduce glare and eye strain, with clear focus states and large touch targets.
- Screen reader friendly: semantic structure, ARIA roles and labels, and live region status updates for TalkBack and other assistive technologies.
- Web Audio feedback: subtle, dependency-free click and confirmation tones generated with the Web Audio API.
- Single file: the entire application ships as one self-contained HTML file with no build step and no external dependencies.

## Getting Started

No installation is required.

1. Open the live site or download index.html.
2. Open the file in any modern browser (Chrome, Edge, Firefox, Safari).
3. Follow the five steps: Genre, Tempo and Mood, Vocals, Production, and Prompt.
4. Copy the generated Sound Prompt and Lyrics with the copy buttons.

## Usage Flow

1. Genre: select the primary music category.
2. Tempo and Mood: set BPM and emotional atmosphere.
3. Vocals: choose vocal or instrumental production and related vocal techniques.
4. Production: select mix characteristics, scenario, makam and note preferences.
5. Prompt: review, copy, and paste the output into Suno or Udio.

## Accessibility

Prompductor follows accessibility-first principles:

- Pure black (#000000) base with high-contrast text to minimize photophobia discomfort.
- Visible focus indicators and keyboard-operable controls.
- Semantic markup and ARIA attributes compatible with TalkBack on Android and VoiceOver on iOS.
- Motion respects the prefers-reduced-motion setting.

## Project Structure

index.html    The complete application (markup, styles, and scripts).
README.md     Project documentation.

## Deployment

The site is published with GitHub Pages from the root of the main branch.

## Tech Stack

- HTML5, CSS3, and vanilla JavaScript
- Web Audio API for interface sounds
- GitHub Pages for hosting

## Contributing

Issues and pull requests are welcome. Please keep changes consistent with the single-file architecture and the accessibility guidelines above.

## License

All rights reserved unless a license file is added to this repository.
