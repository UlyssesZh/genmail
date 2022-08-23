---
layout: mail
math: true
---

Dear Ulysses,

````md

# Title $math$

en dash: 1--2

em dash---like

---

'quotes' "quotes" "you're evil"

| table | table |
| --- | --- |
| content 1 | content 2 |
| content 3 | content 4 |

- [ ] foo
- [x] bar

Some $x^2/2$

Other inline math: $\frac12$

$$x^2-2px+q=0.$$

$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}.$$

```latex
dollar $$math$$
$math$ won't be rendered inside code block
```

```js
// ---------------------------------------------------------------
// helper functions
// ---------------------------------------------------------------
function styleSheetLoaded(styleSheet) {
  var sheets     = document.styleSheets,
      stylesheet = sheets[(sheets.length - 1)];
  // find CSS file 'styleSheetName' in document
  for(var i in document.styleSheets) {
    if(sheets[i].href && sheets[i].href.indexOf(styleSheet) > -1) {
      return true;;
    }
  }
}
```
````

# Title $math$

en dash: 1--2

em dash---like

---

'quotes' "quotes" "you're evil"

| table | table |
| --- | --- |
| content 1 | content 2 |
| content 3 | content 4 |

- [ ] foo
- [x] bar

Some $x^2/2$

Other inline math: $\frac12$

$$x^2-2px+q=0.$$

$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}.$$

```latex
dollar $$math$$
$math$ won't be rendered inside code block
```

```js
// ---------------------------------------------------------------
// helper functions
// ---------------------------------------------------------------
function styleSheetLoaded(styleSheet) {
  var sheets     = document.styleSheets,
      stylesheet = sheets[(sheets.length - 1)];
  // find CSS file 'styleSheetName' in document
  for(var i in document.styleSheets) {
    if(sheets[i].href && sheets[i].href.indexOf(styleSheet) > -1) {
      return true;;
    }
  }
}
```

Best regards,
{% include google_sig.html %}
