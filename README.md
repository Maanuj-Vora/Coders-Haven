# Welcome to Coders' Haven

This website will include our tutorials, and other files which may prove beneficial for those starting to learn how to code

This website will be located [here](https://maanuj-vora.github.io/Coders-Haven/)

If you have any suggestions, or would like to propose a new idea/coding language to implement/a better name, open a new issue

---

### Script Status

![Floppy Disk or Save Icon](https://github.com/Maanuj-Vora/Coders-Haven/workflows/Floppy%20Disk%20or%20Save%20Icon/badge.svg)

![Contributing to the Contributors](https://github.com/Maanuj-Vora/Coders-Haven/workflows/Contributing%20to%20the%20Contributors/badge.svg)

---

### Editing Paths

Files to be edited will be in the path `/content/docs/`
`/content/menu/index.md` is where the the sidebar's information will be written into

`/content/docs/<language>/` is the directory where the information of different coding languages will be kept in

---

### Contributors
<html><table><tr><td align="center"><a href=https://github.com/Maanuj-Vora><img src=https://avatars1.githubusercontent.com/u/31610859?v=4 width="50;" alt=Maanuj Vora/><br /><sub style="font-size:14px"><b>Maanuj Vora</b></sub></a></td><td align="center"><a href=https://github.com/apps/github-actions><img src=https://avatars2.githubusercontent.com/in/15368?v=4 width="50;" alt=apps/github-actions/><br /><sub style="font-size:14px"><b>apps/github-actions</b></sub></a></td><td align="center"><a href=https://github.com/actions-user><img src=https://avatars1.githubusercontent.com/u/65916846?v=4 width="50;" alt=actions-user/><br /><sub style="font-size:14px"><b>actions-user</b></sub></a></td></tr></table></html>


---

## References

This website is heavily built upon [Hugo Book](https://themes.gohugo.io/hugo-book/) as well as the [Hugo Framework](https://gohugo.io/) itself

---

## In-Built Cool Stuff

### Buttons

``` tpl
{{< button href="https://maanuj-vora.github.io/" >}}Visit{{< /button >}}
```

---

### Columns

``` html
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

``` tpl
{{< details title="Question" open=false >}}

### Answer

Explanation
{{< /details >}}
```

``` tpl
{{< expand "Question" "..." >}}

### Answer

Explanation
{{< /expand >}}
```

---

### Hints

``` tpl
{{< hint [info|warning|danger] >}}

### This is not a joke. Python is bae

{{< /hint >}}
```

---

### KaTex

Helps in rendering math formulas and stuff

Inline Example

``` latex
{{< katex >}}\pi(x){{< /katex >}}
```

Block Example

``` latex
{{< katex display >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}
```

---

### Mermaid

This helps in the generation of flow charts and svg charts

``` tpl
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

``` markdown
{{< tabs "uniqueid" >}}
{{< tab "Bulbasaur" >}} The Grass-Type Pokémon {{< /tab >}}
{{< tab "Squirtle" >}} The Water-Type Pokémon {{< /tab >}}
{{< tab "Charmandar" >}} The Fire-Type Pokémon {{< /tab >}}
{{< /tabs >}}
```

---
