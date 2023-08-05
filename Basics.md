# Tags: `headers`, `headings`

Aliases: `header-increment`, `heading-increment`

This rule is triggered when you skip heading levels in a Markdown document, for
example:

```markdown
# Heading 1

### Heading 3

We skipped out a 2nd level heading in this document
```

When using multiple heading levels, nested headings should increase by only one
level at a time:

```markdown
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

## Another Heading 2

### Another Heading 3
```


>this text is inside of a blockquote
- Im a
- Bullet
- List


> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life


# Headings represent the structure of a document and can be confusing
when skipped
# Fenced code block
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Footnote	Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

Heading ID	### My Great Heading {#custom-id}


Definition List	term
: definition


Strikethrough	~~The world is flat.~~


Task List	- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media


Emoji
(see also Copying and Pasting Emoji)	That is so funny! :joy:


Highlight	I need to highlight these ==very important words==.


Subscript	H~2~O


Superscript	X^2^
