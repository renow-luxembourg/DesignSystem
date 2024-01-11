```html
<details class="cmp-accordion">
  <summary class="cmp-accordion__summary" tabindex="-1">
    <h3 class="cmp-accordion__header">Accordion heading</h3>
  </summary>
  <div class="cmp-accordion__panel">
    <p>Contenu initialement masqué</p>
  </div>
</details>

<style>
details summary[tabindex="-1"] {
  pointer-events: none;
  user-select: none;
}
</style>
```