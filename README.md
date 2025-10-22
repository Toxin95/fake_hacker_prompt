# Fake Hacker Prompt

A simple **hacker-style terminal generator** built with pure HTML, CSS, and JavaScript. This single `index.html` file displays a black screen with neon green text being typed at a configurable speed, with optional speed increase and start delay.

## [Try it on GitHub Pages](https://toxin95.github.io/fake_hacker_prompt/)

## Repository Contents

* `index.html` — main single-file project containing all markup, styles, and logic.
* `README.md` — this documentation file.

## Features

* Type any multiline text to simulate console output.
* Adjustable typing speed (characters per second).
* Optional incremental speed increase (percentage-based):

  * `linear` — increases every second.
  * `perChar` — increases after a set number of characters.
* Configurable start delay (seconds).
* Cursor options: `block`, `bar`, or `none`.
* First line shows without any prefix; subsequent lines display the `>>>` prompt.
* Press **Esc** or the **Exit** button to close the overlay.

## How to Use

1. Download or copy the `index.html` file to your local folder.
2. Open it directly in your browser or host it on a static web server.
3. Type or paste your text, set typing speed, increment options, and start delay, then click **Start**.

### Tips

* Use multiple lines to enable the `>>>` prefix on subsequent lines.
* For a realistic hacking effect, use a slower base speed (30–80 cps) and a slight speed increase over time.

## Customization

* Change the neon color by modifying the CSS variable `--green` in the HTML file.
* Replace the `>>>` prefix by searching for `&gt;&gt;&gt;` in the code and replacing it with any symbol you prefer.
* To port this to React or Vue, extract the JavaScript logic into a component and keep the same CSS.

## License

Free to use and modify for personal or commercial projects. Attribution is appreciated but not required.

## Contact

If you’d like to enhance this project with:

* glitch or distortion effects
* typing sounds
* video export capabilities

feel free to reach out or fork it on GitHub!
