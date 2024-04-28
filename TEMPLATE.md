# Chapter Title

<div custom-style="SP - Editorial">
Anything here goes inside an editorial block with appropriate styling.
</div>

A **_keyword_** styles like that. We have **bold** and _italics_ text. We also have `inline code` and [https://gpuweb.github.io/gpuweb/](https://gpuweb.github.io/gpuweb/) links.

<div custom-style="P - Callout Heading">
Important Note
</div>
<div custom-style="P - Callout">
This callout should be preceded by an "Important Note" heading with appropriate styling.
</div>

## Styles

### Lists

#### Ordered Lists with Code Block

1. A list
2. With code block as part of list

    ```
    let a = 1;
    let b = 1;
    ```

3. This item should start with "3" no matter what number is put at start due to ordered list syntax in Markdown.

#### Unordered Lists

* A list
* With code block as part of list

    ```
    let a = 1;
    let b = 1;
    if (a === b) {
        console.log("Equal");
    }
    ```
* This item should start with a bullet point no matter what is put at start due to unordered list syntax in Markdown.

### Image with Caption

![](https://raw.githubusercontent.com/gpuweb/gpuweb/main/logo/webgpu.png)

<!-- Local images also work -->

<div custom-style="IMG - Caption">
Figure a0.b0: A figure
</div>

### Table with Caption

| Column 1 | Column 2 |
|-|-|
| Column 1 Row 1 | Column 2 Row 1 |

<div custom-style="IMG - Caption">
Figure a0.b1: A table
</div>

### Code Block

```
let a = 1;
let b = 1;
if (a === b) {
    console.log("Equal");
}
```
