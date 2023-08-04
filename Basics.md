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

# Headings represent the structure of a document and can be confusing
when skipped
