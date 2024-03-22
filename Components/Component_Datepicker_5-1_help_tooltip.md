```html
<div class="form-group">
  <div class="form-group-label">
    <label for="datefield">Date de l'évènement<label>
    <div class="tooltip">
      <button type="button" class="tooltip-btn" aria-label="Help on Date field" title="Help on Date field" aria-expanded="false" aria-controls="tooltip-content">i</button>
      <div id="tooltip-content" class="tooltip-content">
        <p>La date doit être postérieure à la date du jour</p>
      </div>
    </div>
  </div>
  <div class="form-group-field">
    <input id="datefield" name="datefield" type="date" aria-describedby="tooltip-content">
  </div>
</div>
```