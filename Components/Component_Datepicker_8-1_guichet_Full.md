```html
<div class="form-group field-error">
  <div class="form-group-label">
    <label for="date">Label (JJ/MM/AAAA)<span class="field-required">*</span></label>
    <div class="tooltip">
      <button type="button" aria-label="Help on date label field" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Exemple et aide non-essentiel à propos du champ date</p>
      </div>
    </div>
  </div>
  <div class="form-group-field">
    <input id="date" name="datefield" type="text" aria-describedby="desc-date error-date" aria-invalid="true">
    <div class="alert alert--info" id="desc-date">
      <p>Message d'aide</p>
    </div>
    <div class="alert alert--error" id="error-date">
      <p class="error">Message d'erreur</p>
    </div>
  </div>
</div>
```