+++
title = "coast sample"
date = 2025-08-19
authors = ["Myxogastria0808"]
[taxonomies]
tags = ["coast"]
+++

Various notation methods are listed below.

# h1

## h2

### h3

#### h4

##### h5

###### h6

# note

{% note() %}
This is a note.
{% end %}

{% tip() %}
This is a tip.
{% end %}

{% important() %}
This is a important.
{% end %}

{% warning() %}
This is a warning.
{% end %}

{% caution() %}
This is a caution.
{% end %}

# Tips

Link

Zola: [Zola Site](https://www.getzola.org/)

Normal

**Bold**

_Italic_

~Strikethrough~

- Bullet List
  - Bullet List
    - Bullet List
- Bullet List

1. Numbered List
   1. Numbered List
      1. Numbered List
2. Numbered List

- [ ] checkbox
- [x] checkbox

> Blockquote

Horizontal

---

katex

$$
\frac{dy}{dx} + p(x) y^2 + q(x) y + r(x) = 0
$$

emoji

:smile:

code block

```rs
fn main() {
    println!("Hello, world!");
}
```

colocation

program file sample: [here](sample.rs).

# mermaid

{% mermaid() %}
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
{% end %}

# image

image with caption

{{ image(path="/content/sample/image.jpg", width=1000, height=200, caption="caption") }}

custom image

{{ image(path="/content/sample/image.jpg", width=100, height=200) }}

image (for vertical image)

{{ image(path="/content/sample/image.jpg", height=200) }}

image (for horizontal image: pattern1)

{{ image(path="/content/sample/image.jpg") }}

image (for horizontal image: pattern2)

{{ image(path="/content/sample/image.jpg", width=300) }}
