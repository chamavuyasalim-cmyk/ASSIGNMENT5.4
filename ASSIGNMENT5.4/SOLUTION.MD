# Assignment 5.4 — CSS Variables & Design Tokens

Aim: To create a small design system using reusable CSS variables for colors, spacing, and font sizes, and apply them to a sample webpage.



## 1. Explanation of CSS variables

CSS variables, also called custom properties, allow us to store reusable values and access them using the `var()` function.

For example:

```
:root {
    --primary-color: #2563eb;
    --spacing-medium: 16px;
    --font-large: 32px;
}

h1 {
    color: var(--primary-color);
    font-size: var(--font-large);
    margin-bottom: var(--spacing-medium);
}
```

| Variable             | Purpose                         |
| -------------------- | ------------------------------- |
| `--primary-color`    | Main blue color for the website |
| `--secondary-color`  | Purple accent color             |
| `--background-color` | Page background                 |
| `--text-color`       | Main text color                 |
| `--spacing-small`    | Small spacing: 8px              |
| `--spacing-medium`   | Medium spacing: 16px            |
| `--spacing-large`    | Large spacing: 32px             |
| `--font-small`       | Small text: 14px                |
| `--font-medium`      | Medium text: 18px               |
| `--font-large`       | Large text: 32px                |


## 2. Result

The webpage demonstrates how CSS variables create a reusable design system. Colors, spacing, and font sizes are defined in `:root` and reused across headings, buttons, cards, and page sections. Updating a variable changes every element that uses it.

## 6. SCREEN SHOT OF WEBSITE
![alt text](<5.4 IMAGE.png>)

