# C# Knowledge Map — light and dark themes

Open `index.html` in a modern desktop or mobile browser. No framework, image, or network access is required.

## Color theme

Use the appearance button (moon icon) in the top-right corner to choose **System**, **Light**, or **Dark**.

- System follows your device's light/dark appearance preference.
- Light and Dark override the device preference.
- JavaScript stores your selection in localStorage when supported.
- In JavaScript-restricted previews, the CSS-based selection and static mind map remain available.

Theme colors are stored as `--t-*` CSS variables under the `/* Theme tokens */` comment.
Topic data remains inside the `TOPICS` constant, and the diagram is rendered with SVG elements.
