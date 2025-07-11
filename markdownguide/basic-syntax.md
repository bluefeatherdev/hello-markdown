# Basic Syntax

--- 

```markdown
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

---

```markdown
Heading level 1
===============

Heading level 2
---------------
```

Heading level 1
===============

Heading level 2
---------------

---

# Heading Best Practices

```markdown
Try to put a blank line before...

# Heading

...and after a heading.
```

---

# Paragraphs

```markdown
I really like using Markdown.

I think I'll use it to format all of my documents from now on
```

I really like using Markdown.

I think I'll use it to format all of my documents from now on

## Paragraph Best Practices

```markdown
Don't put tabs or spaces in front of your paragraphs.

Keep lines left-aligned like this.
```

Don't put tabs or spaces in front of your paragraphs.

Keep lines left-aligned like this.

# Line Breaks

```markdown
This is the first line.  
And this is the second line.
```

This is the first line.  
And this is the second line.

## Line Break Best Practices

```markdown
First line with two spaces after.  
And the next line.

First line with the HTML tag after.<br>
And the next line.
```

First line with two spaces after.  
And the next line.

First line with the HTML tag after.<br>
And the next line.

# Emphasis

## Bold

```markdown
I just love **bold text**.

I just love __bold text__.

Love**is**bold

### Bold Best Practices

Love**is**bold
```

I just love **bold text**.

I just love __bold text__.

Love**is**bold

### Bold Best Practices

```markdown
Love**is**bold
```

Love**is**bold

## Italic

```markdown
Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow
```

Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

### Italic Best Practices

```markdown
A*cat*meow
```

A*cat*meow

## Bold and Italic

```markdown
This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.

This is really***very***important text.
```

This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.

This is really***very***important text.

### Bold and Italic Best Practices

```markdown
This is really***very***important text.
```

This is really***very***important text.

# Blockquotes

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
```

> Dorothy followed her through many of the beautiful rooms in her castle.

## Blockquotes with Multiple Paragraphs

```markdown
beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Nested Blockquotes

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Blockquotes with Other Elements

```markdown
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

## Blockquotes Best Practices

```markdown
Try to put a blank line before...

> This is a blockquote

...and after a blockquote.
```

Try to put a blank line before...

> This is a blockquote

...and after a blockquote.

# Lists

## Ordered Lists

```markdown
1. First item
2. Second item
3. Third item
4. Fourth item
```

1. First item
2. Second item
3. Third item
4. Fourth item

<br>

```markdown
1. First item
1. Second item
1. Third item
1. Fourth item
```

1. First item
1. Second item
1. Third item
1. Fourth item

<br>

```markdown
1. First item
8. Second item
3. Third item
5. Fourth item
```

1. First item
8. Second item
3. Third item
5. Fourth item

<br>

```markdown
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
```

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

### Ordered List Best Practices

```markdown
1. First item
2. Second item
```

1. First item
2. Second item

## Unordered Lists

```markdown
- First item
- Second item
- Third item
- Fourth item
```

- First item
- Second item
- Third item
- Fourth item

<br>

```markdown
* First item
* Second item
* Third item
* Fourth item
```

* First item
* Second item
* Third item
* Fourth item

<br>

```markdown
+ First item
+ Second item
+ Third item
+ Fourth item
```

+ First item
+ Second item
+ Third item
+ Fourth item

<br>

```markdown
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

### Starting Unordered List Items With Numbers

```markdown
- 1968\. A great year!
- I think 1969 was second best.
```

- 1968\. A great year!
- I think 1969 was second best.

### Unordered List Best Practices

```markdown
- First item
- Second item
- Third item
- Fourth item
```

- First item
- Second item
- Third item
- Fourth item

## Adding Elements in Lists

### Paragraphs

```markdown
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.
```

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### Blockquotes

```markdown
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.
```

* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

### Code Blocks

```markdown
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.
```

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

### Images

```markdown
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](https://www.markdownguide.org/assets/images/tux.png)

3. Close the file.
```

1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](https://www.markdownguide.org/assets/images/tux.png)

3. Close the file.

### Lists

```markdown
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
```

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

# Code

```markdown
At the command prompt, type `nano`.
```

At the command prompt, type `nano`.

## Escaping Backticks

```markdown
``Use `code` in your Markdown file.``
```

``Use `code` in your Markdown file.``

## Code Blocks

```markdown
    <html>
      <head>
      </head>
    </html>
```

    <html>
      <head>
      </head>
    </html>

# Horizontal Rules

```markdown
***

---

_________________
```

***

---

_________________


## Horizontal Rule Best Practices

```markdown
Try to put a blank line before...

---

...and after a horizontal rule.
```

Try to put a blank line before...

---

...and after a horizontal rule.

# Links

```markdown
My favorite search engine is [Google](https://google.com).
```

My favorite search engine is [Google](https://google.com).

## Adding Titles

```markdown
My favorite search engine is [Google](https://google.com "The most popular search engine on the world!").
```

My favorite search engine is [Google](https://google.com "The most popular search engine on the world!").

## URLs and Email Addresses

```markdown
<https://www.markdownguide.org>

<fake@example.com>
```

<https://www.markdownguide.org>

<fake@example.com>

## Formatting Links

```markdown
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```

I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).


## Reference-style Links

### Formatting the First Part of the Link

```markdown
[hobbit-hole][1]
[hobbit-hole] [1]
```

[hobbit-hole][1]
[hobbit-hole] [1]

### Formatting the Second Part of the Link

```markdown
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
```

[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

### An Example Putting the Parts Together

```markdown
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.
```

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

```markdown
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

## Link Best Practices

```markdown
[link](https://www.example.com/my%20great%20page)

<a href="https://www.example.com/my great page">link</a>
```

[link](https://www.example.com/my%20great%20page)

<a href="https://www.example.com/my great page">link</a>

<br>

```markdown
[a novel](https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_%28novel%29)

<a href="https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_(novel)">a novel</a>
```

[a novel](https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_%28novel%29)

<a href="https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_(novel)">a novel</a>

# Images

```markdown
![The San Juan Mountains are beautiful!](https://www.markdownguide.org//assets/images/san-juan-mountains.jpg "San Juan Mountains")
```

![The San Juan Mountains are beautiful!](https://www.markdownguide.org//assets/images/san-juan-mountains.jpg "San Juan Mountains")

## Linking Images

```markdown
![A Beautiful Blue Jay](https://cdn.download.ams.birds.cornell.edu/api/v1/asset/302355171/1800 "A Beautiful Blue Jay by ebird.org")
```

![A Beautiful Blue Jay](https://cdn.download.ams.birds.cornell.edu/api/v1/asset/302355171/1800 "A Beautiful Blue Jay by ebird.org")

# Escaping Characters

```markdown
\* Without the backslash, this would be a bullet in an unordered list.
```

\* Without the backslash, this would be a bullet in an unordered list.

## Characters You Can Escape

| Character | Name                                        |
|-----------|---------------------------------------------|
| `\`       | backslash                                   |
| `` ` ``   | backtick *(see also escaping backticks)*    |
| `*`       | asterisk                                    |
| `_`       | underscore                                  |
| `{}`      | curly braces                                |
| `[]`      | brackets                                    |
| `<>`      | angle brackets                              |
| `()`      | parentheses                                 |
| `#`       | pound sign                                  |
| `+`       | plus sign                                   |
| `-`       | minus sign *(hyphen)*                       |
| `.`       | dot                                         |
| `!`       | exclamation mark                            |
| `|`       | pipe *(see also escaping pipe in tables)*   |

# HTML

```markdown
This **word** is bold. This <em>word</em> is italic.
```

This **word** is bold. This <em>word</em> is italic.

## HTML Best Practices

For security reasons, not all Markdown applications support HTML in Markdown documents. When in doubt, check your Markdown application’s documentation. Some applications support only a subset of HTML tags.

Use blank lines to separate block-level HTML elements like `<div>`, `<table>`, `<pre>`, and `<p>` from the surrounding content. Try not to indent the tags with tabs or spaces — that can interfere with the formatting.

You can’t use Markdown syntax inside block-level HTML tags. For example, `<p>italic and **bold**</p>` won’t work.
