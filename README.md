# Welcome to Coders' Haven

This website will include our tutorials, and other files which may prove beneficial for those starting to learn how to code

This website will be located [here](https://maanuj-vora.github.io/Coders-Haven/)

If you have any suggestions, or would like to propose a new idea/coding language to implement/a better name, open a new issue

---

## Contribution Guidelines

### Editing Paths

Files to be edited will be in the path `/content/`

`/content/menu/index.md` is where the the sidebar's information will be written into

`/content/folder/` is the directory where the information of different coding languages will be kept in

---

### Ethics

Please do not include any deragatory terms in any way, shape or form. Ever.

Advertising your own products is also frowned upon. Make this website resource that others would highly recommend

---

## Contributors

If you have a friend, or know someone who would like to contribute to this project and does not have access, you can send me a direct message on discord to `Rainbwsep#4828` or contact me through any other medians

---

## References

This website is heavily built upon [Hugo Book](https://themes.gohugo.io/hugo-book/) as well as the [Hugo Framework](https://gohugo.io/) itself

---

## In-Built Cool Stuff

### Buttons

```tpl
{{< button href="https://maanuj-vora.github.io/" >}}Visit{{< /button >}}
```

---

### Columns

```html
{{< columns >}} <!-- begin columns block -->
# Left Column
Old

<---> <!-- invisible seperator -->

# Middle Column
Mc.

<---> <!-- invisible seperator -->

# Right Column
Donald
{{< /columns >}}
```

---

### Expanding Content

```tpl
{{< details title="Question" open=false >}}
### Answer
Explanation
{{< /details >}}
```
```tpl
{{< expand "Question" "..." >}}
### Answer
Explanation
{{< /expand >}}
```

---

### Hints

```tpl
{{< hint [info|warning|danger] >}}
### This is not a joke. Python is bae
{{< /hint >}}
```

---

### KaTex

Helps in rendering math formulas and stuff

Inline Example
```latex
{{< katex >}}\pi(x){{< /katex >}}
```

Block Example
```latex
{{< katex display >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}
```

---

### Mermaid

This helps in the generation of flow charts and svg charts

```tpl
{{< mermaid >}}
sequenceDiagram
Ash Ketchum->>Professor Oak: Hello Professor, can I get my pokémon
alt is late
Professor Oak->>Ash Ketchum: Here is Pikachu, shoo shoo
else is on time
Professor Oak->>Ash Ketchum: Of course Ash, you can choose between these three pokémon
end
opt Extra response
Professor Oak->>Ash Ketchum: Goodluck on your journey
end
{{< /mermaid >}}
```

---

### Tabs
```markdown
{{< tabs "uniqueid" >}}
{{< tab "Bulbasaur" >}} The Grass-Type Pokémon {{< /tab >}}
{{< tab "Squirtle" >}} The Water-Type Pokémon {{< /tab >}}
{{< tab "Charmandar" >}} The Fire-Type Pokémon {{< /tab >}}
{{< /tabs >}}
```

---
