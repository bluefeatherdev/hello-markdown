# Hacks

Workarounds for things not officially supported by Markdown.

## Underline

```markdown
Some of these words <ins>will be underlined</ins>.
```

Some of these words <ins>will be underlined</ins>.

## Indent (Tab)

```markdown
&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.
```

&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.

## Center

```markdown
<center>This text is centered.</center>
```

<center>This text is centered.</center>

<br>

```markdown
<p style="text-align:center">Center this text</p>
```

<p style="text-align:center">Center this text</p>

## Color

```markdown
<font color="red">This text is red!</font>
```

<font color="red">This text is red!</font>

```markdown
<p style="color:blue">Make this text blue.</p>
```

<p style="color:blue">Make this text blue.</p>

## Comments

```markdown
Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: # 

And here's another paragraph that's visible.
```

Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: # 

And here's another paragraph that's visible.

## Admonitions

```markdown
> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.
```

> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.

## Image Size

```markdown
<img src="https://cdn.download.ams.birds.cornell.edu/api/v1/asset/302355171/1800" width="200">
```

<img src="https://cdn.download.ams.birds.cornell.edu/api/v1/asset/302355171/1800" width="200">

## Image Captions

```html
<figure>
    <img src="https://www.markdownguide.org/assets/images/albuquerque.jpg"
         alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>
```

<figure>
    <img src="https://www.markdownguide.org/assets/images/albuquerque.jpg"
         alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>

```markdown
![Albuquerque, New Mexico](https://www.markdownguide.org/assets/images/albuquerque.jpg)
*A single track trail outside of Albuquerque, New Mexico.*
```

![Albuquerque, New Mexico](https://www.markdownguide.org/assets/images/albuquerque.jpg)
*A single track trail outside of Albuquerque, New Mexico.*

## Link Targets

```markdown
<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>
```

<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>

## Symbols

Here’s a partial list of HTML entities for symbols:

```html
- Copyright (`©`) — &copy;
- Registered trademark (`®`) — &reg;
- Trademark (`™`) — &trade;
- Euro (`€`) — &euro;
- Left arrow (`←`) — &larr;
- Up arrow (`↑`) — &uarr;
- Right arrow (`→`) — &rarr;
- Down arrow (`↓`) — &darr;
- Degree (`°`) — &#176;
- Pi (`π`) — &#960;
```

- Copyright (`©`) — &copy;
- Registered trademark (`®`) — &reg;
- Trademark (`™`) — &trade;
- Euro (`€`) — &euro;
- Left arrow (`←`) — &larr;
- Up arrow (`↑`) — &uarr;
- Right arrow (`→`) — &rarr;
- Down arrow (`↓`) — &darr;
- Degree (`°`) — &#176;
- Pi (`π`) — &#960;

## Line Breaks Within Table Cells

```markdown
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |
```

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |

## Lists Within Table Cells

```markdown
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |
```

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

## Table of Contents

```markdown
#### Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)
```

#### Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)

## Videos

```markdown
[![Image alt text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID)
```

[![10 Fun Facts About Blue Jays | Noisy, Beautiful, Interesting](https://img.youtube.com/vi/NPta-zaYnaQ/0.jpg)](https://youtu.be/NPta-zaYnaQ)
