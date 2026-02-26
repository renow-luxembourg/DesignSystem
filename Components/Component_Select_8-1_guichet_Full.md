```html
<div class="form-group field-error">
  <div class="form-group-label">
    <label for="select">Label<span class="field-required">*</span></label>
    <div class="tooltip">
      <button type="button" aria-label="Aide sur le champ Label" title="Aide sur le champ Label" class="tooltip-btn">i</button>
      <div class="tooltip-content" role="status">
        <p>Exemple et aide non-essentielle à propos du champ</p>
      </div>
    </div>
  </div>
  <div class="form-group-field">
    <select id="select" name="select" class="form-field" aria-describedby="desc-select error-select" aria-invalid="true" required>
      <option value="" selected disabled hidden>Sélectionner une option</option>
      <option value="option1">Option 1</option>
      <option value="option2">Option 2</option>
      <option value="option3">Option 3</option>
    </select>
    <div class="alert alert--info" id="desc-select">
      <p>Message d'aide</p>
    </div>
    <div class="alert alert--error" id="error-select">
      <p class="error">Message d'erreur</p>
    </div>
  </div>
</div>
```
