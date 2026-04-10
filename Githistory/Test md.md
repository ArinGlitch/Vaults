# Sample Markdown Test File

This file is meant to test **common Markdown features** and a **TypeScript code block**.

---

## 1. Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4

---

## 2. Text Formatting

This is **bold** text.  
This is *italic* text.  
This is ***bold and italic*** text.  
This is ~~strikethrough~~ text.  
This is `inline code`.

---

## 3. Lists

### Unordered List
- Item one
- Item two
  - Nested item
  - Another nested item
- Item three

### Ordered List
1. First item
2. Second item
3. Third item

### Task List
- [x] Write markdown
- [x] Add TypeScript block
- [ ] Test rendering

---

## 4. Blockquote

> This is a blockquote.
>
> It can span multiple lines.

---

## 5. Link and Image

[OpenAI](https://openai.com)

![Sample image alt text](https://via.placeholder.com/300x120.png?text=Markdown+Image)

---

## 6. Table

| Feature    | Supported | Notes                  |
|------------|-----------|------------------------|
| Headings   | Yes       | Multiple levels        |
| Lists      | Yes       | Ordered and unordered  |
| Tables     | Yes       | Great for structure    |
| Code block | Yes       | Including TypeScript   |

---

## 7. Horizontal Rule

Below is another separator:

---

## 8. Collapsible Section

<details>
  <summary>Click to expand</summary>

  This is hidden content inside a collapsible section.

  You can put **Markdown** here too.

</details>

---

## 9. TypeScript Example

```ts
type User = {
  id: number;
  name: string;
  email?: string;
};

function greet(user: User): string {
  return `Hello, ${user.name}!`;
}

const currentUser: User = {
  id: 1,
  name: "Aaryan",
  email: "aaryan@example.com",
};

console.log(greet(currentUser));
```

## 10. JSON Example
```json
{
  "name": "sample-markdown",
  "version": "1.0.0",
  "enabled": true
}
```

## 11. Nested Markdown Content

Here is a mixed example:

- **Bold item**
    
- _Italic item_
    
- `Code item`
    
- [Link item](https://example.com)![Attachment.tiff](file:///Attachment.tiff)

## 12. Footnote

Here is a statement with a footnote.[^1]
  
[^1]: This is the footnote content.

## 13. Final Note

That should cover most Markdown rendering cases for testing.