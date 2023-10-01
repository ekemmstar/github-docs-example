# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation(')
```
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5 and print the result
result = factorial(5)
puts "Factorial of 5 is #{result}"

```
when you can you should attempt to apply syntax highlighting your codeblocks
```ruby
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5 and print the result
result = factorial(5)
puts "Factorial of 5 is #{result}"

<img width="200px" src="https://github.com/ekemmstar/github-docs-example/assets/103825682/0839480d-3f79-4f4b-aa20-26be50f46fcf "/>

Good Cloud Engineers use codeblocks for both code and Errors that appear in the console.
```bash
TypeError: no implicit conversion of Integer into String
```
> Here is an example of using a codeblock for an error that appears in bash

## Step 3 - Use Github Flavoured Markdown Task Lists
Github extends Markdown to have a list where you can check off items. <sup>[3]</sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Opt)
GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`|:cloud: |
| Cloud with Lightning| `:cloud_with_lightning`|🌩️ |

## Step 5 - How to create a Table

You can use the followwing markdown format to create tables
```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`|:cloud: |
| Cloud with Lightning| `:cloud_with_lightning`|🌩️ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formattiing options.[<sup>[5]</sup>](#external-references)
## External References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[1]</sup>
- [Basic writing and formatting syntax(Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images0)<sup>[2]</sup>
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- [GFM - Emoji](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extension)](https://github.github.com/gfm/#tables-extension-)
