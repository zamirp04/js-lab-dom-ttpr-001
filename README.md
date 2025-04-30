<p align="center">
  <img src="img/domplaygroundmini.png?auto=format&fit=crop&w=1200&q=80" alt="Colorful dice tumbling" width="600">
</p>

# DOM Playground – Dark-Mode Toggle

A quick lab to practice **DOM selection**, **event handling**, and class-based theming. Build a button that flips the page between a normal (light) palette and a dark palette.

---

## Learning Goals

- Select elements with `document.querySelector` / `getElementById`
- Attach listeners via `addEventListener`
- Toggle a class on `<body>` using `classList.toggle()`
- Organize work with clear, incremental Git commits

---

## Starter Files

Clone this repo (or download these three files) into the same folder. The HTML and CSS are finished; you will edit **`main.js`** only.

## ## 🔍 Hints & Resources

- **MDN → `Element.classList.toggle()`** – discover the one-liner that adds or removes a class.
- **DevTools Console tip:** open your page, then run `document.body.classList.toggle('dark')` to see the style flip before you write any code.
- **`aria-pressed` attribute** – MDN’s `aria` docs show how to keep your button accessible by updating this value each click.
- **Local Storage** – (Optional) check MDN’s “Using the Web Storage API” to persist the user’s theme choice across refreshes.
