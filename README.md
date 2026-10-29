# tools.rayanupadhyay.com

Handy little tools by Rayan. A grid of tiles on the homepage, each one opening its own tool.

**Live:** [tools.rayanupadhyay.com](https://tools.rayanupadhyay.com)

## Tools

| Tool | Link | What it does |
| --- | --- | --- |
| Pomodoro Timer | `#pomodoro` | Focus timer with short and long breaks, plus a beep when time's up |
| Flashcards | `#flashcards` | Make cards, flip them, shuffle, and quiz yourself |
| Calculator | `#calculator` | Scientific calculator with trig, logs, powers, and keyboard support |
| Typing Test | `#typing` | Words per minute and accuracy in 15, 30, or 60 seconds |
| How Old Am I? | `#age` | Exact age down to the second, plus days until your next birthday |
| Unit Converter | `#units` | Length, weight, temperature, speed, and data |
| Coin & Dice | `#dice` | Flip a coin or roll up to six dice |
| Word Counter | `#words` | Words, characters, sentences, reading time, and word limits |
| Color Picker | `#color` | Pick a color and copy its hex, RGB, or HSL code |
| Reaction Time | `#reaction` | Click when the box lights up and see your time in milliseconds |
| Case Changer | `#case` | UPPERCASE, lowercase, Title Case, camelCase, snake_case, kebab-case |
| Base Converter | `#base` | Binary, octal, decimal, and hex |

Every tool has its own link, so you can send someone straight to one, like `tools.rayanupadhyay.com#typing`.

## Saving

Flashcards, pomodoro settings, your birthday, and best scores are saved in the browser with `localStorage`. They stay on that device only and nothing is sent anywhere.

## Adding a tool

1. Add a tile inside `.grid` with `href="#yourtool"` and give it its own class for styling.
2. Add a `<section class="win" data-tool="yourtool" hidden>` with the tool's controls.
3. Add a title and one-line description to `TITLES` in the script.
4. Add colors and a font for its banner with a `#toolView[data-active="yourtool"]` rule in the CSS.

## Tech

One `index.html` file. Plain HTML, CSS, and JavaScript with no frameworks or build step. Fonts from Google Fonts. Hosted on Vercel.# Tools
