# Markdown Syntax Guide

This file is a quick reference for core Markdown 
cd ~/cse103_lab/LAB3/my_first_repo
pwd
cat > MARKDOWN_GUIDE.md << 'EOF'
# Markdown Syntax Guide

This file is a quick reference for core Markdown syntax.

# Heading 1 (largest)
## Heading 2
### Heading 3

## Text Formatting

**Bold text**, *Italic text*, ~~Strikethrough~~

## Lists

Unordered list:

- Item A
- Item B
  - Nested item B1 (indent with 2 spaces)

Ordered list:

1. First step
2. Second step

## Code

Inline code: `print("Hello")`

Fenced code block (use the language name for syntax highlighting):

```python
def greet(name):
    return f"Hello, {name}!"
```

## Links

Hyperlink: [GitHub](https://github.com)

## Table

| Column 1 | Column 2 | Column 3 |
|----------|:--------:|---------:|
| Left     | Centre   | Right    |

## Blockquote

> An important note or reference goes here.

## Horizontal Divider

---

End of guide.
