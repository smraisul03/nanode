---
title: Nanode Project Bot
date: 2023-02-23T07:21:31.139Z
summary: " "
slides:
  theme: league
  highlight_style: dracula
authors: []
tags:
  - Tutorials
image:
  preview_only: true
  caption: ""
  alt_text: ""
categories: []
---
{{< slide background-image="boards.webp" >}}

# Nanode Bot

by Ariya Seng, S M Raisul Alam Bhuiyan, and Tom Tran.

C﻿SCI 310-01

**D﻿ATE**

- - -

## Introduction

{{< fragment >}} W﻿hat is the Nanode Bot? {﻿{< /fragment >}}

{﻿{ <fragment> }} W﻿hat hardware are we using? {﻿{ </fragment> }}

{{< speaker_note >}}

N﻿anode is an Arduino like 8 bit microcontroller board with integrated Ethernet connectivity.

T﻿he bot portion of the project are the sensors and motors we're using.

H﻿ardware:

Arduino Uno R3

Ultrasonic Sensor Module

GY-521 Module (gyroscope & accelerometers)

Camera Module

Line Tracking Module (ITR200001)

IO Expansion Block

Cell Box (Lithium Ion Battery)

  {{< /speaker_note >}}

- - -

## U﻿ses

W﻿hat are we using the Nanode Bot to demonstrate?

E﻿xplain what we're using the Nanode Bot to demonstrate: camera modules, 

- - -

## Code Highlighting

Inline code: `variable`

Code block:

```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

- - -

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = ;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

- - -

## Fragments

Make content appear incrementally

```
{{</* fragment */>}} $\mathbf{y} =  $ {{</* /fragment */>}}
{{</* fragment */>}} $X\boldsymbol\beta$ {{</* /fragment */>}}
{{</* fragment */>}} $+ \boldsymbol\varepsilon$ {{</* /fragment */>}}
```

Press `Space` to play!

{{< fragment >}} $\mathbf{y} =  $ {{< /fragment >}}
{{< fragment >}} $X\boldsymbol\beta$ {{< /fragment >}}
{{< fragment >}} $+ \boldsymbol\varepsilon$ {{< /fragment >}}

- - -

A fragment can accept two optional parameters:

* `class`: use a custom style (requires definition in custom CSS)
* `weight`: sets the order in which a fragment appears

- - -

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}

- Only the speaker can read these notes
- Press `S` key to view

{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}

* Only the speaker can read these notes
* Press `S` key to view

{{< /speaker_note >}}

- - -

## Themes

* black: Black background, white text, blue links (default)
* white: White background, black text, blue links
* league: Gray background, white text, blue links
* beige: Beige background, dark text, brown links
* sky: Blue background, thin dark text, blue links

- - -

* night: Black background, thick white text, orange links
* serif: Cappuccino background, gray text, brown links
* simple: White background, black text, blue links
* solarized: Cream-colored background, dark green text, blue links

- - -

{{< slide background-image="boards.webp" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="boards.webp" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

- - -

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

- - -

# Questions?

[Ask](https://discord.gg/z8wNYzb)

[Documentation](https://wowchemy.com/docs/content/slides/)