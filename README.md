# Processing.py - Avatar Generator

## Picasso Inspired Avatar Generator

![](Avatar_Generator.png)

---

# Overview

This project is a generative art sketch that creates randomized abstract portraits inspired by Picasso-style compositions.

The sketch combines layered image assets such as:

* hair
* eyes
* noses
* lips
* ears
* abstract textures

to generate a unique avatar each time the program runs.

Built using a Processing / Processing.py style graphics environment.

---

# Features

* Randomized portrait generation
* Layered facial feature composition
* Abstract artistic overlays
* Slightly randomized face proportions
* Lightweight and easy to extend
* Picasso-inspired visual style

---

# Canvas Settings

The sketch creates a:

```text
300 x 300
```

pixel canvas with a white background.

---

# How It Works

The script:

1. Draws a randomized face base
2. Loads image assets from predefined arrays
3. Randomly selects facial features
4. Places each feature onto the canvas
5. Produces a unique generated portrait

Each execution creates a different composition.

---

# Randomized Elements

## Abstract Overlays

Top and bottom abstract textures are randomly selected.

Examples:

* `abstract1.png`
* `abstract5.png`
* `abstract7.png`

---

## Hair

Random hairstyle selection:

```text
hair1.png → hair5.png
```

---

## Eyes

Left and right eyes are independently randomized:

```text
eye1.png → eye6.png
```

This increases visual variation.

---

## Nose

Random nose selection:

```text
nose1.png → nose3.png
```

---

## Lips

Random mouth selection:

```text
lips1.png → lips3.png
```

---

## Ears

Randomized left and right ear assets.

---

# File Structure

Example project structure:

```text
project-folder/
│
├── sketch.py
├── Avatar_Generator.png
├── hair1.png
├── hair2.png
├── eye1.png
├── eye2.png
├── nose1.png
├── lips1.png
├── abstract1.png
└── ...
```

All image assets should remain in the same folder as the sketch unless custom paths are added.

---

# Requirements

This sketch requires a Processing-compatible environment supporting:

* `loadImage()`
* `image()`
* `ellipse()`
* `random()`

Recommended environments:

* Processing (Python Mode)
* Processing.py
* p5 adaptations

---

# Running the Sketch

1. Open the sketch in Processing Python Mode
2. Ensure all PNG assets are inside the project folder
3. Run the sketch
4. A new randomized avatar will generate

---

# Customization

The generator can be expanded by:

* adding more facial assets
* introducing color palettes
* randomizing positions and scaling
* adding animation
* exporting generated avatars automatically
* generating avatar collections

---

# Future Improvements

Potential enhancements:

* procedural backgrounds
* rarity systems
* metadata export
* NFT collection generation
* high resolution rendering
* interactive UI controls
* animated portraits

---

# Notes

* PNG transparency is recommended for all assets.
* Layer order affects final appearance.
* Randomization uses uniform probability selection.

---

# Author

Experimental generative art project inspired by abstract portrait composition and Picasso-style aesthetics.
