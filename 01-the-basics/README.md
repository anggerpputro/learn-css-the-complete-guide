### Inline Styling:

```
<section style="background: #ff2359">
```

### Style Tag:

```
<style>
    section {
        background: #ff2359;
    }
</style>
```

### CSS File:

```
<head>
    <link rel="stylesheet" href="main.css">
</head>
```

### Text Styling:

```
h1 {
    color: white;
    font-family: sans-serif;
}
```

#### Add Google Fonts:

add to tag head

```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">
```

apply to element in css file

```
h1 {
    color: white;
    font-family: "Anton", serif;
}
```

### Selectors

##### 1. Elements:

Set equal style for these elements

```
h1 {
    color: red;
}
```

```
<h1>Our Header</h1>
```

##### 2. Classes:

Set equal style for elements within the same class

```
.blog-post {
    color: red;
}
```

```
<h1 class="blog-post">Our Header</h1>
<p>Paragraph</p>
<h1 class="blog-post">Another Header</h1>
```

##### 3. Universal:

Apply to all elements

```
* {
    color: red;
}
```

```
<h1>Our Header</h1>
<p class="blog-post">The blog post</p>
```

##### 4. IDs:

Set style to one specific element

```
#main-title {
    color: red;
}
```

```
<h1 id="main-title">Our header</h1>
```

##### 5. Attributes:

Set equal styles to all elements with attribute(s)

```
[disabled] {
    color: red;
}
```

```
<button disabled>Click</button>
```
