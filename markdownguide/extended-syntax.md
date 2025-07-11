# Extended Syntax

## Tables

```markdown
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

```markdown
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |
```

| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |

### Alignment

```markdown
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## Fenced Code Blocks

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Syntax Highlighting

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Footnotes

```markdown
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


## Heading IDs

```markdown
### My Great Heading {#custom-id}
```

### My Great Heading {#custom-id}

### Linking to Heading IDs

```markdown
[Heading IDs](#heading-ids)
```

[Heading IDs](#heading-ids)

## Definition Lists

```markdown
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Strikethrough

```markdown
~~The world is flat.~~ We now know that the world is round.
```

~~The world is flat.~~ We now know that the world is round.

## Task Lists

```markdown
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Emoji

### Copying and Pasting Emoji

```markdown
Gone camping! ⛺ Be back soon.

That is so funny! 😂
```

Gone camping! ⛺ Be back soon.

That is so funny! 😂

### Using Emoji Shortcodes

```markdown
Gone camping! :tent: Be back soon.

That is so funny! :joy:
```

Gone camping! :tent: Be back soon.

That is so funny! :joy:

## Highlight

```markdown
I need to highlight these ==very important words==.
```

I need to highlight these ==very important words==.

```markdown
I need to highlight these <mark>very important words</mark>.
```

I need to highlight these <mark>very important words</mark>.

## Subscript

```markdown
H~2~O
```

H~2~O

```markdown
H<sub>2</sub>O
```

H<sub>2</sub>O

## Superscript

```markdown
X^2^
```

X^2^

```markdown
X<sup>2</sup>
```

X<sup>2</sup>

## Automatic URL Linking

```markdown
https://www.example.com
```

https://www.example.com

## Disabling Automatic URL Linking

```markdown
`https://www.example.com`
```

`https://www.example.com`

