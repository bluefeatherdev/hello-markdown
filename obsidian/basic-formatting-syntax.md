# Basic formatting syntax

## Paragraph

```markdown
This is a paragraph.

This is anther paragraph.
```
This is a paragraph.

This is anther paragraph.

```markdown
Multiple          adjacent          spaces



and multiple newlines between paragraphs.
```
Multiple          adjacent          spaces



and multiple newlines between paragraphs.

### Line breaks

```markdown
line one
line two
```
line one line two

```markdown
line three__  
line four
```
line three   
line four

```markdown
line five

line six
```
line three   

line four

## Headings

```markdown
# This is a heading 1
## This is a heading 2
### This is a heading 3
#### This is a heading 4
##### This is a heading 5
###### This is a heading 6
```
# This is a heading 1
## This is a heading 2
### This is a heading 3
#### This is a heading 4
##### This is a heading 5
###### This is a heading 6

# Bold, italics, highlights 

```markdown
**Bold text**

__Bold text__

*Italic text*

_Italic text_

~~Striked out text~~

==Highlighted text==

**Bold text and _nested italic_ text**

***Bold and italic text***

___Bold and italic text___
```
**Bold text**

__Bold text__

*Italic text*

_Italic text_

~~Striked out text~~

==Highlighted text==

**Bold text and _nested italic_ text**

***Bold and italic text***

___Bold and italic text___


```markdown
\*\*This line will not be bold\*\*
```
\*\*This line will not be bold\*\*

```markdown
\**This line will be italic and show the asterisks*\*
```
\**This line will be italic and show the asterisks*\*

# Internal links

```markdown
[[Three laws of motion]]
```
[[Three laws of motion]]

```markdown
[Three laws of motion](Three%20laws%20of%20motion.md)
```
[Three laws of motion](Three%20laws%20of%20motion.md)

# External links

```markdown
[Obsidian Help](https://help.obsidian.md)
```
[Obsidian Help](https://help.obsidian.md)

```markdown
[Note](obsidian://open?vault=MainVault&file=Note.md)
```
[Note](obsidian://open?vault=MainVault&file=Note.md)

# Escape blank spaces in links

```markdown
[My Note](obsidian://open?vault=MainVault&file=My%20Note.md)
```
[My Note](obsidian://open?vault=MainVault&file=My%20Note.md)

```markdown
[My Note](<obsidian://open?vault=MainVault&file=My Note.md>)
```
[My Note](<obsidian://open?vault=MainVault&file=My Note.md>)

# External images

```markdown
![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg))
```
![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg))

```markdown
![Engelbart|100x145](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
```
![Engelbart|100x145](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

```markdown
![Engelbart|100](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
```
![Engelbart|100](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

# Quotes

```markdown
> Human beings face ever more complex and urgent problems, and their effectiveness in dealing with these problems is a matter that is critical to the stability and continued progress of society.

\- Doug Engelbart, 1961
```
> Human beings face ever more complex and urgent problems, and their effectiveness in dealing with these problems is a matter that is critical to the stability and continued progress of society.

\- Doug Engelbart, 1961

# Lists

```markdown
- First list item
- Second list item
- Third list item
```
- First list item
- Second list item
- Third list item

```markdown
* First list item
* Second list item
* Third list item
```
* First list item
* Second list item
* Third list item

```markdown
+ First list item
+ Second list item
+ Third list item
```
+ First list item
+ Second list item
+ Third list item

```markdown
1. First list item
2. Second list item
3. Third list item
```
1. First list item
2. Second list item
3. Third list item

```markdown
1) First list item
2) Second list item
3) Third list item
```
1) First list item
2) Second list item
3) Third list item

```markdown
1. First list item
   
2. Second list item
3. Third list item
   
4. Fourth list item
5. Fifth list item
6. Sixth list item
```
1. First list item
   
2. Second list item
3. Third list item
   
4. Fourth list item
5. Fifth list item
6. Sixth list item

# Task lists
```markdown
- [x] This is a completed task.
- [ ] This is an incomplete task.
```
- [x] This is a completed task.
- [ ] This is an incomplete task.

```markdown
- [x] Milk
- [?] Eggs
- [-] Eggs
```
- [x] Milk
- [?] Eggs
- [-] Eggs

# Nesting lists

```markdown
1. First list item
   1. Ordered nested list item
2. Second list item
   - Unordered nested list item
```
1. First list item
   1. Ordered nested list item
2. Second list item
   - Unordered nested list item

```markdown
- [ ] Task item 1
	- [ ] Subtask 1
- [ ] Task item 2
	- [ ] Subtask 1
```
- [ ] Task item 1
	- [ ] Subtask 1
- [ ] Task item 2
	- [ ] Subtask 1

# Horizontal rule

```markdown
***
****
* * *
---
----
- - -
___
____
_ _ _
```
***
****
* * *
---
----
- - -
___
____
_ _ _

# Inline code  

```markdown
Text inside `backticks` on a line will be formatted like code.
```
Text inside `backticks` on a line will be formatted like code.

# Code blocks

```markdown
Text inside `backticks` on a line will be formatted like code.
```
Text inside `backticks` on a line will be formatted like code.

```markdown
Text inside `backticks` on a line will be formatted like code.
```
Text inside `backticks` on a line will be formatted like code.

````markdown
```
cd ~/Desktop
```
````
```
cd ~/Desktop
```

````markdown

~~~
cd ~/Desktop
~~~
````
~~~
cd ~/Desktop
~~~

```markdown
    cd ~/Desktop
```
    cd ~/Desktop

````markdown
```dart
void main() {
  print('Hello World!');
}
```
````
```dart
void main() {
  print('Hello World!');
}
```

# Footnotes

```markdown
This is a simple footnote[^1].

[^1]: This is the referenced text.
[^2]: Add 2 spaces at the start of each new line.
  This lets you write footnotes that span multiple lines.
[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.
```
This is a simple footnote[^1].

[^1]: This is the referenced text.
[^2]: Add 2 spaces at the start of each new line.
  This lets you write footnotes that span multiple lines.
[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.

```markdown
You can also use inline footnotes. ^[This is an inline footnote.]
```
You can also use inline footnotes. ^[This is an inline footnote.]

# Comments

```markdown
This is an %%inline%% comment.

%%
This is a block comment.

Block comments can span multiple lines.
%%
```
This is an %%inline%% comment.

%%
This is a block comment.

Block comments can span multiple lines.
%%

# Escaping Markdown Syntax

```markdown
- Asterisk: \*
- Underscore: \_
- Hashtag: \#
- Backtick: \`
- Pipe (used in tables): \|
- Tilde: \~
```
- Asterisk: \*
- Underscore: \_
- Hashtag: \#
- Backtick: \`
- Pipe (used in tables): \|
- Tilde: \~

```markdown
1\. This won't be a list item.
```
1\. This won't be a list item.
