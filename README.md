# Claude Skills Card UI

A sleek **single-file HTML/CSS/JavaScript card UI** inspired by Claude Skills.

The project lives in one file: [`claude-skills-card-ui.html`](./claude-skills-card-ui.html). It creates an interactive 3D card with a dark premium look, glowing gradient shader, subtle grain texture, Claude-style mark, and mouse-follow tilt animation.

---

## UI Preview

> GitHub README files cannot run the JavaScript tilt interaction, but this preview represents the card’s content and layout. Open the HTML file in a browser to see the full 3D hover effect.

<table>
  <tr>
    <td width="420" align="center">
      <br />
      <h3>✳ suraj.dsgn</h3>
      <br />
      <h1>New Claude Skills</h1>
      <p><strong>for UI/UX Engineers</strong></p>
      <br />
      <p>
        Dark interactive card · glowing shader · mouse tilt · responsive layout
      </p>
      <br />
    </td>
  </tr>
</table>

---

## Description

**Claude Skills Card UI** is a standalone HTML project that displays a polished interactive card for UI/UX presentation work. The card is centered on the page and uses CSS variables plus JavaScript mouse tracking to create a smooth 3D tilt effect.

It is useful for experimenting with modern UI cards, hero visuals, landing page concepts, portfolio shots, and animated interface components.

---

## What the UI Includes

- A single responsive card layout
- Dark premium background style
- Orange/red glowing shader gradient
- Subtle SVG noise texture overlay
- Vignette overlay for depth
- Claude-style radial brand mark
- Brand label: `suraj.dsgn`
- Main heading: `New Claude Skills`
- Subtitle: `for UI/UX Engineers`
- Mouse-follow 3D tilt interaction
- Hover glow based on cursor position
- Mobile-friendly sizing with media queries

---

## Built With

- HTML
- CSS
- JavaScript

No React. No Vite. No Tailwind. No dependencies.

---

## File Structure

```text
claude-skills-card-ui/
├── claude-skills-card-ui.html
└── README.md
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/IsaacOdeimor/claude-skills-card-ui.git
```

Open the folder:

```bash
cd claude-skills-card-ui
```

Then open the HTML file directly in your browser:

```bash
claude-skills-card-ui.html
```

You can also double-click the file from your file manager.

---

## How It Works

The card uses CSS custom properties for rotation and cursor light position:

```css
--rx: 0deg;
--ry: 0deg;
--mx: 50%;
--my: 50%;
```

JavaScript listens for mouse movement on the card, calculates the cursor position, and updates the CSS variables. Those values control the `rotateX`, `rotateY`, and hover spotlight effect.

---

## Customization

You can edit the HTML file to change:

- Brand name
- Main heading
- Subtitle
- Card size
- Border radius
- Gradient colors
- Tilt strength
- Font styling
- Shadow intensity
- Mobile layout

For example, the tilt strength is controlled here:

```js
const maxTilt = 10;
```

Increase it for stronger movement or reduce it for a softer hover effect.

---

## Best Use Cases

- UI/UX card experiments
- Portfolio design previews
- Landing page hero cards
- AI product feature cards
- Frontend animation practice
- CSS gradient and shader experiments

---

## License

Add a license file if you want to define how others can use or modify this project.
