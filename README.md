<div align="center">
 <img src="meta/center_title.png" alt="Mr. Breakfast's Free Prompts" width="500"/>  
</div>

<p align="center">
 <b>Mr. Breakfast's Free Prompts</b> is an input prompt pack with over 400 svg and png assets 
 <br>
 
 <br>
</p>

<div align="center">
 <img src="previews/preview.png" alt="pack preview" width="550"/>
</div>

---

<details>
  <summary><b>🍬 Previews</b></summary>
 
   <img src="previews/generic_preview.png" alt="generic preview"/>
   <img src="previews/keyboard_preview.png" alt="keyboard and mouse preview"/>
   <img src="previews/switch_preview.png" alt="switch preview"/>
   <img src="previews/ps5_preview.png" alt="ps5 preview"/>
   <img src="previews/xbox_preview.png" alt="xbox preview"/>
   <img src="previews/steamdeck_preview.png" alt="steam deck preview"/>

</details>

---

Inspired by the look and freedom of [Kenney](https://kenney.nl/assets/input-prompts-pixel-16) and the freedom of [Xelu's](https://thoseawesomeguys.com/prompts/) free prompts.

Remix the source here, or download and support the pack on [Itch.io](https://mrbreakfastsdelight.itch.io/mr-breakfasts-free-prompts)

### 🛋️ Supports:
- Nintendo Switch
- Xbox Series
- PlayStation™ 5
- Steam Deck
- Generic game pad
- Keyboard and mouse

### 🖌️ How is the Source made?
The source was designed in [Inkscape](https://inkscape.org/). The assets are created with fill gradients, strokes, and the Poppins font. The gradients are locked and globally shared between assets, allowing for easy edits of the dark and light color schemes.

Here's an example of a generic light button:

![image](meta/button_example.png)

And the gradients included so far:

![image](meta/gradient_names.png)

Many of the triggers/bumpers were created using Inkscape's `Corner` live path effect. The keyboard keys have a separate gradient from the buttons for their light and dark schemes.

### ♻️ Contributing Guide

You will need to install the following:

1. [Inkscape](https://inkscape.org/) (version 1.3 or greater recommended)
2. [Poppins font](https://fonts.google.com/specimen/Poppins)

If you intend to submit a pull request, please organize your work under the correct layers, and make sure your paths are properly grouped and named.

Groups begin with the vender name `xbox`, then the name of the button `y`, and then whatever other attributes apply. `color` if it's a colored button, and `dark` or `light` depending on the scheme it follows:

> `vender_title_tags`
> 
> Example: `xbox_y_color_dark`

After you've made your changes, you'll need to update the corresponding files in `~/svg`, `~/png`, svg preview sources in `~/previews/src`, and the exported png previews in `~/previews`.

Before you submit your pull request, make sure to summarize your changes in `CHANGE_NOTES` under the next Itch release.

### 🎂 Who uses these?
So far no one! Want your project featured? Add a link here in the README

### 🛟 I need help! FAQ</summary>
#### I need my PNG to be higher resolution
#### There's no text in the SVG

