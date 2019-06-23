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

