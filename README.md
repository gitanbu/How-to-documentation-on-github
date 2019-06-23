# How-to-documentation-on-github

# The largest heading
## The second largest heading
###### The smallest heading


**This is bold text**    -> To Make Bold text
*This text is italicized* -> To make Italic words
~~This was mistaken text~~ -> To Make Strike out the words
**This text is _extremely_ important** -> To make Bold and italic word

**Quoting text**

We can quote text with a >.

In the words of Anbazhagan:

> He wants to become All-Rounder


## To format code or text into its own distinct block, use triple backticks.

Some basic Git commands are:
```
git status
git add
git commit
```

## Creating and highlighting code blocks

Share samples of code with fenced code blocks and enabling syntax highlighting.
Fenced code blocks

You can create fenced code blocks by placing triple backticks ``` before and after the code block. We recommend placing a blank line before and after code blocks to make the raw formatting easier to read.

```
function test() {
  console.log("notice the blank line before this function?");
}
```

## Syntax highlighting

You can add an optional language identifier to enable syntax highlighting in your fenced code block.

For example, to syntax highlight Ruby code:

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Lists

You can make an unordered list by preceding one or more lines of text with - or *.

- George Washington
- John Adams
- Thomas Jefferson

To order your list, precede each line with a number.

1. James Madison
2. James Monroe
3. John Quincy Adams



## Task lists

To create a task list, preface list items with a regular space character followed by [ ]. To mark a task as complete, use [x].

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request


## Using emoji

You can add emoji to your writing by typing :EMOJICODE:.

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

Rendered emoji

Typing : will bring up a list of suggested emoji. The list will filter as you type, so once you find the emoji you're looking for, press Tab or Enter to complete the highlighted result.

For a full list of available emoji and codes, check out emoji-cheat-sheet.com.


## Ignoring Markdown formatting

You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.

Let's rename \*our-new-project\* to \*our-old-project\*.


## Creating a table

You can create tables with pipes | and hyphens -. Hyphens are used to create each column's header, while pipes separate each column. You must include a blank line before your table in order for it to correctly render.

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |



Cells can vary in width and do not need to be perfectly aligned within columns. There must be at least three hyphens in each column of the header row.

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

## Formatting content within your table

You can use formatting such as links, inline code blocks, and text styling within your table:

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

You can align text to the left, right, or center of a column by including colons : to the left, right, or on both sides of the hyphens within the header row.

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |


To include a pipe | as content within your cell, use a \ before the pipe:

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |


## For more information

Visit https://help.github.com/en/articles/basic-writing-and-formatting-syntax

## For Emoji

Visit https://www.webfx.com/tools/emoji-cheat-sheet/
